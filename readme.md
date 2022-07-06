
git pull origin https://github.com/virendrakryadav/vk-wikimedia-docker

Create directory named "projects" here
Switch to project "directory"
git clone https://gerrit.wikimedia.org/r/mediawiki/core.git inside the "projects" directory
This creates "core" directory" 
copy files from core directory to the vk_wikimedia-docker directory and rename it to "mediawiki"

copy the LocalSettings.php file in app root folder i.e. mediawiki directory

Run sudo docker-compose -f mediawiki.yml -d up


Import database from mysql/bkup directory


Support reference links
