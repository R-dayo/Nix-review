# Nix OS review
## About Nix OS
NixOS is a Linux distribution based on a package manager named Nix. NixOS uses an immutable design and an atomic update model. Its use of a declarative programming configuration system allows reproducibility and portability. It is free and open-source software with an MIT License.

NixOS is configured using composable modules, and relies on packages defined in the Nixpkgs project. Package recipes and configurations are written in the purpose-built "Nix language" that ships with the Nix package manager. 

[read more at wikipedia](https://en.wikipedia.org/wiki/NixOS)

## So, what makes me want to use Nix OS?
Its package manager, Nix. I know, I can just install it on Fedora. But I already fell in love with how declarative Nix OS is. You know, I made a bash script for automated post installation before. But whenever I use it on Fedora fresh install, it doesn't do the work I wrote for. For example, I wrote a command to add both free and nonfree rpmfusion repositories. But after using the script, the rpmfusion repositories is not added. When I write the script I had a thoughts:

> What if a distro can be installed with dotfiles like how we copy hyprland configuration?
> 
> What is the distro with such capabilities?

Then I found one distro that I have dream about.
That is, Nix OS.

## Hibernation Test
- hibernate start at 06:40 bat is 84%
- hibernate end at 08:00 bat is 80%

## Thoughts on Nix OS
### Day 1 using Nix OS
Things are intimidating at first. But after doing some research and experimenting through gnome-boxes, Nix OS is not that hard. Its update are atomic, its declarative approach make things easy to maintain, easy rollback and immutable system which makes it even harder to break. Also I'm impressed by Nix package manager. Because this is the first time I've seen a package manager that is capable to install Krita with G'mic plugin. This is because Nix OS declarative, so every software dependencies are isolated, which make this distro very stable without problems like dependency interference. 

Meanwhile traditional distro with popular package manager like APT, DNF, and PACMAN cannot do that. Plus, this package manager has a huge number of package. Meaning I can install numerous software using the package manager. Unfree software are also available in Nix. At this point, what the hell is snap, appimage, and flatpak?
