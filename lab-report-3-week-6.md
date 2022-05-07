# CSE 15L Lab Report 3: Misc Etc

## Speedy SSH
The configuration shown below allows a user to SSH into a server using a username rather than the full hostname.
![Image](ssh_config.png)

This makes it much faster to connect and copy files, like below.
![Image](ssh_config_login.png)
![Image](ssh_config_scp.png)

## Github in Server
Next is setting up SSH keys to allow editing a repository from the command line.
![Image](ssh_key_github.png)

Here is the private key on the server
![Image](ssh_key_remote.png)

And now, a successful push to the remote repository. [Link](https://github.com/bxhackel/Example/commit/7bd36f31f36980f8188e52b53fc096934a53aee0)
![Image](git_commit.png)

## Speed Copy
Finally, the following can be used to copy whole directories using `scp` rather than single files.
![Image](scp_multi.png)
This allows for quick testing and execution.
![Image](ssh_markdown_test.png)

We can combine the two into one command to run them all.
![Image](ssh_scp_one.png)