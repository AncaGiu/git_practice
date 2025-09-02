Curs GIT Naveen Automation lab
GIT PUSH
1. in command line:
-cd path_to_project/project_name
>git init
>ls -alt
2. pe GIT hub -> go to the repository created:
selectezi din grupa urmatoare: 
"…or push an existing repository from the command line"
copiaza comanda urmatoare:
>git remote add origin https://github.com/AncaGiu/DemoRepo.git
si paste in command line, la calea deja data mai sus
 3. in command line:
>git status
-all files are red= they are Pending
>git add .
>git status
-all files are green now
>git commit -m "first commit with playwright code"
>git push origin master   ->push to origin from master (origin - repository ul de pe git HUB; master numele branch ului local) 

ADAUGARE fisier nou
1.in Visual Studio- creez fisier nou cu cod & modific un fisier deja existent
2.in command line -> 
>git status  ->apare Noul fisier ca Untracked si cel Modified
>git add .     
>git status  ->apar cu verde fisierul nou(New) si fisierul modificat (Modified)
>git commit -m "git_test new file and modified file are commited "
>git push origin master

GIT PULL
(Repository = folderele mele de pe GIT Hub)
1.creez un folder local pe laptop si intru in el:
>mkdir NewFolder
>cd NewForlder
2.pe GIT HUb intru in repository ul pe care vreau sa il copiez local si copiez url ul aferent
3. clonez repository ul pe care vreau sa il copiez, la mine pe local. in linia de comanda in folder ul nou creat (NewFolder) dau comanda de clonare:
>git clone <url>
4.In VisualStudio Code-> click pe File ->"Add folder to Workspace" -> selectam folderul local cu noile date de pe Repository
5. in GitHub modificam continutul unui fisier din Reposity ul clonat ->salvam
5.in linia de comanda intram cu cd in folderul clona al repository ului si apoi dam comanda:
>git pull origin master   -> pull from origin to master(origin - repository ul de pe git HUB; master numele branch ului local) 

