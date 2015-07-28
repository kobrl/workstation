# workstation

## Installation

0. Ensure you have access via https to github.com.

0. Pull the `compozed-workstation` from github.com project to the home folder.

  ```
  cd $HOME
  git clone https://github.com/compozed/compozed-workstation.git  
  ls -1 compozed-worstation/
  ... 
    README.md
    bin
    sprout-wrap
    vim-config
  ...
  ```

0. run install script.

  ```
  ./compozed-workstation/bin/install_workstation
  ```


## Update existing workstation

0. Bring latest code to repo

  ```
  cd $HOME/compozed-worstation/
  git pull origin master
  ```

0. Re run install_workstation

  ```
  cd $HOME
  ./compozed-workstation/bin/install_workstation
  ```
