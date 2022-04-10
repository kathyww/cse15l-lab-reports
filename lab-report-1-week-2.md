# Lab Report 1

In Lab1 you will set up VS code and learn some basic remotely connection skills.

1. Set up VS Code

    Follow the instructoin and download VS Code from [VS Code website](https://code.visualstudio.com).
    After installed you should see the page below when you open it. 
    ![Image](https://user-images.githubusercontent.com/103288344/162638790-5a2ead72-a8cb-4123-b2e4-88c6225c66c0.png)

2. Remotely Connecting

    In VS Code, open terminal and run the command:
    `$ ssh cs15lsp22zz@ieng6.ucsd.edu`
    
    Type yes if you get a message like this:
    `⤇ ssh cs15lsp22zz@ieng6.ucsd.edu
    The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
    RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
    Are you sure you want to continue connecting (yes/no/[fingerprint])?`
    
    Press enter, and then give your password. Now you successfully connect to another computer in the terminal.
    ![Image](https://user-images.githubusercontent.com/103288344/162639728-c7775f02-642a-419a-b833-338ec1846fc4.png)
    
3. Trying Some Commands

    Try commands in terminal. For example: 
    ls - show list
    cd - change directory 
    pwd - print working directories
   
    ![Image](https://user-images.githubusercontent.com/103288344/162639944-a86d280c-a2f5-4f37-a789-c5ebf0cfbbad.png)

4. Moving Files with `scp`
    Use the command `scp` to copy a file from your computer to a remote computer.
    Remember always run it from the client(your computer).
    
    ![Image](https://user-images.githubusercontent.com/103288344/162640661-d215fe33-9fd4-4cb1-835d-4c003e769629.png)

5. Setting an SSH Key
    Use SSH key to avoid typing the password repeatedly every time you log in. 
    First, run the command `ssh-keygen` which creates two files - public key and private key.
    
7. Optimizing Remote Running



## screenshot
![Image](https://user-images.githubusercontent.com/103288344/162541853-4c589485-be25-45fc-b4ae-15a1fedcac13.png)

