# Clone the repository to your local machine
1. Generate an SSH key on your local machine. 
    - This is necessary to clone a remote repository to your machine and make further changes to it.
    - Windows: [official guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows)

# Update from local to cloud
1. git status 
   - make sure no random files are added!
   - if there are, add them to .gitignore
2. git add .
3. git commit -m "meaningful message that describes what you did"
4. git push origin main

# Download packages
1. `pip install -r requirements.txt`