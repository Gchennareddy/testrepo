# testrepo
Remote github repository creation using cli commands.
curl -u "Gchennareddy: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" https://api.github.com/user/repos -d '{"name":"testrepo","private":false}'
username: Gchennareddy:  
Token:  ghp_YEwyRNUliVxpuQIHj9FIeredeWyXqBOvL0gMQkO
Classic token creation in github.

 
After creation of remote repository(testrepo) in github and clone the repo
  git clone https://github.com/Gchennareddy/testrepo.git

Created file and add the file into staging area
   git add file
   git commit -m "first file added"
Check the current branch in local and remote
    git branch -M main (change branch name)
 
For push the details from local to remote repository enter username and password(token)
   git push origin main
 


