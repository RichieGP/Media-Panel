This is a test panel view for a media player using components of picture elements, mini media player custom buttons, custom sliders, stack cards and most importantly, Music Assistant.

Many thanks to the development team for MA and mini media player, fabulous work!

This is proof of concept, it is not intended to be finsihed work and will not work without being adapted for your own environment.  Specific areas that will need changing are:
- scale, aspect ratio:  It is designed to be scaled to my use case, an iPad Pro as a wall panel with a dashboard that utlises the custom side bar.
- card and icon sizes: I have used px as this fits my use case.  For anyone wishing to scale this panel view, these will need to be altered to percentage/rem sizing +/- positioning
- media player entities will need to be changed
- you will need to make your own input booleans and custom template sensors.
- you will need to expose MA to the web and your path to the different views will be different from mine

If you wish to set up MA the way I have, you will either need to run a reverse proxy server (NPM) or wait for the next MA update that may allow view configurability

I am afraid I will not be able to support people getting it to work for their own systems as I do not have the time. I am posting the code due to a request to do so. 
Some of the code is quite complex but I hope it may help give some people some ideas on how to build their own.

Enjoy!
