# REORGANIZED

This repo is taken apart and put in pieces.
Pieces will be published when ready, to start with aws-profile-organizer

Stay tuned for more ...

# cloud9-tools
Some handy tools for use in your AWS cloud9 linux hosted desktop

# setup
Clone this repo in a Cloud9 desktop and run the setup.sh script in the root of the repo. After setup completed, source your profile or open a new terminal window for the changes to take effect.

For the cross account commands, make sure to edit the ${C9TOOLS}/etc/config file with appropriate values for
MASTER_ACCOUNT and XACCOUNT_ACCESS_ROLE

# how

By default the tools will be installed under ~/.c9tools in a bin and a etc directory. The bin directory is added to your PATH by appending a line to your .profile. The \_functions file is sourced as well. Most commands actually are functions as they manipulate your environment variables. 

# more information

can be found by running myfunctions for a list of all commands in \_functions and manfunction <functioname> for a short description of each function.
