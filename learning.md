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
**To commit changes:** *git commit -m "your_commit_message"*  