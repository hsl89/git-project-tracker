# Github Project Progress Tracker

Track the following progresses made by a group of users on an repo:
* Number of PRs created
* Number of PRs accepted 
* Number of PRs merged
* Number of commits
* Number of issues resolved

## Install requirements
```
pip install -r requirements.txt
```

## Github Access Token
The notebook uses Github Python APIs [PyGithub](https://pygithub.readthedocs.io/en/latest/introduction.html#download-and-install) to queries the contributions to the repo. To initiate the 
`Github` class in the notebook, you need to export Github access token to the shell.

```
export GITHUB_ACCESS_TOKEN=<your github access token>
```

