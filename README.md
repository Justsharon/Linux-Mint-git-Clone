# How to clone a repository on Linux Mint 21.2 "Victoria"

### I am new to linux OS, therefore after changing from windows OS I faced challenges when I was trying to clone my github repositories. I therefore decided to write this oncei figured out how to clone the repository on my linux mint operating system.

Step 1:

Open the terminal by presing 
  `ctrl+alt+T`
    
Step 2:

Run the code below in your terminal
    `git clone  https://github.com/username/repository.git`

Step 3:

The terminal will prompt you to enter your github username . Key in your username and hit enter then , you will get     another prompt to enter your password. This is the point where you will have to key generate a private token on         github, because when you key in the github password the cloning process will fail as it nolonger accepts passwords      as atoken when using linux.

Step 4:

After keying in the private token when prompted, then hit `enter . THen wait for the clonning process of ypur           repository to complete.

### How to generate a private token on github 

  Step 1:
  Login to your github account.

  Step 2:
  Click on your profile on the top right corner then navigate to the `Settings` from the dropdown menu.

  Step 3:
  On the left sidebar, click on `Developer settings.`

  Step 4:
  Generate a new token, by  clicking on `Personal access tokens.`
  Click on the "Generate token" button

  Step 5:
  Configure token by  entering a name for your token then choose the desired sopes and grant relevant permissions for     the token. For private repos you atleast need the  `repo` scope.

  Step 6:
  Generate the token  by clicking on the `generate token` button

  Step 7:
  Once generated, the token will be displayed on the screen. Copy the token and save it in a secure place. This is        because github will not show the token again, so ensure that you copy it immeadiately.
  

