+++
title = "Refrain: Melody for a better mood"

[extra]
description = "Introducing Refrain, new modern music player for GNOME."
image = "images/posts/refrain.png"
+++

Long before I switched to Linux, I used Winamp to play music. It was minimalist and did exactly what it was supposed to do. Play music and almost nothing else. So I've never had much desire to try something else. It was also sufficient for me because I didn't listen to music much anyway and when I did, I always just tapped the one song I wanted to play in the file manager.

But later I learned about the hit of the time, Spotify. It looked super cool, you can play anything you want without needing to download it. Spotify has also it's official Linux app, so I kept using it after I switched to Linux.

But later I decided, for various reasons, to get rid of this proprietary application, so I was looking for some open source alternatives. At that time I was already using GNOME and wanted a player that fit into GNOME.

My requirements were:

1. It must be open source.
2. It must look like a GNOME app and act like a GNOME app.
3. It must have a similar workflow to Spotify.

We have several options.

[**Rhythmbox**](https://flathub.org/apps/details/org.gnome.Rhythmbox3) is literally packed with features, but it looks terrible. It has a workflow quite similar to Spotify's, but I really don't want to look at its ugly UI every day.

![Rhythmbox window](/images/posts/introducing-refrain/rhythmbox-window.png)

[**GNOME Music**](https://flathub.org/apps/details/org.gnome.Music) looks (mostly) good, and as a GNOME app should. The workflow is similar to Spotify's, but it lacks one, for me the most important thing, the queue. What I really love on Spotify and I loved on Winamp too is the queue. Playlists and categorization by artists is a good thing, but I still need the queue. I rarely want to play one whole album, I rather want to add to the queue exactly the songs I just want to listen.

![GNOME Music window](/images/posts/introducing-refrain/gnome-music-window.png)

[**Lollypop**](https://flathub.org/apps/details/org.gnome.Lollypop) is more advanced than GNOME Music. And it has also a better designed UI, even when it still doesn't use Libadwaita. But it has the same problem as GNOME Music. It lacks the queue.

![Lollypop window](/images/posts/introducing-refrain/lollypop-window.jpg)

The big hit of the last year, [**Amberol**](https://flathub.org/apps/details/io.bassi.Amberol), is just perfect, but it's still not for me. It follows the Winamp-like workflow. Its slogan says everything, it just "Plays music, and nothing else". Its vision is not to be a library manager, but that's against my requirement number 3.

![Amberol window](/images/posts/introducing-refrain/amberol-window.png)

As you can see, it is very difficult to find the right player for me. (I guess I'm a little picky, too.) And that's why I decided to create my own. So I'm happy to introduce you Refrain!

<div style="display: flex; align-items: center; gap: 1rem;">
  <img alt="Refrain icon" src="/images/posts/introducing-refrain/refrain-icon.svg">
  <div style="display: flex; flex-direction: column;">
    <b style="font-size: 2rem;">Refrain</b>
    <span>Melody for a better mood</span>
  </div>
</div>

However, the application is still at a very early stage. But what will it offer in the future:

- Beautiful UI following the GNOME HIG and made right for GNOME.
- Music library management similar to GNOME Music or Lollypop.
- Queue oriented workflow.
- The most cool features of Amberol, such as coloring the UI by album cover.

If you are interested in the project, you can follow it's development on [GitLab](https://gitlab.gnome.org/pervoj/Refrain) or get informed about the latest news on my [Mastodon](https://mastodon.social/@pervoj) or [Twitter](https://twitter.com/pervojcz).
