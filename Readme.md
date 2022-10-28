A Bash Script combining my most used commands from ssh, scp and sshfs

## Requirements

You have to install these package both on your local and remote systems

> openssh

## How to use

```git clone https://github.com/gooosz/syncat.git```

```cd syncat```

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
