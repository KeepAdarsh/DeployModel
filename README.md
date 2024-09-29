# DeployModel

# ModelDeploy

i have created a Rest Flask API .
Then deployed the model.

Instead of using Azure, i have deployed it on Render.
As Azure is a paid service according to my knowledge,
But in Render we can deploy 3 model for free.

to link the git repository and server, we need to add this to out virtual environment.

!-------Useful Git Commands-------!

git config --global user.email "adarshgourab.das2003@gmail.com"
git config --global user.name "KeepAdarsh"
git init
git add . 
git commit -m "first deplyoment"  
git remote add origin https://github.com/KeepAdarsh/DeployModel.git
git push -u origin master

!-------Some Additional Commands-------!

pip install flask
pip install gunicorn
pip freeze >> requirements.txt
