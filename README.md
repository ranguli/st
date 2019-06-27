# st

An actively maintained upstream fork of Suckless.org's Simple Terminal (st) with my personal configurations and most of the patches from the [Suckless Wiki](https://st.suckless.org/patches/)

## Installation
```
git clone https://github.com/ranguli/st
cd ./st

make clean
make
sudo make install
``` 

## How an upstream fork works:
- Create your Git repo
- Add the remote repo as an upstream: ``` git remote add upstream https://git.suckless.org/st ``` This is now a source we can pull from for updates to the codebase, etc.
- Fetch updates for branches and commit history: ```git fetch upstream```
- Check out the local master branch: ```git checkout master```
- Merge the changes between your two repos: ```git merge upstream/master```

Further reading on the topic (paraphrased from this article): https://help.github.com/articles/syncing-a-fork/ 
