# NovaStream for Google TV

A TV player for the TV service you already pay for. Connect it to the playlist (M3U) or login your
provider gives you, and you get live TV with a guide, movies and series, voice search, and a Soccer tab
with today's matches and the channels in your lineup that carry them.

> **NovaStream is a player only.** It comes with no channels, films or series, and no links to any.
> Everything you watch comes from your own provider. Use it only with a service you're authorized to watch.

This is a test version for friends, installed outside the Play Store. Tell me what works and what doesn't.

## Install (about 5 minutes, once)

1. **Turn on developer mode:** on the TV, *Settings → System → About*, then click **Android TV OS build**
   seven times ("You are now a developer").
2. **Install Downloader:** search the Play Store for **Downloader** (by AFTVnews) and install it.
3. **Let Downloader install apps:** *Settings → Apps → Security & restrictions → Unknown sources* →
   turn on **Downloader**. (On some TVs: *Settings → System → Developer options → Install unknown apps*.)
4. **Get NovaStream:** open Downloader, type the code **9760489** in its box, choose **Go**, then **Install**.
   (Or type the whole address: `github.com/grivera82/novastream-tv/releases/latest/download/NovaStream.apk`.)
   The code always gets the newest version.
5. Open **NovaStream** from *Your apps*.

## Sign in

The first screen shows a **QR code**. Scan it with your phone (on the same Wi-Fi as the TV), then paste the
playlist link from your provider, or fill in the server, username and password they gave you. You can also
type them with the remote on the right side of the screen. To change it later: *Settings → Change playlist*.

Your login stays on your TV and is only sent to your provider.

## Updates

When there's a new version, NovaStream shows **Update** at the top; install it from *Settings*.
The first time, the TV asks to let NovaStream install apps: allow it, then choose *Install* again.

## Using it

- **Home**: what's on now, Continue watching, My list, Live now, new movies and series.
- **Live TV**: *On now*, *Your channels*, a **TV guide**, and every category. While watching, Up / Down
  change channel, Left goes back to the last one, Right lists the channels, OK opens the channel menu
  (captions, audio, sleep timer), numbers jump to a channel.
- **Movies / Series**: categories and posters; Left / Right skip 10 seconds while playing; the next
  episode starts by itself.
- **Soccer**: today's matches with live scores, and which of your channels show each one.
- **Hold OK** on any card for its options (My list, Your channels, remove from Continue watching).
- **Settings**: languages, adult categories (hidden unless you turn them on), the Soccer tab, 4K versions
  first or last, subtitles, and your account.

## Privacy

NovaStream sends me problem reports so I can fix bugs: crashes, freezes, and playback errors (with the name
of the channel or title that failed to play). Once a day it also sends the app version, the TV model and how
much it was used (counts only), and it shows me when it's online. Your login and your provider's address are
never included, and your TV is known only by a random ID.
