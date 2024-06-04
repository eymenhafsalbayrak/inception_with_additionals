1  apt-get update
2  apt-get install curl -y
3  curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
4  apt-get install nodejs -y
15  cd opt/
17  mkdir node-app
18  cd node-app/
19  echo 'console.log("nodejsapp from ubuntu...");' > index.js
22  node index.js 



