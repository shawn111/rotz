# dropin.rs - An dropin manager help to handle dotfiles and others with documents

fork from [Rotz 👃](https://volllly.github.io/rotz/)

Thanks Rotz provide the basic ideas of Dotfile manager.
It provide the owner based file structure, not rely of the orignal files.
For example, we can create a school folder to handle all files related with school.
It might releated with shell, ssh, ...

The rotz design is very match to manage systemd drop-in files.
However, systemd is Linux only solution.


## Roadmap and different with Rotz

* copy mode instead of link
* hooks instead of install commmand
* handle system files
* remote repos
* support multi machines
* provide more linux functions rely on systemd or podman
* mdbook-autosummary base document

## Usage

Run `rotz --help` to see all commands Rotz has.

## Contribute

Feel free to create pull requests and issues for bugs, features or questions. 
