# A03
## Directions on Using Git/Github/Webstorm

### Setting Up
1. Create a **Github** account
- https://github.com/join
2. Download **Git**
- https://git-scm.com/downloads
3. Download Webstorm
- https://www.jetbrains.com/student/
4. Connect **Github** w/ Webstorm
- In Webstorm press (Ctrl+Alt+S) for system preferences.
- Select Version control **Git**. 
- Enter the path to the git.exe
5. Create a **Repository** on Github
- Click "+" sign in the upper right corner and select "New Repository"
6. Create a **Repository** on Webstorm
- Select VCS and Import int Version Control
Import **Repository** from **Github**
- From Main page, select Checkout from Version Control -> Git 
OR
- From within Webstorm, Select VCS -> Checkout from Version Control -> Git 
- Enter Github repository name
- Enter local path name

### Using Webstorm to **Push** a File to **Github**
1. Open Webstorm and create a Webstorm file
- Go to File -> HTML -> HTML 5 OR File -> Stylesheet
2. Add files to **Git**
- Add to Git dialog box opens
- Click Add. This adds to local file system
3. **Commit** your changes
- On top of Webstorm, select VCS -> Git -> Commit
- Text box with "msg added" will appear. Add/change any text and press blue "Commit" button
4. **Push** changes to **Remote** Repository
- Press "Ctrl" -> "Shift" -> "K" on keyboard OR "VCS" -> "Git" -> "Push"
- Select the committed file and click Push
- File will now appear on Github

## Glossary

- Branch - set of development code that does not interfere with production system

- Clone - creates a clone of an existing **repository** in an new directory at another location

- Commit - stores new part of project into **repository**

- Fetch - gets **branch** from **repository**, find which objects are missing from local database, and returns with missing objects added

- GIT - a free content tracker used for storing code being developed by multiple people at once and seeing what changes were made by said developers

- Github - open source version control system

- Merge - brings content from one branch into the main branch 

- Merge Conflict - event that occurs when **Git** is unable to automatically resolve differences in code between two commits

- Push - gets a branch of a **repository** and its committed refs and updates the associated remote repository

- Pull - fetches a **branch** and merges it

- Remote - **repository** used to track project that exists elsewhere. Can be communicated via fetch, push, or pull

- Repository - collection of refs

## References

Prof. Arthur Hendela Lectures (Week 2, Week 3)  
https://git-scm.com/docs/gitglossary  
https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone#:~:text=git%20clone%20is%20a%20Git,copy%20of%20the%20target%20repository.&text=Cloning%20a%20local%20or%20remote%20repository  
https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/
https://blog.axosoft.com/learn-git-merge-conflict/#:~:text=A%20merge%20conflict%20is%20an,merge%20commits%20without%20your%20help.
