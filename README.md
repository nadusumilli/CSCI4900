# CSCI4900 Fossology

## Introduction.
This is a Fossology project assigned by Matt to our team. The members of our team are Brian and Nikhit. We will be creating software that uses Fossology Nomos and DoSOCS to pull information from projects such as licensing information and dependency information including JAR files.

## Copyright.
Brian and Nikhit

## License(s).
Because this code is free to use and share by everyone, our license will be Attribution 4.0 International

## Install Directions.
#### Obtain Source Files for Fossology and DoSOCS<br />
DoSOCS - https://github.com/DoSOCSv2/DoSOCSv2<br />
Fossology - http://www.fossology.org/projects/fossology/wiki/Git_Download

#### Install the correct dependencies/libraries for Python 2.7 and for DoSOCS<br />
Ensure Python is version 2.7, if it is 3.0 it will not work<br />
1. To check, run python --version

#### To add libraries for DoSOCS<br />
| File(s) | Commands |
| --- | --- |
|SQLAlchemy|pip install sqlalchemy|
|python-mysqldb|sudo apt-get build-dep python-mysqldb|
|libpq-dev|sudo apt-get install libpq-dev|
|posstgreSQL|pip install psycopg2|
|libglib2.0-dev|sudo apt-get install libglib2.0-dev|

#### Install Fossology and DoSOCS in your environment<br />
For DoSOCS<br />
1. Run the install-nomos.sh shell script in the /scripts directory of your DoSOCS installation.<br /><br />
For Fossology<br />
1. Add "deb http://www.fossology.org/releases/2.6.2/Ubuntu 'version' contrib" ('version' usually 14.04) to /etc/apt/sources.list<br />
2. Run installation commands sudo apt-get update, sudo apt-get install fossology<br />

#### Install Maven in your environment<br/>
For Maven<br />
1. Type sudo apt-get install maven.<br/>
2. To verify Type mvn -version.

## Environment.

The enviornment should be in a Virual Box and Unix using Python code for any programs and scripts 

## Usage.

Used to generate a list of dependecies given a pom.xml and one command. This will be a "one-shot" method of genertaing said list, and it uses programs such as SPDX and DoSOCS.
