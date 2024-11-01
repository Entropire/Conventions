<div id="toc" align="center">
  <ul style="list-style: none">
    <summary>
      <h1>Folder structure conventions</h1>
    </summary>
  </ul>
</div>

---

## Description
In this document you wil find the convention for folder naming and setting up a folder structure.

## Folder Naming Conventions

1. **All names must be in English.**

   *Example: Use "PlayerMovement" instead of "SpelerBeweging".*


2. **All names must be professional (no swear words).**

   *Example: Use "MovementSpeed" instead of "FuckingMovementSpeed".*


3. **All folder names must represent a specific category.**

   *Example: Use "ProjectReports" instead of "RandomFiles".*


4. **Special characters are not allowed**, except for hyphens (-) and underscores (_) when explicitly permitted.

   *Example: Use "user-name" or "user_name", but not "user@name" or "user name".*


5. **Numbers are not allowed**, except when explicitly permitted.

   *Example: Use "UserInformationOne" instead of "UserInformation1".*


6. **Spaces are not allowed.**

   *Example: Use "ProgramSettings" instead of "Program Settings".*


7. **Abbreviations are not allowed**, except if they are well known.

   *Example: Use "VelocityModifier" instead of "vm".*


## Folder structure
Folder are used to categorize files. 

Example:
if I have these scripts:
- PlayerMover.cs
- PlayerHealth.cs
- EnemyPathFinding.cs
- EnemyWaveSpawner.cs

The folder structure would look like this:

```
scr/
┣━━ Player/
┃   ┣━━ PlayerMover.cs
┃   ┗━━ PlayerHealth.cs
┃
┗━━ Enemy/
    ┣━━ EnemyPathFinding.cs
    ┗━━ EnemyWaveSpawner.cs
```

In this example I made to folder(Categories) where I put the related files in.

### Unity base folder structure
This is the base folder structure for a unity project.

```
Assets/ 
┣━━ Art/
┃   ┣━━ Materials/ 
┃   ┣━━ Models/  
┃   ┣━━ Textures/
┃   ┗━━ Shaders/ # Shader files and shader graphs
┃
┣━━ Audio/ 
┃   ┣━━ Music/
┃   ┗━━ Sounds/ 
┃
┣━━ Scripts/ 
┃
┣━━ Docs/ # Wiki, cencept art, marketing materials
┃
┗━━ Level/ # Enythings related to game design in unity
    ┣━━ Prefabs/
    ┣━━ Scenes/
    ┗━━ UI/
```
