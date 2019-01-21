#
# Replace ssb-interop.js file with mine
#
sudo cat ssb-interop-append.js >> /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static/ssb-interop.js

#
# Place my style sheet in the correct location
#
sudo cp -p black.css /Applications/Slack.app/Contents/Resources/black.css
