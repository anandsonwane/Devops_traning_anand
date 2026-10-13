Git Version Controlling 

Task 1 & 2
    1. Create the repositroy through UI 
    2. Clone the repo using command git clone https://github.com/anandsonwane/Devops_traning_anand.git
    3. Create the file using commands 
        1. echo #Devops$traning > Readme.md
        2. git add .
        3. git commit -m "FirstCommit"
        4. git push -u origin main

Task 3
    1. Go to setting of the repo
    2. In that ruleset and create the rule 
    3. and select the  Require a pull request before merging
    4. Test it 

Task 4 5 6 
    1. create one branch
    2. Add YAML file into it
    3. git switch main
       git pull origin main
    git switch -c feature/dummy-test
    echo Dummy workflow test>>Readme.md
    git add Readme.md
    git commit -m "Test dummy workflow"
    git push -u origin feature/dummy-test