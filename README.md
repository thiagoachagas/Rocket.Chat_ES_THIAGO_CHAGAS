# Rocket.Chat_ES_THIAGO_CHAGAS
Rocket Chat Challenge
I had to create a GCP account, create a new instance, configure this new instance, set a group of rules to start the installation.

Started a new instance
Started the installation using the guide https://docs.rocket.chat/quick-start/installing-and-updating/simple-deployment-methods/manual-installation/debian-based-distros/ubuntu


As the installation progressed I noticed that I've encountered a few issues, regardin the Node version.

So I noticed that I shouldn't use the version 12 (the one there's on the how-to) (sudo apt-get -y update && sudo apt-get install -y curl && curl -sL https://deb.nodesource.com/setup_12.x | sudo bash -). This one would cause me problems.

I tryed once to see what would happen and I had issues with Fibers.

So I had to install Node version 14 (as the how-to was saying right at the beggining "As from Rocket.Chat 4.4.0, NodeJS version 14.x.x is used".)

This way I was able to progress with the installation without problems.


This is the link to acceshttp://34.68.250.201:3000/channel/general
Login: rocketchatchallenge
Password: rocket@chat

![image](https://user-images.githubusercontent.com/99359659/153595430-cd28f076-a799-42fe-bd41-5b60f98530d1.png)



