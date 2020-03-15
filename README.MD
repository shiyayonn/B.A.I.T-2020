Repository for B.A.I.T 2020

Starting with Git

1. Create a folder on your desktop.
2. Create an empty text file or any file inside the folder that you created or you can create via gitbash by entering this command, "touch hello.txt".
3. Open your gitbash. 
4. Enter command, "git init" to initialize the Git Repository.
5. Enter command, "git add ." this command adds all the files to the staging area or "git add hello.txt" if you want to add specific file. Also, this command is also allowed "git add hello.txt hello2.txt" for multiple adding of files.
6. To add this to your desired repository, type " git remote add origin "https://github.com/brykurt/B.A.I.T-2020.git".
7. Enter, "git status" if you want to check the files that you have added to the staging area.
8. Enter, "git commit -m 'Your message'".
9. Enter, "git push origin master" to upload the files to this repository.
10. Check your Repository if the files have been pushed.


Generating SSH keys

1. Open gitbash then type, "ssh-keygen".
2. Name your key and check the two files. The two files will have the same name, but, the other one will have an extension ".pub".
3. Once you located the .pub file, edit it with your text editor then copy the code.
4. Go to your Github Account, click settings, then on the left side of the screen, click "SSH and GPG keys".
5. Click the "New SSH key" button.
6. Name your key and paste the code that you copied from the .pub file. And then, click "Add SSH key" button.




