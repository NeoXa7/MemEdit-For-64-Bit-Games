                                                                  C# App Usage
// This Dll is Primiarly Used for creating cheats for video game.

//Getting Started
Open Visual Studio and make a new  project.
Add Project reference to MemEdit.dll.
Project » Add Reference » Browse… » Select MemEdit.dll
Check if your game requires 64bit compiling.
Raise app privileges.
                                                                  
//Place using statement above namespace.
using MemEdit;

//Create a namespace for MemEdit in your class.
memEdit memEdit = new memEdit("cs2");


