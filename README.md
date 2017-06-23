# prossh

Push your shell profile to SSH hosts.

### What is this?

A simple script that uploads a local shell profile file of your choice before dropping you in an SSH session. It keeps a backup of the old file on the remote host in case a remote file already exists and differs from the uploaded file.

### Install

    cd ~/bin
    wget https://raw.githubusercontent.com/jonatanblue/prossh/master/bin/prossh
    chmod +x prossh

Set the name of your profile in `PROFILE_FILE`, then SSH like this:

    prossh user@host
