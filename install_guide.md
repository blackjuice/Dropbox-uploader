#Installing dropbox uploader

##first, install curl

reference link: http://askubuntu.com/questions/259681/the-program-curl-is-currently-not-installed


###Then, enter these command-lines:

`sudo sed -i -e 's/us.archive.ubuntu.com/archive.ubuntu.com/g' /etc/apt/sources.list`

`sudo apt-get update`

`sudo apt-get install curl`

##install dropbox uploader

reference link: http://xmodulo.com/access-dropbox-command-line-linux.html

###command line:

`wget https://raw.github.com/andreafabrizi/Dropbox-Uploader/master/dropbox_uploader.sh`

`chmod +x dropbox_uploader.sh`

`./dropbox_uploader.sh`

###You will be asked to enter the link:

https://www.dropbox.com/developers/apps

* Choose Dropbox API app

* Files and database

* App cannot be limited

* All file types accessed

* Name cannot include 'drop' or 'dropbox'


###When done, check if it works with:

`./dropbox_uploader.sh info`
