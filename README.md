# glib-config
Includes Hello World program and vscode config files for building and running glib and libsoup.

## Linux
### Install glib library
sudo apt-get install libglib2.0-dev (will install dependencies as well)

### Install libsoup library
sudo apt-get install libsoup2.4-dev (NOTE: VERSION 2.4. MAKE SURE YOU LOOK AT DOCS FOR CORRECT VERSION)

### Install json-glib library
sudo apt-get install libjson-glib-dev

### Install gdb c++ debugging
sudo apt-get install gdb

### Update/Install SSL/TLS Certificates
sudo apt-get update

sudo apt-get install wget ca-certificates

## Windows + WSL
### Build/Run
Clone repo into WSL file system. Run install commands above. Connect VS Code instance to WSL project directory. Ctrl+F5 to run without debugging or F5 to run debugger.
