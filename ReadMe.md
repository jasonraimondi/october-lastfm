An OctoberCMS Plugin that adds a feed from last.fm to show your visitors what you have been listening to! Scrobble to last.fm from Spotify.

Available options:
-----------------------
- User Name: This is your last.fm User Name so we know which RSS Feed to Parse!
- Song Limit: How many songs do you want to list? The LastFM Feed shows up to 10, but you can limit it to a lower number.

It is a pretty simple plugin, so not much to talk about. It adds an ordered list of your recent tracks listened to from last.fm. You can scrobble to last.fm from Spotify.


Install With:
------------------------
php artisan plugin:install DigitalCanvas.LastFM


Quickstart guide:
------------------------
1. Go to the 'System' tab in October, and install the plugin using the DigitalCanvas.LastFM code or use command line tool artisan with the syntax 'php artisan plugin:install DigitalCanvas.LastFM'
2. After installation has finished a new component will appear in under Octobers 'CMS > Components' tab.
3. Open the your selected page/layout, and add the component to it.
4. Add this small code anywhere on the page/layout: {% component 'LastfmFeed' %} Be sure to use the correct alias, if you haven't changed it, then it should be 'LastfmFeed'.
5. That's it.