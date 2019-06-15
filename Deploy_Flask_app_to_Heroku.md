All the command operate in Anacoda Prompt

**part 1(Anacoda)** 
1. Create a github repository
git add .
git commit -m""
git push

**part 2** 
1. heroku create file.name(eg:belly-button-project2019) (Heroku app name)
(Name must start with a letter, end with a letter or digit and can only contain lowercase letters, digits, and
 dashes.)

2. git remote -v

3.Create conda environment
$ conda create -n file.name(eg:belly_button_biodiversity_ens python-3.7)

4. activate this environment(check all conda environments`conda info --envs`) (activate belly_button_env
 gonna be the base once activated) 
*activate belly_button_env* or *activate belly_button_env* or *source activate belly_button_env*

5. `pip freeze` to check all the module in this environments we have installed

6. python app.py (run app.py to make sure all the modules we needed have been installed, install the modules and run`ptyhon app.py` again and again till we get result)

**part 3:** push all the data to heroku 
1. git add -A
2. git commit -m "setup basic server"
3. git push origin master(github master)
4. git push heroku master

**part 4:** output "pip freeze' to requirements.txt in base
1. pip freeze > requirements.txt
1. git add -A
2. git commit -m "added requirements.txt"

**part 5:**
heroku open(We can see a webpage)
heroku logs(check errors)


