# learning Git  
#### Creating git repositorty
**To initailize a new repo in an empty dir:** *git init*  
**To clone a repo maintaining the repo name:** *git clone link_to_repo*  
**To clone a repo changing the repo name:** *git clone link_to_repo new_repo_name*  

#### Configuring git environment  
**To configure username:** *git config --global user.name your_user_name*  
**To configure email:** *git config --global user.email your_email*  
**To configure default editor** *git config --global core.editor your_editor*  

#### Managing repository
**To stage changes:** *git add item_to_stage*  
**To unstage changes:** *git reset HEAD item_to_unstage*  
**To discard changes:** *git checkout -- item_to_discard*
**To check status** *git status*  
**For more details on status** *git diff*  
**For status on staged files** *git diff --staged*  
**To commit changes:** *git commit -m "your_commit_message"*  
**To add a remote repo with a spec name** *git remote add spec_name remote_url*  
**To view remote info** *git remote [-v]*  
**To fetch from remote** *git fetch remote_name*  
**To push to remote** *git push \<remote> \<branch>*  **
**To view remote** *git remote show remote_name*  
**To rename remotes** *git rename old_remote_name new_remote_name*  
**to remove reomtes** *git remote remove remote_name*  
**to display all tags** *git tag*
**to be more specific** *git tag --list "pattern_here"*  
**to add or create tag** *git tag -a tag_name -m "tag message here"*  
**to tag at a later time** *git tag -a tag_name commit_sha1*  
**to show latest tag** *git show*  
**to show specific tag** *git show tag_name*  
**to push a tag** *git push remote_name tag_name*  
**to delete a tag** *git tag -d tag_name*  
**to delete a remote tag** *git push remote_name --delete tag_name*