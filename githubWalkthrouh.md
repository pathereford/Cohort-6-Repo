
<!-- to get new class information -->

In VsCode, file => open folder  /Desktop/Class-repo
in terminal type     git pull

Copy the new content to your working folder
    ie; CoHort-6-repo/assignments/week5

When you are ready to push your changes up 
    ensure that the file path in GIT  (the yellow part)
        is /dev/Cohort-6-repo   (  dev or persevere code )

        git add .
        git commit -m "your Message of what you are uploading"
        git commit origin main

Other useful commands

git remote -v     (tells what repo this folder is connected to)
git reset         (undoes your stagged changes)
git remote add origin "https://github.com/yourRepo/cohort-6     (re adds your repo to folder)


-------------- NEW NEW NEW NEW -------------

Folder Structure: 
Desktop  
   Dev
        ClassRepo    : This is where we pull files in
        WORKING      : This is where we work out of


 in ClassRepo/Cohort-6-repo   
 git remote -v should say https://github.com/mrmcgrain/CoHort-6-Repo (push)

 in WORKING 
 git remote -v should say your github address

 In VScode open folder Desktop / Dev
  right click classRepo  - Open in intergrated  terminal
            git pull origin main
    drag new files in to WORKING

when you have uploads ready for github
   right click your WORKING folder
      open in Intergrated Terminal
            git push origin main


            