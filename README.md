# apprentissage-git

## liste des commandes pour FORK 

    git clone https://github.com/FiguerasMaxime/apprentissage-git
    git checkout dev
    git checkout -b maxime

### effectuez vos changements et vos commits 

    git remote add upstream https://github.com/LePtiDev/apprentissage-git.git
    git checkout master
    git pull --ff-only upstream master
    git checkout maxime
    git push -f origin maxime