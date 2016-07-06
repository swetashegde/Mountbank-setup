# Mountbank-setup

#### Installing Mountebank on Mac

- Install homebrew from [http://brew.sh/](http://brew.sh/)
- Install npm ```brew install npm```
- Install Mountebank ```npm install -g mountebank```
- Place the configuration file `mb-config.ejs` on your Mac
- Start Mountebank ```mb start --configfile=mb-config.ejs &```
- Stop Mountebank ```mb stop```