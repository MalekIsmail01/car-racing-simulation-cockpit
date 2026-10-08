# Unity scripts

This folder contains two scripts from the cockpit's Unity project:

- `Assets/Scripts/CarController.cs` handles the simulated car's steering, throttle, braking and wheel movement.
- `Assets/Scripts/cameracontroller.cs` follows the car in the simulation.

The scripts are from a project created with **Unity 2021.3.26f1**. The package manifest and editor version are included for reference.

This is a code sample, not a complete playable Unity project: scenes and third-party EasyRoads3D and MapMagic assets are not included. The original car controller also had a stray `&` that prevented it from compiling; that typo has been corrected here.
