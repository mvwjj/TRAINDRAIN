## 1. Installing LFS
For Git to be able to handle large files like Unity scene, textures, or models Git Large File Storage has to be installed on the server and by the user.

Download link:
https://git-lfs.github.com/

Installation is straightforward: 1) Run the downloaded .exe installer and 2) when finished, run in your repository command ***git lfs install***. 

## 2. git ssh-authentication agent on Win
You can enable authentication agent for auto-password in Git-bash: [git-ssh-auth-win-setup.md](./git-ssh-auth-win-setup.md). It is very usefull for **lfs**.

If you use tools like SourceTree, TortoiseGit, or other GUI you can read additional information on this page https://docs.unity3d.com/Manual/SmartMerge.html.

