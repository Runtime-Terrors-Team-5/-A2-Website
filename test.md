# Testing

This page contains the tests performed either generated from the software or performed manually. Details on the methods and further evidence can be found in our software testing report:
[Test2.pdf](/deliverables/Test2.pdf)


## Coverage Report

Generated from automated testing tooling 

![CoverageReport.png](/test/CoverageReport.png)

## Automatic Tests:

Includes snippits of codes with results, or links to the code where appropriate

| Automatic Test              | Functional Requirement  |
|-----------------------------|-------------------------|
| [T_WinScreen.png](/test/T_WinScreen.png)| FR_SCORE_TRACKING | 
| [T_SaveLoadA.png](/test/T_SaveLoadA.png)| FR_SAVE_GAME            | 
| [T_MachineAndInventory](https://github.com/Runtime-Terrors-Team-5/-A2-Active-Repo/blob/main/PiazzaPanic1/PiazzaPanic1-main/core/src/com/neves6/piazzapanic/AllMachinesTest.java)| FR_ITEM_REMOVAL |
| [T_MachineAndInventory.png](/test/T_MachineAndInventory.png)| FR_ITEM_REMOVAL |
| [T_UnlockStations.png](/test/T_UnlockStations.png)| FR_PROGRESS |
| [T_PowerupA](https://github.com/Runtime-Terrors-Team-5/-A2-Active-Repo/blob/main/PiazzaPanic1/PiazzaPanic1-main/core/src/com/neves6/piazzapanic/poweruptest.java)| FR_DIFFICULTY |
| [T_PowerupA.png](/test/T_PowerupA.png)| FR_DIFFICULTY | 
| [T_Customers.png](/test/T_Customers.png)| FR_CUSTOMER_ARRIVAL     |
| [T_LevelDifficulty.png](/test/T_LevelDifficulty.png)| FR_INCREASED_DIFFICULTY |
| [T_Recipes.png](/test/T_Recipes.png)| FR_RECIPE_PRIORITY      |
| [T_Assessment1Machines.png](/test/T_Recipes.png)| FR_RECIPE_PRIORITY      |
| [T_Tilemap_.png](/test/T_Tilemap.png)| FR_FIXED_LAYOUT         |
| [T_OS.png](/test/T_OS.png)| FR_FLEXIBLE_OS          |

## Manual Tests:

Covers manual test-cases, designed to test parts of code not covered by automatic tests

| Manual Test                 | Functional Requirement  | Justification          |
|-----------------------------|-------------------------|------------------------|
| [T_SaveLoadM.png](/test/T_SaveLoadM.png)| FR_SAVE_GAME | Additional testing along with automatic testing to ensure feature works |
| [T_TutorialM.png](/test/T_TutorialM.png)| FR_DISPLAY_TUTORIAL, FR_TUTORIAL_SKIP | It is important for a human to test the tutorial to ensure it is suitable for gameplay |
| [T_PowerupM.png](/test/T_PowerupM.png)| FR_DIFFICULY, FR_REPUTATION_POINTS | Involves collsion with randomly spawning powerups and thus need to test user cabability to do so |
| [T_CustomerDisplayM.png](/test/T_CustomerDisplayM.png)| FR_RECIPE_DISPLAY, FR_ACTION_TIMER_BAR | Visual changes that benefit the user, need checking manually as they are random |
| [T_DurationTimer.png](/test/T_DurationTimer.png)| FR_DURATION_TIMER       | Can accurately ensure that the time is updated each second manually |

[← back to deliverables](/deliverables.md)

[← back to main page](/README.md)
