#🔹 Step 1: Copy your SSH public key
In Git Bash, type:

bash
Copy
Edit
cat ~/.ssh/id_rsa.pub
(or if you saved it with another name, adjust accordingly.)

This will display your public key (a long string starting with ssh-rsa ...).

Carefully select and copy the entire key (without missing any characters).

🔹 Step 2: Log in to GitHub
Open https://github.com and sign in.

🔹 Step 3: Go to SSH keys settings
In the top right corner, click your profile picture ➔ Settings.

In the sidebar, click SSH and GPG keys.

Click the New SSH key button.

🔹 Step 4: Add your key
Title: Give it a name (example: My Laptop, Work PC, etc.)

Key: Paste your copied SSH public key here.

Then click Add SSH key.

🔹 Step 5: Done!
Now your GitHub account recognizes your computer via SSH.
You can now clone, pull, push using SSH links like:

bash
Copy
Edit
git@github.com:username/repository.git
instead of HTTPS.
