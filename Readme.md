A Bash Script combining my most used commands from ssh, scp and sshfs

## Requirements

You have to install these package both on your local and remote systems

> openssh

## How to use

```git clone https://github.com/gooosz/syncat.git```

```cd syncat```

Now go into the script by e.g. ```vim syncat``` (or your editor of choice)\
and put your host and remote IPs into the ```$LAPTOP``` and ```$PC``` vars (doesn't matter which one, as long the corresponding user name is set correctly)\
and their user names into ```$LAPTOP_USER``` and ```$PC_USER```\
and make the bash script executable by

```chmod +x syncat```

now create a symlink to the script in your /usr/bin

```ln -s syncat /usr/bin/syncat```

## Tips

It is recommended to enable passwordless ssh for both machines

## Development

As of right now, the 
> -sy

> -a

> -rm

flags aren't working.
Feel free to create Pull requests
