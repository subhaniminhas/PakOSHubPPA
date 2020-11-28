# PakOSHubPPA
PakOS PPA to install Debian .deb files using apt-get comands by adding PakOS Repository

Install my PPA this way:

curl -s --compressed "https://subhaniminhas.github.io/PakOSHubPPA/KEY.gpg" | sudo apt-key add -
sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://subhaniminhas.github.io/PakOSHubPPA/my_list_file.list"

sudo apt update

Then you can install PakOS packages:

sudo apt install pakoshub
