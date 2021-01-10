## In the Beginning There was Version Control 
>A version control system allows you to revisit previous versions of a file or set of files by recording changes.  Using version control systems, you can easily fix any mistakes made in a file without having to scrap through the whole file.

### LVC

>Local version control used one database on a hard disk that stored changes to files.  

### CVS

>Centralized version control is a server that stores all changes from various clients, making it easier to collaborate. 

>Distributed version control addresses the major vulnerability of the CVS.  The server for the CVS is a single point of failure.  If it goes down, people can’t work with each other on files and are confined to portions on local machines.  

### DVCS

>DVCS allows clients to create mirrored repositories, data backups that easily replace any lost information, this allows teams to work together in a variety of ways simultaneously.

### The Birth of Git

>Git is a DVCS, every time you save changes, it creates a snap shot of the file and stores it, if the file was never changed then it will only reference the already stored identical version.  Every change to a file is tracked by Git, and it always detects file corruption. Git makes it extremely difficult to lose data.

### There are three main states for files in Git
1.  Committed
Securely stored in database.
2. Modified
Changes made to file, but not committed to the database.
3. Staged
Flagged file change version that is ready to be committed.

### A-C-P!
Add, Commit, Push is the sequence that allows locally worked and updated files to be sent to the repository remotely allowing for seemless collaboration.
- Add one file (git add file.md)
- Add all files in directory (git add .)
- Commit changes (git commit -m"")
- "" is to write a note to clarify the changes or work done to said file or files in new update to GitHub
- Push files to GitHub (git push origin main)
 
 [Back to Main Page](https://github.com/plaurion1989/reading-notes/blob/main/README.md)