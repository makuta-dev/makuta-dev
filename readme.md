```cpp
#ifndef DEVELOPER_CORE_H
#define DEVELOPER_CORE_H

/**
 * @project  The Journey to Systems Programming
 * @version  0.0.1-alpha (Early Access)
 * @status   Booting...
 */

#include <iostream>
#include <vector>

class AspiringDev {
public:
    // --- Profile Metadata ---
    const char* player_name = "Maks Makuta";
    const char* class_type  = "Game/System Developer";
    int level               = 3;
    float xp_multiplier     = 1.25f; // Buff: High Curiosity

    // --- System Requirements (My Toolbox) ---
    struct Environment {
        std::string os      = "Arch Linux | Android";
        std::string editor  = "CLion";
        std::string toolchain = "GCC / Clang / CMake";
    };

    // --- Skill Tree: Unlocked Nodes ---
    void GetSkillTree() {
        std::vector<std::string> unlocked = {
            "Variable_Types", "Control_Flow", 
            "Basic_Arrays",   "Function_Overloading",
            "Logic_Gates",    "CLI_Navigation"
        };
        
        for(auto& skill : unlocked) {
            std::cout << "[UNLOCKED]: " << skill << std::endl;
        }
    }

    // --- Achievements ---
    enum class Achievements {
        HELLO_WORLD_MASTER,    // Completed
        SEGFAULT_SURVIVOR,     // In Progress
        MEMORY_LEAK_HUNTER,    // Locked
        OPTIMIZATION_WIZARD    // Locked
    };
};

#endif // DEVELOPER_CORE_H

```

---

### 🏆 Developer Stats (The HUD)

| Attribute | Level | Progress |
| --- | --- | --- |
| **C++ Syntax** | `[▓▓▓░░░░░░░]` | 30% - Learning OOP |
| **Problem Solving** | `[▓▓▓▓░░░░░░]` | 40% - Logic Building |
| **Memory Management** | `[▓░░░░░░░░░]` | 10% - Reading about Pointers |
| **Game Math** | `[▓▓░░░░░░░░]` | 20% - Vectors & Coords |

---
