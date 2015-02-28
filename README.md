# Dropbox-uploader

Installation guide to Dropbox uploader which allows us to access Dropbox account through a terminal.

* See **"install_guide.md"** to installation.

* Adding directory to $PATH: see **".bashrc"**

## Command-lines to access your Dropbox uploader

* To **list all** contents in the **top-level** directory:

`./dropbox_uploader.sh list`

* To **list all** contents in a **specific** folder:

`./dropbox_uploader.sh list Documents/manuals`

* To **upload** a local file to a remote Dropbox folder:

`./dropbox_uploader.sh upload snort.pdf Documents/manuals`

* To **download** a remote file from Dropbox to a local file:

`./dropbox_uploader.sh download Documents/manuals/mysql.pdf ./mysql.pdf`

* To **download an entire remote folder** from Dropbox to a local folder:

`./dropbox_uploader.sh download Documents/manuals ./manuals`

* To **create** a new remote folder on Dropbox:

`./dropbox_uploader.sh mkdir Documents/whitepapers`

* To **delete an entire remote folder** (including all its contents) on Dropbox:

`./dropbox_uploader.sh delete Documents/manuals`
