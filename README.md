# GITFTP
## What is gitftp ?
Well gitftp is a neat little tool that allows you to push your _unstaged changes_ directly to your FTP.

## But why FTP ? Didn't we all agree it's **old** and **unsafe** ?
While this is entirely true, some of us are still stuck in FTP hell. And besides, if you have SFTP access, wouldn't you be better off doing pulls from your server directly ?

## Why only send unstaged changes ?
Because that's a great way to force you to have the same code locally and on your server. And also, that's how my workflow is. So yeah, it's mainly cause I like it this way. ;-)

## Okay you've convinced me. How do I install this ?
As simple as a Blink 182 song :
```
git clone git@github.com:jevin/gitftp.git
cd gitftp
ln -s gitftp /usr/local/bin
```

**Lastly, be aware that all your FTP credentials will be stored in the /projects folder!**

