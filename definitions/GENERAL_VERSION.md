# Versions
All projects following the same version structure from now on *(now is 2022-04-21)*.
The structure looks like this: `MASTER.MINOR.PATCH-BUILD`. Every word is a different variable. 
The variable is a number that changes if a project has changed by a certain degree, which is described in the following table:

| Name     | Definition                                                                                                                                           |
|----------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| `MASTER` | Master changes, if some fundamental structure has been changed. Something like, redid the hole System in a new way, so that the access is different. |
| `MINOR`  | Minor changes, if some big changes happened, like added a new system to the engine or added multiplayer to a game.                                   |
| `PATCH`  | Patch changes, if some small changes happened. For example a bug fix, a new feature and other small stuff.                                           |
| `BUILD`  | Build changes, every time the code is changed but it is in the process to the next patch.                                                            |

### Examples

| What happened?                                      | New Version |
|-----------------------------------------------------|:-----------:|
| Started the project                                 |  `1.0.0-0`  |
| Working on a new tree code.                         |  `1.0.1-1`  |
| Added a new tree that grow 5% faster.               |  `1.0.1-1`  |
| Started to code a AI Enemy, testing first code.     |  `1.0.2-2`  |
| Changed the behavior                                |  `1.0.2-3`  |
| Fixed bugs                                          |  `1.0.2-4`  |
| Shipped version                                     |  `1.0.2-4`  |
| ... a lots of changes later ... (Added multiplayer) | `1.1.0-153` |
