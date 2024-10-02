# PowerShell-quest-n-2   

>## Get-History > historique.txt
PS C:\> Move-Item -Path .\FolderTest1\File2 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest1\File4 -Destination EvenFolder 
PS C:\> Move-Item -Path .\FolderTest2\File6 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest2\File8 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest2\File10 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest1\File1 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest1\File3 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest1\File5 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest2\File7 -Destination EvenFolder
PS C:\> Move-Item -Path .\FolderTest2\File9 -Destination EvenFolder

>## Get-ChildItem -Path *Folder* -Recurse > listing.txt

  Directory: C:\EvenFolder

Mode                LastWriteTime          Length Name
----                -------------          ------ ----
-a----         10/2/2024  6:25 PM               0 File10   
-a----         10/2/2024  6:25 PM               0 File2   
-a----         10/2/2024  6:25 PM               0 File4 
-a----         10/2/2024  6:25 PM               0 File6   
-a----         10/2/2024  6:25 PM               0 File8

  Directory: C:\OddFolder

Mode                LastWriteTime          Length Name
----                -------------          ------ ----
-a----         10/2/2024  6:25 PM               0 File1
-a----         10/2/2024  6:25 PM               0 File3   
-a----         10/2/2024  6:25 PM               0 File5 
-a----         10/2/2024  6:25 PM               0 File7   
-a----         10/2/2024  6:25 PM               0 File9

