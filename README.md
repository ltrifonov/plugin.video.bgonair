# Based on: Simple example plugin for Kodi mediacenter

## Disclaimer
I'm not a python guy, in fact this plugin is result of my very first 3 hours in python. It does the work for me.
Please, fork the code and improve, if you can do it better, just don't criticize.
IT works really slow here (the opposite end of the globe), but it does the job for me, so I don't intend to improve it further.

## How to generate deployable plugin:
If you are in the module folder, assuming the folder is named `plugin.video.bgonair`, run the following (Linux / Mac)

```
cd ..
zip -r plugin.video.bgonair.zip plugin.video.bgonair -x *.git*

```
For windows, just zip the folder and provide to kodi.

License: [GPL v.3](http://www.gnu.org/copyleft/gpl.html)
