# Set up and Instalasi-mongoDB
<ul>
  <li>sudo apt-get purge mongodb-org*</li>
  <li>sudo apt remove mongodb</li>
  <li>sudo apt purge mongodb</li>
  <li>sudo apt autoremove</li>
  <li>sudo rm -r /var/log/mongodb</li>
  <li>sudo rm -r /var/lib/mongodb</li>
  <li>sudo apt-get install gnupg</li>
  <li>wget -qO - https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -</li>
  <li>echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu focal/mongodb-org/4.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.4.list</li>
  <li>sudo apt-get update</li>
  <li>sudo apt-get upgrade</li>
  <li>sudo apt update</li>
  <li>sudo apt upgrade</li>
  <li>sudo apt-get install -y mongodb-org</li>
  <li>sudo apt-get install libc6</li>
  <li>sudo service mongod start</li>
  <li>sudo service mongod status</li>
</ul>
