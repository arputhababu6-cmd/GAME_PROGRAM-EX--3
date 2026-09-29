# GAME_PROGRAM-EX--3

## Aim
To replace the default third person character mesh with a custom skeletal mesh and apply new animations using an animation blueprint.

## Procedure
Import New Character Mesh and Animations:

In the Content Browser, import a new Skeletal Mesh along with its Animations (FBX files).
Ensure the mesh is rigged correctly (ideally to the UE4 Mannequin Skeleton or compatible with it).
Replace Character Mesh:

Open the ThirdPersonCharacter Blueprint (usually found in ThirdPersonBP/Blueprints).
Select the Mesh component.
In the Details Panel, change the Skeletal Mesh to the newly imported mesh.
Set Animation Blueprint:

If available, assign a matching Animation Blueprint in the Details Panel under the Animation section.
If not available, create one:
Right-click in the Content Browser → Animation → Animation Blueprint.
Choose the correct skeleton.
In the AnimGraph, set up state machines or direct animation nodes.
Compile and save.
Preview and Test:

Place the character in the level.
Press Play to test idle, walk, and run animations based on character movement.

## Output:
<img width="843" height="577" alt="image" src="https://github.com/user-attachments/assets/e2ada635-2975-4d5b-8923-bd695adc90b3" />
<img width="476" height="420" alt="image" src="https://github.com/user-attachments/assets/cd3a2b68-64e4-4292-b6dc-673f5e481a24" />
<img width="1541" height="912" alt="image" src="https://github.com/user-attachments/assets/90f08381-c659-4725-845f-a90c245dacd4" />

## Result:

Thus Changing the third-person character mesh and adding animations is implemented Successfully.
