1. Go to the directory you want, and init it as a repo

    ![](init.PNG)

2. Add all files you want uploaded to staging area and then commit

    ![](commit.PNG)
3.  Generate the private and public keys used for auth

    ![](keygen.PNG)
4. Give your SSH key a title and paste your public key into the "Key" field. Click the "Add SSH key" button to add the key to your GitHub account.

    ![](github_key.PNG)
5. Add your SSH key to SSH agent. This will help with the authentication

    ![](SSH_agent.PNG)

6. Update the Git Remote URL and Use `git remote -v` to ensure that you're connected via SSH
 
    ![](remote.PNG)

7. Push to github!



