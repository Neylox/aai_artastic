# aai_artastic
Applied AI project for open artworks using wikimedia.

# Setting up Dev Env
* Install VS Code and Remote Containers Plugin. 
* Reload Folder in Container 
* Switch to .devcontainer and run "pip install -r requirements.txt" within the container (its a workarround don't know why installing after creation does not work)
* CD to frontend folder within /artastic/
* run "npm install"
* run "npm run serve"
* open second terminal
* cd to /artastic/
* run "python manage.py runserver"
* go to localhost:8000 - this is where the frontend will be :) 

You can also run this without VS Code and Remote Containers but you have to install python3 with requirements.txt and npm with package.json dependencys local.

Superuser: root:Summer!2020