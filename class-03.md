# Revisions and the Cloud

## Distributed Version Control
- addresses the major vulnerability of the CVS: the server as a single point of failure. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions
- allows clients to create mirrored repositories
- teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows

## What is Git
- Git is a DVCS that stores data in a file system made up of snapshot
- Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it
- mostly relies on local operations because most necessary information can be found in local resources
- allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN
- Tracking Changes
- Loss of Data
- States:
  - Committed --> data stored on local database
  - Modified - changed but not committed to db
  - Staged - Flagged a file’s changed version to be committed in the next snapshot

## Cloning
- create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL
- copies all versions for a project
- terminal command: git clone https://github.com/testc 


## Tracking and staging
- one file: `git add filename`
- all files: `git add *`

## Committing a File

- After staging one or multiple files, you should commit the changes and record what you did within the commit message:

- `$ git commit -m “made change x,y,z”`

  - This step has committed changes for the file or files (you can have one commit message for multiple files, if applicable) to the HEAD

## Committing All Changes

- `$ git commit -a`
  - This command commits a snapshot of all modifications to tracked files in the working directory

## Pushing Changes

 - push changes to a remote repository

- `$ git push origin master`
  - This command pushes changes from the local “master” branch to the remote repository named “origin”