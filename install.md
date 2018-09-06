### Git Install

1. Install Git Distribution 

```
sudo apt-get install git
```

2. After Git installation to make sure that is it working or not just give the command

```
git --version
```

### Repo Installtion

1. Make sure you have a bin/ directory in your home directory and that it is included in your path:

```
mkdir ~/bin
PATH=~/bin:$PATH
```

2. Download the Repo tool and ensure that it is executable:

```
sudo apt-get install curl
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
chmod a+x ~/bin/repo
```

Done... :+1:
