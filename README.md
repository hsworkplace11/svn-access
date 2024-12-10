# Welcome to Subversion Access repository

This was build in gitlab to manage svn permissions from pipeline


## How to add/remove users

1. Update svn-access-file with correct users and groupslocated at the root of this project
2. Run the new pipeline once done


## Repo Folder Structure

```
|--- gitlab-ci.yml
|--- ansible.cfg
|--- svn-access-file
|--- inventories
     ---hosts  --update this file with your hostname
|--- ansible-playbooks
