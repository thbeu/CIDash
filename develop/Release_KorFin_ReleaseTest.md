# Release KorFin ReleaseTest

Started: 2026-01-02 11:24:21.610899

```
###############################################################################
# ReGenerate Library 6.0 - (C) 2015-2026 A+S Consult GmbH FuE
###############################################################################
PATH_TO_REGENERATE 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/'
Initial arguments: 'release(Platform:X64,Style:ReleaseTest,prj:KorFin,target:d:/TB/ci_work/_ci_release) close'
Executing initial Command 'release' with Arguments '{:Platform=>"X64", :Style=>"ReleaseTest", :prj=>"KorFin", :target=>"d:/TB/ci_work/_ci_release"}'...
###############################################################################
...............................................................................
Auto detected source path '_korfin/xe.raumspline/'.
Scanning 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/_korfin/xe.raumspline/'...
ERROR: MISSING 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/_korfin/xe.raumspline/bin/AplusS.djinee.full.x64.dll'. - C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:125:in `block in releaseFiles'!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
ERROR ERROR ERROR
ERROR: MISSING 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/_korfin/xe.raumspline/bin/AplusS.djinee.full.x64.dll'.
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/util/log.rb:69:in `LCritical'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:125:in `block in releaseFiles'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:118:in `each'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:118:in `releaseFiles'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:107:in `doRelease'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:57:in `executeRelease'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/regenerate_release.rb:16:in `release'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/api_source.rb:186:in `release'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/source/global.rb:546:in `runCommand'
C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/main.rb:119:in `<main>'
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
```

Finished: 2026-01-02 11:24:22.068036

[ERR] Release KorFin ReleaseTest failed after 0.467s with error: `Command '['C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/ruby/bin/ruby.exe', 'C:/Users/ThomasBeutlich/source/repos/Korfin_3/regenerate/main.rb', 'release(Platform:X64,Style:ReleaseTest,prj:KorFin,target:d:/TB/ci_work/_ci_release)', 'close']' returned non-zero exit status 4294967295.`
