# Build KorFin ReleaseTest

Started: 2026-01-02 11:04:14.411791

```
###############################################################################
# ReGenerate Library 6.0 - (C) 2015-2026 A+S Consult GmbH FuE
###############################################################################
PATH_TO_REGENERATE 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/'
Initial arguments: 'build(Platform:X64,Style:ReleaseTest,prj:KorFin) close'
Executing initial Command 'build' with Arguments '{:Platform=>"X64", :Style=>"ReleaseTest", :prj=>"KorFin"}'...
###############################################################################
...............................................................................
Auto detected source path '_korfin/xe.raumspline/'.
Scanning 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/_korfin/xe.raumspline/'...
Collect Project 'djinee.full|Style:ReleaseTest|Platform:X64|PSheme:Sentinel|Runtime:Native Runtime'
Collect Project 'bagel|Style:ReleaseTest|Platform:X64|PSheme:Sentinel|Runtime:Native Runtime'
Generate projects............................
1.913sec to create VS projects........
1.310sec to create XE projects
Localize Projects...............
0.353sec to localize projects
Building
Building project 'KorFin|Style:ReleaseTest|Platform:X64|PSheme:Sentinel|Runtime:Native Runtime'
000.........|.........|.........|.........|.........|.........|.........|.........
001.........|.........|.........|.........|
Building project 'djinee.full|Style:ReleaseTest|Platform:X64|PSheme:Sentinel|Runtime:Native Runtime'
000.........|.........|.........|.........|.........|.........|.........|.........
001.........|.........|.........|.........|.........|.........|.........|.........
002.........|.........|.........|.........|.........|.........|.........|.........
003.........|.........|.........|.........|.........|.........|.........|.........
004.........|.........|.........|...

.............................................................................
MSBuild /m /t:Build /p:Configuration="reltest";Platform="x64" C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj /p:PreferredToolArchitecture=x64
.............................................................................

**********************************************************************
** Visual Studio 2022 Developer Command Prompt v17.14.14
** Copyright (c) 2025 Microsoft Corporation
**********************************************************************
[vcvarsall.bat] Environment initialized for: 'x64'
MSBuild-Version 17.14.23+b0019275e fÃ¼r .NET Framework
Der Buildvorgang wurde am 02.01.2026 11:04:43 gestartet.

     1>Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" auf Knoten "1", Build Ziel(e).
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\sentinel\sentinel.vcxproj" (3) auf Knoten "4" (Standardziele).
     3>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\sentinel_x64_release_sentinel\\sentinel.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\sentinel_x64_release_sentinel\\sentinel.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       ClCompile:
         Alle Ausgaben sind aktuell.
       Lib:
         Alle Ausgaben sind aktuell.
         sentinel.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\sentinel.x64.lib
       FinalizeBuildStatus:
         Die Datei "..\..\obj\sentinel_x64_release_sentinel\\sentinel.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\sentinel_x64_release_sentinel\\sentinel.tlog\sentinel.lastbuildstate".
     3>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\sentinel\sentinel.vcxproj" ist abgeschlossen (Standardziele).
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\stone\stone.vcxproj" (5) auf Knoten "7" (Standardziele).
     5>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\stone_x64_release_sentinel\\stone.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\stone_x64_release_sentinel\\stone.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\quell\quell.vcxproj" (6) auf Knoten "3" (Standardziele).
     6>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\quell_x64_release_sentinel\\quell.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\quell_x64_release_sentinel\\quell.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       Compile_SAL:
         Compiling Save and Load '..\..\..\..\..\_next\fusion2\code\quell\sal\base.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\building.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cables.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cloud.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cycle.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\framework.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\geology.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\geometry.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\kfmnext.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\korfin_container.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\leistungsverzeichnis.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\object_tree.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\power.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\projects.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\route.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\test.sal'...
         ..\..\..\..\..\regenerate\ruby\bin\ruby.exe ..\..\..\..\..\regenerate\tools\sal.rb --projectDir=C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\quell\ --files ..\..\..\..\..\_next\fusion2\code\quell\sal\base.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\building.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cables.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cloud.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\cycle.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\framework.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\geology.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\geometry.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\kfmnext.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\korfin_container.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\leistungsverzeichnis.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\object_tree.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\power.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\projects.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\route.sal;..\..\..\..\..\_next\fusion2\code\quell\sal\test.sal
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\ramp\ramp.vcxproj" (7) auf Knoten "10" (Standardziele).
     7>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\ramp_x64_release_sentinel\\ramp.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\ramp_x64_release_sentinel\\ramp.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/ramp/sr_ramp/protection_codemeter.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/ramp/sr_ramp/protection_sentinel.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/ramp/sr_ramp/runtime.ids
         :VCEnd
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\park\park.vcxproj" (8) auf Knoten "8" (Standardziele).
     8>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
     5>ClCompile:
         Alle Ausgaben sind aktuell.
     8>InitializeBuildStatus:
         "..\..\obj\park_x64_release_sentinel\\park.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\park_x64_release_sentinel\\park.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/park/sr_park/api_cycle.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/park/sr_park/geodesy.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/park/sr_park/korfin_sdk.ids
         :VCEnd
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\nine\nine.vcxproj" (9) auf Knoten "9" (Standardziele).
     9>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\nine_x64_release_sentinel\\nine.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\nine_x64_release_sentinel\\nine.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das Ziel "SHADER_Compile_ToCode" wird Ã¼bersprungen, da alle Ausgabedateien hinsichtlich der Eingabedateien aktuell sind.
     5>ClCompile:
         Alle Ausgaben sind aktuell.
       Lib:
         Alle Ausgaben sind aktuell.
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\ogis\ogis.vcxproj" (10) auf Knoten "5" (Standardziele).
    10>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\ogis_x64_release_sentinel\\ogis.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\ogis_x64_release_sentinel\\ogis.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/ogis/sr_ogis/ogis.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/ogis/sr_ogis/route.ids
         :VCEnd
     5>Lib:
         stone.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.stone.x64.lib
     9>ClCompile:
         Alle Ausgaben sind aktuell.
     5>FinalizeBuildStatus:
         Die Datei "..\..\obj\stone_x64_release_sentinel\\stone.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\stone_x64_release_sentinel\\stone.tlog\stone.lastbuildstate".
     5>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\stone\stone.vcxproj" ist abgeschlossen (Standardziele).
     7>ClCompile:
         Alle Ausgaben sind aktuell.
     9>ClCompile:
         Alle Ausgaben sind aktuell.
       Lib:
         Alle Ausgaben sind aktuell.
     7>ClCompile:
         Alle Ausgaben sind aktuell.
     8>ClCompile:
         Alle Ausgaben sind aktuell.
     9>Lib:
         nine.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.nine.x64.lib
     7>Lib:
         Alle Ausgaben sind aktuell.
         ramp.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.ramp.x64.lib
     9>FinalizeBuildStatus:
         Die Datei "..\..\obj\nine_x64_release_sentinel\\nine.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\nine_x64_release_sentinel\\nine.tlog\nine.lastbuildstate".
     9>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\nine\nine.vcxproj" ist abgeschlossen (Standardziele).
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\grand\grand.vcxproj" (4) auf Knoten "6" (Standardziele).
     4>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
     7>FinalizeBuildStatus:
         Die Datei "..\..\obj\ramp_x64_release_sentinel\\ramp.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\ramp_x64_release_sentinel\\ramp.tlog\ramp.lastbuildstate".
     4>InitializeBuildStatus:
         "..\..\obj\grand_x64_release_sentinel\\grand.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\grand_x64_release_sentinel\\grand.tlog\unsuccessfulbuild".
     7>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\ramp\ramp.vcxproj" ist abgeschlossen (Standardziele).
     4>SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/grand/sr_grand/grand_framework.ids
         :VCEnd
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\dust\dust.vcxproj" (11) auf Knoten "2" (Standardziele).
    11>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\dust_x64_release_sentinel\\dust.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\dust_x64_release_sentinel\\dust.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/bim_commands.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/cycle.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/dust_framework.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/dust_profileeditor.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/ground.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/kfm_next.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/kfmnext.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/pointcloud.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/power.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/routes.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/sonic.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/tetrahedron.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/dust/sr_dust/vegetation.ids
         :VCEnd
     1>Das Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (1) erstellt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\drain\drain.vcxproj" (2) auf Knoten "1" (Standardziele).
     2>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         "..\..\obj\drain_x64_release_sentinel\\drain.tlog\unsuccessfulbuild" wird erstellt, da "AlwaysCreate" angegeben wurde.
         Aktualisieren des Timestamps von "..\..\obj\drain_x64_release_sentinel\\drain.tlog\unsuccessfulbuild".
     8>ClCompile:
         Alle Ausgaben sind aktuell.
     2>SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
    10>ClCompile:
         Alle Ausgaben sind aktuell.
     8>Lib:
         Alle Ausgaben sind aktuell.
         park.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.park.x64.lib
       FinalizeBuildStatus:
         Die Datei "..\..\obj\park_x64_release_sentinel\\park.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\park_x64_release_sentinel\\park.tlog\park.lastbuildstate".
     8>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\park\park.vcxproj" ist abgeschlossen (Standardziele).
     2>ClCompile:
         Alle Ausgaben sind aktuell.
    10>ClCompile:
         Alle Ausgaben sind aktuell.
     4>ClCompile:
         Alle Ausgaben sind aktuell.
     2>ClCompile:
         Alle Ausgaben sind aktuell.
     4>ClCompile:
         Alle Ausgaben sind aktuell.
     2>Lib:
         Alle Ausgaben sind aktuell.
         drain.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.drain.x64.lib
     4>Lib:
         Alle Ausgaben sind aktuell.
         grand.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.grand.x64.lib
       FinalizeBuildStatus:
         Die Datei "..\..\obj\grand_x64_release_sentinel\\grand.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\grand_x64_release_sentinel\\grand.tlog\grand.lastbuildstate".
     2>FinalizeBuildStatus:
         Die Datei "..\..\obj\drain_x64_release_sentinel\\drain.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\drain_x64_release_sentinel\\drain.tlog\drain.lastbuildstate".
     2>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\drain\drain.vcxproj" ist abgeschlossen (Standardziele).
     4>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\grand\grand.vcxproj" ist abgeschlossen (Standardziele).
    10>Lib:
         Alle Ausgaben sind aktuell.
    11>ClCompile:
         Alle Ausgaben sind aktuell.
    10>Lib:
         ogis.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.ogis.x64.lib
       FinalizeBuildStatus:
         Die Datei "..\..\obj\ogis_x64_release_sentinel\\ogis.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\ogis_x64_release_sentinel\\ogis.tlog\ogis.lastbuildstate".
    10>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\ogis\ogis.vcxproj" ist abgeschlossen (Standardziele).
    11>ClCompile:
         Alle Ausgaben sind aktuell.
       Lib:
         Alle Ausgaben sind aktuell.
     6>Compile_SAL:
         -------------------------------------------------------------------------
         Save&Load Compiler.
         -------------------------------------------------------------------------
       PreBuildEvent:
         C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/tools/loca.exe -generateTokenFiles -idsFiles C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/quell/sr_quell/enums.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/quell/sr_quell/quell_framework.ids C:/Users/ThomasBeutlich/source/repos/Korfin_3/_next/fusion2/code/quell/sr_quell/quell_protocol.ids
         :VCEnd
    11>Lib:
         dust.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.dust.x64.lib
     6>ClCompile:
         Alle Ausgaben sind aktuell.
    11>FinalizeBuildStatus:
         Die Datei "..\..\obj\dust_x64_release_sentinel\\dust.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\dust_x64_release_sentinel\\dust.tlog\dust.lastbuildstate".
    11>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\dust\dust.vcxproj" ist abgeschlossen (Standardziele).
     6>ClCompile:
         Alle Ausgaben sind aktuell.
       Lib:
         Alle Ausgaben sind aktuell.
         quell.vcxproj -> C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.quell.x64.lib
       FinalizeBuildStatus:
         Die Datei "..\..\obj\quell_x64_release_sentinel\\quell.tlog\unsuccessfulbuild" wird gelÃ¶scht.
         Aktualisieren des Timestamps von "..\..\obj\quell_x64_release_sentinel\\quell.tlog\quell.lastbuildstate".
     6>Die Erstellung von Projekt "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\quell\quell.vcxproj" ist abgeschlossen (Standardziele).
     1>PrepareForBuild:
         Die strukturierte Ausgabe ist aktiviert. Die Formatierung der Compilerdiagnose spiegelt die Fehlerhierarchie wider. Weitere Informationen finden Sie unter https://aka.ms/cpp/structured-output.
       InitializeBuildStatus:
         Aktualisieren des Timestamps von "..\..\obj\djinee.full_x64_release_sentinel\\djinee.full.tlog\unsuccessfulbuild".
       SHADER_Compile_ToCode:
       Das SHADER_Compile_ToCode-Ziel wird Ã¼bersprungen, da es keine Eingaben besitzt.
       Compile_Djinee_Export:
         Djinee Sources '..\..\..\..\..\_next\fusion2\code\djinee\_other\bridge.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\card.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\cinema.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\collaboration.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\cycle.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\dgmtex.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\geopkg.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\ifc.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\knp.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\landxml.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\magis.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\plan.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\points.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\port_base.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\reporter.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\shape.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\sonic.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\vissim.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_design.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_energy_definitions.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_inventory.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\enums.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\env.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\images.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\io.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\loca.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\log.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\primitive_math.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\primitive_types.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\tangle_store.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\_framework.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\_framework_core.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\bagel.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\bim.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\comp_properties.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\database.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\geodesy.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\korfin_resources.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\korfin_sdk.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\apluss_obj.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\engine_fusion.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\engine_kfe.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\geometry.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\media.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\pet.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_areas.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_buildings.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_datenaustausch.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_georef_images.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_gist.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_ground.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_korfin.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_leistungsverzeichnis.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_modeling.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_objectlibrary.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_pointcloud.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_power.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes_alignment.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes_cables.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_terrain.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_tools.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_translation.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_utilities.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_vegetation.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules_leistungskatalog.djinee'...
         Djinee Export Output Files '..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.bridge.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.card.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.cinema.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.collaboration.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.cycle.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.dgmtex.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.geopkg.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.ifc.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.knp.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.landxml.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.magis.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.plan.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.points.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.port_base.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.reporter.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.shape.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.sonic.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.vissim.h;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_design.h;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_energy_definitions.h;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_inventory.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.enums.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.env.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.images.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.io.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.loca.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.log.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.primitive_math.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.primitive_types.h;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.tangle_store.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT._framework.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT._framework_core.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.bagel.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.bim.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.comp_properties.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.database.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.geodesy.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.korfin_resources.h;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.korfin_sdk.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.apluss_obj.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.engine_fusion.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.engine_kfe.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.geometry.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.media.h;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.pet.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_areas.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_buildings.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_datenaustausch.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_georef_images.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_gist.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_ground.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_korfin.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_leistungsverzeichnis.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_modeling.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_objectlibrary.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_pointcloud.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_power.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes_alignment.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes_cables.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_terrain.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_tools.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_translation.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_utilities.h;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_vegetation.h;..\..\..\..\..\_next\fusion2\code\djinee\export\NAT.modules_leistungskatalog.h;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.bridge.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.card.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.cinema.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.collaboration.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.cycle.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.dgmtex.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.geopkg.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.ifc.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.knp.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.landxml.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.magis.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.plan.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.points.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.port_base.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.reporter.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.shape.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.sonic.cc;..\..\..\..\..\_next\fusion2\code\djinee\_other\export\NAT.vissim.cc;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_design.cc;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_energy_definitions.cc;..\..\..\..\..\_next\fusion2\code\djinee\apps\export\NAT.app_inventory.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.enums.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.env.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.images.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.io.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.loca.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.log.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.primitive_math.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.primitive_types.cc;..\..\..\..\..\_next\fusion2\code\djinee\base\export\NAT.tangle_store.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT._framework.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT._framework_core.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.bagel.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.bim.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.comp_properties.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.database.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.geodesy.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.korfin_resources.cc;..\..\..\..\..\_next\fusion2\code\djinee\framework\export\NAT.korfin_sdk.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.apluss_obj.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.engine_fusion.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.engine_kfe.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.geometry.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.media.cc;..\..\..\..\..\_next\fusion2\code\djinee\geometry\export\NAT.pet.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_areas.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_buildings.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_datenaustausch.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_georef_images.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_gist.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_ground.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_korfin.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_leistungsverzeichnis.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_modeling.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_objectlibrary.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_pointcloud.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_power.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes_alignment.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_routes_cables.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_terrain.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_tools.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_translation.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_utilities.cc;..\..\..\..\..\_next\fusion2\code\djinee\modules\export\NAT.modules_vegetation.cc;..\..\..\..\..\_next\fusion2\code\djinee\export\NAT.modules_leistungskatalog.cc'...
         ..\..\..\..\..\regenerate\ruby\bin\ruby.exe ..\..\..\..\..\regenerate\tools\djinee.rb --export --projectDir=C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\/ --files ..\..\..\..\..\_next\fusion2\code\djinee\_other\bridge.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\card.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\cinema.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\collaboration.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\cycle.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\dgmtex.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\geopkg.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\ifc.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\knp.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\landxml.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\magis.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\plan.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\points.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\port_base.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\reporter.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\shape.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\sonic.djinee;..\..\..\..\..\_next\fusion2\code\djinee\_other\vissim.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_design.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_energy_definitions.djinee;..\..\..\..\..\_next\fusion2\code\djinee\apps\app_inventory.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\enums.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\env.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\images.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\io.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\loca.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\log.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\primitive_math.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\primitive_types.djinee;..\..\..\..\..\_next\fusion2\code\djinee\base\tangle_store.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\_framework.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\_framework_core.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\bagel.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\bim.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\comp_properties.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\database.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\geodesy.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\korfin_resources.djinee;..\..\..\..\..\_next\fusion2\code\djinee\framework\korfin_sdk.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\apluss_obj.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\engine_fusion.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\engine_kfe.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\geometry.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\media.djinee;..\..\..\..\..\_next\fusion2\code\djinee\geometry\pet.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_areas.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_buildings.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_datenaustausch.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_georef_images.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_gist.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_ground.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_korfin.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_leistungsverzeichnis.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_modeling.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_objectlibrary.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_pointcloud.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_power.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes_alignment.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_routes_cables.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_terrain.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_tools.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_translation.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_utilities.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules\modules_vegetation.djinee;..\..\..\..\..\_next\fusion2\code\djinee\modules_leistungskatalog.djinee --defines DJINEE_AREAS;DJINEE_BAGEL;DJINEE_BIM;DJINEE_BUILDINGS;DJINEE_COMMENTS;DJINEE_CORE;DJINEE_CYCLE;DJINEE_DA;DJINEE_DATABASE;DJINEE_DATADUMP;DJINEE_DGMTEX;DJINEE_ENGINE_CORE;DJINEE_ENGINE_FUSION;DJINEE_ENGINE_KFE;DJINEE_ENV;DJINEE_EVENTER;DJINEE_FRAMEWORK;DJINEE_FREE;DJINEE_GEODESY;DJINEE_GEOMETRY;DJINEE_GEOPKG;DJINEE_GROUND;DJINEE_IFC;DJINEE_IMAGES;DJINEE_IO;DJINEE_KF_CSV;DJINEE_KF_RESOURCES;DJINEE_KIB;DJINEE_LANDXML;DJINEE_LK;DJINEE_LOCA;DJINEE_LOG;DJINEE_LV;DJINEE_MAGIS;DJINEE_MATH;DJINEE_MEDIA;DJINEE_NET;DJINEE_PET;DJINEE_PLAN;DJINEE_POINTCLOUD;DJINEE_POINTCLOUD_KFE;DJINEE_PORTBASE;DJINEE_POWER;DJINEE_ROUTE;DJINEE_SDK;DJINEE_SHAPE;DJINEE_SONIC;DJINEE_TERRAIN;DJINEE_TYPES;DJINEE_VISSIM;DJINEE_XE_CORE;DJINEE_CINEMA;DJINEE_GEOREFIMAGES;DJINEE_GIST;DJINEE_KFMNEXT;DJINEE_MODELING;DJINEE_OBJECTLIB;DJINEE_POINTS;DJINEE_PROFILES;DJINEE_TRANSLATION;DJINEE_UTILITIES;DJINEE_VEGETATION
         -------------------------------------------------------------------------
         Say hello to the Djinee compiler.
         No changes in .djinee-files detected, skip execution...

         -------------------------------------------------------------------------
       PreBuildEvent:
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\regenerate\tools\copy.exe -sourceFile "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\pdfium\bin\pdfium.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\openssl\bin\libssl-3-x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\openssl\bin\libcrypto-3-x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\ecwdll\bin\ecwdll.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\opencascade\bin\opencascade.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\libE57Format\bin\e57dll.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_libs\liblaszip\bin\liblaszip.x64.dll" -targetFile "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\pdfium.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\libssl-3-x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\libcrypto-3-x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\ecwdll.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\opencascade.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\e57dll.x64.dll" "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\liblaszip.x64.dll"
         :VCEnd
       ClCompile:
         Alle Ausgaben sind aktuell.
         Alle Ausgaben sind aktuell.
         Alle Ausgaben sind aktuell.
       Link:
         C:\Program Files\Microsoft Visual Studio\2022\Enterprise\VC\Tools\MSVC\14.44.35207\bin\HostX64\x64\link.exe /ERRORREPORT:QUEUE /OUT:"..\..\..\bin\AplusS.djinee.full.x64.dll" /INCREMENTAL:NO /NOLOGO /LIBPATH:..\..\..\..\..\_libs\libminizip\lib\release64 /LIBPATH:..\..\..\..\..\_libs\zlib\lib\release64 /LIBPATH:..\..\..\..\..\_libs\sentinel\lib\x64 /LIBPATH:..\..\..\..\..\_libs\crunch\lib\release64 /LIBPATH:..\..\..\..\..\_libs\freeimage\lib\release64 /LIBPATH:..\..\..\..\..\_libs\clipper\lib\release64 /LIBPATH:..\..\..\..\..\_libs\pdfium\lib\release64 /LIBPATH:..\..\..\..\..\_libs\tcl\lib\release64 /LIBPATH:..\..\..\..\..\_libs\sqlitecpp\lib\release64 /LIBPATH:..\..\..\..\..\_libs\openssl\lib\release64 /LIBPATH:..\..\..\..\..\_libs\ecwdll\lib\release64 /LIBPATH:..\..\..\..\..\_libs\opencascade\lib\release64 /LIBPATH:..\..\..\..\..\_libs\shapelib\lib\release64 /LIBPATH:..\..\..\..\..\_libs\libE57Format\lib\release64 /LIBPATH:..\..\..\..\..\_libs\liblaszip\lib\release64 /LIBPATH:"..\..\..\..\..\_libs\yaml-cpp\lib\release64" MSCorEE.lib dxgi.lib d2d1.lib dwrite.lib d3d11.lib d3d9.lib GlU32.lib psapi.lib ws2_32.lib rpcrt4.lib libminizip.x64.lib zlib.x64.lib libhasp_windows_x64_110651.lib crnlib.x64.lib fi.freeimage.x64.lib fi.libjpeg.x64.lib fi.libopenjpeg.x64.lib fi.libpng.x64.lib fi.libtiff4.x64.lib clipperlib.x64.lib pdfium.x64.lib tcl.x64.lib sqlitecpp.x64.lib sqlite3.x64.lib "libssl-3.x64.lib" "libcrypto-3.x64.lib" ecwdll.x64.lib opencascade.x64.lib shapelib.x64.lib e57dll.x64.lib liblaszip.x64.lib "yaml-cpp.x64.lib" kernel32.lib user32.lib gdi32.lib winspool.lib comdlg32.lib advapi32.lib shell32.lib ole32.lib oleaut32.lib uuid.lib odbc32.lib odbccp32.lib /MANIFEST /MANIFESTUAC:"level='asInvoker' uiAccess='false'" /manifest:embed /DEBUG:FULL /PDB:"..\..\..\bin\AplusS.djinee.full.x64.pdb" /OPT:REF /OPT:ICF /LTCG /LTCGOUT:"..\..\obj\djinee.full_x64_release_sentinel\\AplusS.djinee.full.x64.iobj" /TLBID:1 /DYNAMICBASE /NXCOMPAT /IMPLIB:"..\..\..\bin\AplusS.djinee.full.x64.lib" /MACHINE:X64 /DLL ..\..\obj\djinee.full_x64_release_sentinel\\project_info.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\bagel_runtime.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\djinee.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\djinee_assertions.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\djinee_public.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.events.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.bridge.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.card.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.cinema.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.collaboration.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.cycle.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.dgmtex.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.geopkg.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.ifc.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.knp.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.landxml.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.magis.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.plan.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.points.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.port_base.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.reporter.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.shape.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.sonic.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.vissim.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.app_design.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.app_energy_definitions.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.app_inventory.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.enums.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.env.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.images.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.io.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.loca.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.log.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.primitive_math.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.primitive_types.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.tangle_store.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT._framework.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT._framework_core.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.bagel.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.bim.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.comp_properties.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.database.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.geodesy.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.korfin_resources.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.korfin_sdk.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.apluss_obj.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.engine_fusion.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.engine_kfe.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.geometry.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.media.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.pet.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_areas.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_buildings.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_datenaustausch.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_georef_images.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_gist.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_ground.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_korfin.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_leistungsverzeichnis.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_modeling.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_objectlibrary.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_pointcloud.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_power.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_routes.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_routes_alignment.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_routes_cables.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_terrain.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_tools.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_translation.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_utilities.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_vegetation.obj
         ..\..\obj\djinee.full_x64_release_sentinel\\NAT.modules_leistungskatalog.obj
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.nine.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.drain.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.dust.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.grand.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.ogis.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.park.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.quell.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.ramp.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\AplusS.stone.x64.lib
         C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\bin\sentinel.x64.lib
     1>LINK : fatal error C1047: Das Objekt oder die Bibliotheksdatei "..\..\..\..\..\_libs\libminizip\lib\release64\libminizip.x64.lib" wurde von einer anderen Version des Compilers erstellt als andere Objekte wie "..\..\obj\djinee.full_x64_release_sentinel\\project_info.obj". Kompilieren Sie alle Objekte und Bibliotheken mit dem gleichen Compiler neu. [C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj]
     1>LINK : fatal error LNK1257: Fehler bei Codegenerierung. [C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj]
     1>Die Erstellung des Projekts "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" ist abgeschlossen, Build Ziel(e) -- FEHLER.

Fehler beim Buildvorgang.

       "C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj" (Build Ziel) (1) ->
       (Link Ziel) ->
         LINK : fatal error C1047: Das Objekt oder die Bibliotheksdatei "..\..\..\..\..\_libs\libminizip\lib\release64\libminizip.x64.lib" wurde von einer anderen Version des Compilers erstellt als andere Objekte wie "..\..\obj\djinee.full_x64_release_sentinel\\project_info.obj". Kompilieren Sie alle Objekte und Bibliotheken mit dem gleichen Compiler neu. [C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj]
         LINK : fatal error LNK1257: Fehler bei Codegenerierung. [C:\Users\ThomasBeutlich\source\repos\Korfin_3\_korfin\xe.raumspline\_build\_prj\djinee.full\djinee.full.vcxproj]

    0 Warnung(en)
    2 Fehler

Verstrichene Zeit 00:00:06.74


.............................................................................

ERROR!!!

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
ERROR ERROR ERROR
FAILED TO BUILD!! CHECK LOG!
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/vstudio/vstudio_project.rb:514:in `BuildProject'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_build.rb:186:in `block in buildProjects'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_build.rb:180:in `each'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_build.rb:180:in `buildProjects'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_build.rb:69:in `doBuild'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_build.rb:42:in `build'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/api_source.rb:132:in `build'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/global.rb:531:in `runCommand'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/main.rb:119:in `<main>'
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
```

Finished: 2026-01-02 11:04:50.518045

[ERR] Build KorFin ReleaseTest failed after 36.116s with error: `Command '['C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/ruby/bin/ruby.exe', 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/main.rb', 'build(Platform:X64,Style:ReleaseTest,prj:KorFin)', 'close']' returned non-zero exit status 4294967295.`
