
git clone https://github.com/kenokabe/nomachine-4.2.25_1

nomachine-4.2.25_1

sudo apt-get update
sudo apt-get install gdebi
sudo gdebi ****.deb 

sudo /usr/NX/bin/nxserver --status

sudo /usr/NX/bin/nxserver --start

sudo /usr/NX/bin/nxserver --status —restart


sudo /usr/NX/scripts/setup/nxserver --keygen

NX> 704 Starting: server-keygen operation at: Thu Jun 19 11:59:24 2014.
NX> 704 Generating new ssh-keys. Please wait.
NX> 704 Keys generated correctly. Backing up files.
NX> 704 Back up of keys made. Updating files.
NX> 704 Keys updated. NX clients should now use key:
NX> 704 /usr/NX/share/keys/default.id_dsa.key
NX> 704 to get connected to this NX server.

$ nomachine-4.2.25_1


# ken at ken-trading in ~/nomachine-4.2.25_1 on git:master o [12:09:17]
$ sudo mv /usr/NX/share/keys/default.id_dsa.key ./default.id_dsa.key
 
# ken at ken-trading in ~/nomachine-4.2.25_1 on git:master x [12:09:56]
$ s
 
# ken at ken-trading in ~/nomachine-4.2.25_1 on git:master o [12:10:05]
$ git push origin master
 
# ken at ken-trading in ~/nomachine-4.2.25_1 on git:master o [12:10:28]
$