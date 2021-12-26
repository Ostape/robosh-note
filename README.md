This Application is created just for studying new technologies.
The main idea is to create a note application where users can save text, voice, image, and video notes. Also, the user is able to share these data via NFC, Bluetooth, WI-FI, and just via Android Intent.
There is an option to synchronize notes with ROBOSH back-end service and Google Firebase service.

For planning and creating tasks Trello board is used. Link to Trello: https://trello.com/b/LZgwUQIP/roboshnote

I use the default release branch strategy: 
 * main branch for keeping stable code
 * develop branch for merging developed code in feature branches

Branch naming convention:
 - feature/BBM-{ticket number}-ticket-name - branch where feature functionality is developed
 - chore/BBM-{ticket number}-ticket-name - branch where some non-feature functionality is developed (like change some data in README.md)
 - bugfix/BBM-{ticket number}-ticket-name - branch where some bugfix is developed