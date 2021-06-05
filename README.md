# Red Hat Enterprise Linux 7 - Universal Base Image - stock

The file is above 25MB, so i have to upload the file to my google cloud. use 7z to extract the file which is nearly 46MB tar.gz 

https://drive.google.com/file/d/1yQlpdegS52fPLx9LuKqB5IgQQDAt0Kdh/view?usp=sharing

Just simple import to wsl using command wsl --import <name_for_this_distro> <local_directory> <this_package> --version 2

then run using the command wsl -d <name_for_this_ditro>

then try to execute systemctl status.
