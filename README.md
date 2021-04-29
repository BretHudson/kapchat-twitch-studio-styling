# Twitch Studio Chat Styling for KapChat

<p align="center">
  <img width="482" src="/images/banner.png?raw=true">
</p>

<p align="center">
  Get the Twitch Studio chat overlay feel within OBS!
</p>

<p align="center">
  <img width="402" src="/images/preview.gif?raw=true">
</p>

## Setting it up

 1. Create a new source (Browser) in OBS
 2. For the URL, set it to https://www.nightdev.com/hosted/obschat/?theme=bttv_dark&channel=CHANNEL_NAME&fade=false&bot_activity=true&prevent_clipping=false
	 - Replace `CHANNEL_NAME` with the name of your Twitch channel
 3. Set the width/height to the dimensions you'd like. I used 400x500
 4. Open up this repository's [main.css](main.css) and copy/paste the contents into the Custom CSS option in the source
 5. Click OK and enjoy!

## Notes

If you want to resize the source, it is best to update the width & height within the source properties. Scaling it within the OBS interface will cause scaling artifacts. It'll look like 💩.

If you have multiple scenes, I recommend creating a scene with just the chat in it, and then adding that scene to others (you can do this via a source). Otherwise, each time you switch scenes, the chat will reset.
