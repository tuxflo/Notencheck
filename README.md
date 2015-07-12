# Notencheck
Casperjs script to automatically check grades from the HTW Dresden and execute custom notification script.

# Idea
While waiting for the results of my last exams I was pissed, that I have to check the HTW Grades page manually so I was looking for a solution to automate that and doing a custom notification (In my case a telegram message) if new grades are availible.

#Installation
Depending on your setup you have several options for the installation process:

###HTW Server
If you don't have acces to a Server (root, VServer or shared Host like Uberspace) you can build and run the script on the HTW server ilux150. For this the easiest way is to manually install node.js and npm as described [here](https://gist.github.com/isaacs/579814). After installing node and npm you hopefully easily can do
`npm install -g casperjs@1.1.0-beta3` to install casperjs.
Note that I was unable to compile/install telegram-cli for the HTW Server so you have to use a different notification tool to submit the new releases.

###Normal Server
If you have access to a server or you want to run the script on your local computer you can just follow the installation guides for installing casperjs. If you want to use telegram messanger for notifications you'll have to compile/install telegram-cli as described on the [project page](https://github.com/vysheng/tg)
