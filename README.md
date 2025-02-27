# lainos_repo
A Pacman repository for the inclusion of Calamares installer during LainOS ISO build and for packages not included in the Arch Core, Extra, Community, and AUR repositories.

To use this repo, append these lines to /etc/pacman.conf:

[lainos_repo]

SigLevel = Optional TrustAll

Server = https://github.com/The-LainOS-Project/lainos_repo/raw/main/X86_64/

fork removes : in 2 file names so you can reliably clone the repo on windows
