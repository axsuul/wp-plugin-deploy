# WP Plugin Deploy

This Ruby script allows you to keep your WordPress plugin in a Git repository and still be able to deploy to the Subversion repository that the [wordpress.org](http://wordpress.org) plugin database uses. 

## Instructions

Edit the variables within the [deploy](/deploy) script to customize it to your project. Place the source of the plugin within the [plugin](/plugin) directory.

## Process

To deploy, run the command

```
$ ./deploy
```

Make sure to `chmod +x` the script to make it executable. What it does is create `svn` directory, keep the Subversion repository in there, and push it remotely.