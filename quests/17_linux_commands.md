"C:\Develops\multi_medias


PS C:\Develops\multi_medias> cd ../
PS C:\Develops> cd ../
PS C:\> cd /Commands
PS C:\Commands> pwd

Path
----
C:\Commands


PS C:\Commands> mkdir

cmdlet mkdir(명령 파이프라인 위치 1)
다음 매개 변수에 대한 값을 제공하십시오.
Path[0]: cd /mkdir Projects
Path[1]: pwd
Path[2]: mkdir Projects
Path[3]:


    디렉터리: C:\Commands\cd


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:48                mkdir Projects


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:48                pwd
d-----      2025-11-06   오후 5:48                mkdir Projects


PS C:\Commands>
PS C:\Commands> mkdir Projects


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:48                Projects


PS C:\Commands> cd 'C:\Program Files\'
PS C:\Program Files> cd ../..
PS C:\> cd /Commands
PS C:\Commands> ls


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:48                Projects


PS C:\Commands> cd /Commands/Projects
PS C:\Commands\Projects> pwd

Path
----
C:\Commands\Projects


PS C:\Commands\Projects>  ../
../ : '../' 용어가 cmdlet, 함수, 스크립트 파일 또는 실행할 수 있는 프로그램 이름으로
 인식되지 않습니다. 이름이 정확한지 확인하고 경로가 포함된 경우 경로가 올바른지 검증
한 다음 다시 시도하십시오.
위치 줄:1 문자:2
+  ../
+  ~~~
    + CategoryInfo          : ObjectNotFound: (../:String) [], CommandNotFoundExcep
   tion
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Commands\Projects> cd ../
PS C:\Commands> mkdir

cmdlet mkdir(명령 파이프라인 위치 1)
다음 매개 변수에 대한 값을 제공하십시오.
Path[0]: Data
Path[1]: Reports
Path[2]: Backup
Path[3]:


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:51                Data
d-----      2025-11-06   오후 5:51                Reports
d-----      2025-11-06   오후 5:51                Backup


PS C:\Commands> ;s
s : 's' 용어가 cmdlet, 함수, 스크립트 파일 또는 실행할 수 있는 프로그램 이름으로 인
식되지 않습니다. 이름이 정확한지 확인하고 경로가 포함된 경우 경로가 올바른지 검증한
다음 다시 시도하십시오.
위치 줄:1 문자:2
+ ;s
+  ~
    + CategoryInfo          : ObjectNotFound: (s:String) [], CommandNotFoundExcepti
   on
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Commands> ls


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:51                Backup
d-----      2025-11-06   오후 5:51                Data
d-----      2025-11-06   오후 5:48                Projects
d-----      2025-11-06   오후 5:51                Reports


PS C:\Commands> cd /Backuo
cd : 'C:\Backuo' 경로는 존재하지 않으므로 찾을 수 없습니다.
위치 줄:1 문자:1
+ cd /Backuo
+ ~~~~~~~~~~
    + CategoryInfo          : ObjectNotFound: (C:\Backuo:String) [Set-Location], It
   emNotFoundException
    + FullyQualifiedErrorId : PathNotFound,Microsoft.PowerShell.Commands.SetLocatio
   nCommand

PS C:\Commands> cd / Backup
Set-Location : 'Backup' 인수를 허용하는 위치 매개 변수를 찾을 수 없습니다.
위치 줄:1 문자:1
+ cd / Backup
+ ~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Set-Location], ParameterBinding
   Exception
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Comm
   ands.SetLocationCommand

PS C:\Commands> cd/ Backup
cd/ : 'cd/' 용어가 cmdlet, 함수, 스크립트 파일 또는 실행할 수 있는 프로그램 이름으로
 인식되지 않습니다. 이름이 정확한지 확인하고 경로가 포함된 경우 경로가 올바른지 검증
한 다음 다시 시도하십시오.
위치 줄:1 문자:1
+ cd/ Backup
+ ~~~
    + CategoryInfo          : ObjectNotFound: (cd/:String) [], CommandNotFoundExcep
   tion
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Commands>
PS C:\Commands> cwd
cwd : 'cwd' 용어가 cmdlet, 함수, 스크립트 파일 또는 실행할 수 있는 프로그램 이름으로
 인식되지 않습니다. 이름이 정확한지 확인하고 경로가 포함된 경우 경로가 올바른지 검증
한 다음 다시 시도하십시오.
위치 줄:1 문자:1
+ cwd
+ ~~~
    + CategoryInfo          : ObjectNotFound: (cwd:String) [], CommandNotFoundExcep
   tion
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Commands> pwd

Path
----
C:\Commands


PS C:\Commands> mkdir Test


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:53                Test


PS C:\Commands> mkdir Notes


    디렉터리: C:\Commands


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----      2025-11-06   오후 5:54                Notes


PS C:\Commands> cd C:\Commands\Notes
PS C:\Commands\Notes> pwd

Path
----
C:\Commands\Notes


PS C:\Commands\Notes>
"