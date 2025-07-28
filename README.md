# miniconda
To create a new environment and install all








Install tips
```
https://repo.anaconda.com/miniconda/


wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
bash Miniconda3-latest-Linux-x86_64.sh

```




update .bashrc
```

##########
# miniconda
##########
# cd $HOME/Desktop/RUN_TIME
# wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
# bash Miniconda3-latest-Linux-x86_64.sh
# Miniconda3 will now be installed into this location:
# $HOME/miniconda3
#
#
alias miniconda_activate='source $HOME/miniconda3/bin/activate'
alias miniconda_deactivate='conda deactivate'
alias pyenv='miniconda_activate'
function check_new_packages() {
    comm -13 <(sort $HOME/Desktop/MY_GIT/First_Step_Debian/installed_packages.txt) <(pip list | sort)
}
alias mini_check='check_new_packages'


```


```
git clone 'https://github.com/Tpj-root/miniconda.git'
cd miniconda
miniconda_activate
pip install -r requirements.txt


```
