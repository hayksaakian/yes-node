yes/node
==================

A Node app that says "yes" or "no"

Install
==================

From a terminal session on a PC that has heroku's command line tools already installed, and git (which might be included there)

    git clone https://github.com/hayksaakian/nodejs-hello-world
    
    cd nodejs-hello-world
    
    heroku create

    git push heroku master


... and you're good to go!

Configure
==================

From a terminal inside the proper directory

    heroku config:set STATE=YES

Where YES is whatever text you'd like displayed.

You can wrap YES with quotes, like "YES" to use more complicated text

