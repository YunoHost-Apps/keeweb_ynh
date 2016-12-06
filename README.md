# Keeweb for YunoHost #

Web client for reading and editing Keepass files locally. It can also sync with WebDAV (Owncloud, Nextcloud...), Dropbox, Google Drive, OneDrive...
![screenshot](https://habrastorage.org/files/ec9/108/3de/ec91083de3e64574a504bc438d038dec.png)

## Usage with OwnCloud/NextCloud ##
1. Open your file through webdav using https://linktoowncloud/remote.php/webdav/PATH-TO-YOUR-KDBX-FILE and your username and password (no need to enter username and password if you are using a private Keeweb, as it will automatically detect that you are logged in OwnCloud/NextCloud

## Usage for Dropbox sync ##
1. [create](https://www.dropbox.com/developers/apps/create) a Dropbox app
2. find your app key (in Dropbox App page, go to Settings/App key)
3. Enter the app key when prompted

## Add default files on your homepage ##
1. Read https://github.com/keeweb/keeweb/wiki/Configuration#json-app-config
2. In your config.json add the "files" entry with the appropriate settings

**More information on the documentation page:**    
https://keeweb.info/

**Live demo:**    
https://app.keeweb.info/
