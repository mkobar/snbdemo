# snbdemo

##Social Networks for Buildings (SNB) Web App with BlueMix

[![License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](https://github.com/mkobar/snbdemo/blob/master/LICENSE)

Entry for The Koder 2016 Online Hackathon, Stamford CT 20 Feb 2016

### The Idea
The idea is to make micro-social networks for building-sized co-located communities, and include the building as both a persona and participant.  Any posts made in the building are automatically aggrated to the building's account and then automatically routed to the correct location or individual in the building (e.g. facilities management, building event coordinators, etc.) and some (most) are also available to all the network members (while in the building).

The building could "read" the posts and using BlueMix and Watson APIs, respond to post and questions - like a chatbot.

The service uses geolocation and a geo-fence to determine the user's location and the building they are in.

### How It Was Built
This mobile application was built with the sweet [Ionic Framework](http://ionicframework.com/) (Angular.js/JavaScript/CSS/HTML5) and uses the IBM BlueMix, Watson and Cloud-foundry services for authentication, responses and cloud data storage.

### Status
Unfortunately I could not get my app to workk with BlueMix and Cloud-foundry but checked in the code to demonstrate my progress.

##Resources

### BlueMix and Ionic

http://www.raymondcamden.com/2015/07/20/saucedb-building-the-back-end-with-ibm-bluemix/

http://www.raymondcamden.com/2015/10/27/nodeschool-for-ibm-bluemix-and-node-js/

http://heidloff.net/article/deploying-apis-built-via-nodejs-to-ibm-bluemix

https://strongloop.com/strongblog/part-1-ionic-loopback-node-js-mobile/

https://dzone.com/articles/ionic-hybrid-mobile-app-using-mobilefirst-platform

## License

Released under the [MIT License] (http://opensource.org/licenses/MIT)
Copyright @ 2016 [RKOSecurity] (http://www.rkosecurity.com)
