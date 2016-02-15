# CSCI4900 Fossology
## Introduction.
This is a Fossology project assigned by Matt to our team. The members of our team are Brian and Nikhit. We will be creating software that uses Fossology Nomos and DoSOCS to pull information from projects such as licensing information and dependency information including JAR files.
## Copyright.
Brian and Nikhit
## License(s).
Because this code is free to use and share by everyone, our license will be Attribution 4.0 International
## Install Directions.
Obtain Source Files for Fossology and DoSOCS
DoSOCS - https://github.com/DoSOCSv2/DoSOCSv2
Fossology - http://www.fossology.org/projects/fossology/wiki/Git_Download
Install the correct dependencies/libraries for Python 2.7 and for DoSOCS
Ensure Python is version 2.7, if it is 3.0 it will not work
1. To check, run python --version
To add libraries for DoSOCS
1. SQLAlchemy - pip install sqlalchemy 
2. sudo apt-get build-dep python-mysqldb
3. sudo apt-get install libpq-dev 
4. pip install psycopg2 (For posstgreSQL)
5. sudo apt-get install libglib2.0-dev
Install Fossology and DoSOCS in your environment
For DoSOCS
1. Run the install-nomos.sh shell script in the /scripts directory of your DoSOCS installation.
For Fossology
1. Add "deb http://www.fossology.org/releases/2.6.2/Ubuntu 'version' contrib" ('version' usually 14.04) to /etc/apt/sources.list
2. Run installation commands sudo apt-get update, sudo apt-get install fossology
## Environment.

## Usage.
