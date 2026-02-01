+------------------------------------------------------------+
|           * Kaptan Yosun's WorldEditor Renewal *           |
+------------------------------------------------------------+

+--------------------------------------------+---------------+
| General Information                        | Version       |
+--------------------------------------------+---------------+
| Base                                       | [Mainline]    |
| DirectX                                    | [9]           |
| Granny                                     | [2.11.8]      |
| DevIL                                      | [1.8.0 Static]|
+--------------------------------------------+---------------+

+------------------------------------------------------------+
|                       * Bug Fixes *                        |
+------------------------------------------------------------+
[YOSUN_WORLDEDITOR_FIX_001]        : Fixes crash when a .spt SpeedTree model is selected on brush.

+------------------------------------------------------------+
|                         * HOW TO *                         |
+------------------------------------------------------------+
Copy WorldEditor folder to your Client Source directory.
Open your Client Solution in Visual Sudio.
Right click on solution > Add > Existing Project
Select WorldEditor.vcxproj
Done.

NOTE: I don't have a PRTerrainlib, instead I use TerrainLib directory only.
So don't forget to edit WorldEditor.vcxproj file to target correct vcxproj locations.

Now you must have a D:\ disc. I recommed you to spare 20GB from your main disc and create a D:\ disc.
Copy your "ymir work" folder from your pack to D:\
Copy all DLL's inside D_Disc folder to D:\
Copy all your maps, textureset, property folders to D:\

Now compile and run WorldEditor_Debug_Win32.exe in D:\