+++
title = "Refrén: Melodie pro lepší náladu"

[extra]
description = "Refrén, nový moderní hudební přehrávač pro GNOME."
image = "images/posts/refrain.png"
+++

Dlouho před tím, než jsem přešel na Linux, jsem pro přehrávání hudby používal Winamp. Byl minimalistický a dělal přesně to, co dělat měl. Přehrával hudbu a skoro nic jiného nedělal. Nikdy jsem tedy neměl potřebu zkoušet něco nového. Byl pro mě dostatečný také proto, že jsem hudbu stejně moc neposlouchal, a když ano, jen jsem poklepal na tu jednu skladbu, kterou jsem si chtěl přehrát, ve správci souborů.

Později jsem se ale dozvěděl o hitu té doby, Spotify. Vypadalo vážně skvěle, můžete si přehrát cokoli chcete aniž byste to museli stahovat. Spotify má také oficiální linuxovou aplikaci takže jsem v jeho používání pokračoval i po přechodu na Linux.

Později jsem se ale z různých důvodů rozhodl se této proprietární aplikace zbavit a hledal jsem nějaké open source alternativy. V té době jsem již používal GNOME a chtěl jsem tedy přehrávač, který do GNOME zapadá.

Mé požadavky byly:

1. Musí být open source.
2. Musí vypadat jako aplikace pro GNOME a taky se tak chovat.
3. Musí mít koncept podobný Spotify.

Máme více možností.

[**Rhythmbox**](https://flathub.org/apps/details/org.gnome.Rhythmbox3) je doslova nabitý funkcemi, ale vypadá hrozně. Koncept má celkem podobný tomu u Spotify, ale na jeho ošklivé rozhraní se každý den dívat nechci.

![okno Rhythmboxu](/images/posts/introducing-refrain/rhythmbox-window.png)

[**Hudba GNOME**](https://flathub.org/apps/details/org.gnome.Music) vypadá (většinou) dobře a tak jak by aplikace pro GNOME měla. Koncept je podobný tomu u Spotify, ale chybí mu jedna, pro mě nejdůležitější, funkce, fronta. Co na Spotify miluji a miloval jsem i na Winampu byla právě fronta. Seznamy skladeb a třídění podle interpretů je sice dobrá věc, ale stále potřebuji frontu. Zřídkakdy si chci pustit celé album, radši si chci přidat do fronty přesně ty skladby, které chci zrovna poslouchat.

![okno Hudby GNOME](/images/posts/introducing-refrain/gnome-music-window.png)

[**Lollypop**](https://flathub.org/apps/details/org.gnome.Lollypop) je pokročilejší než Hudba GNOME. Má také lépe navržené rozhraní, i přes to, že stále nepoužívá Libadwaitu. Má ale stejný problém jako Hudba GNOME. Chybí mu fronta.

![okno Lollypopu](/images/posts/introducing-refrain/lollypop-window.jpg)

Hit posledního roku, [**Amberol**](https://flathub.org/apps/details/io.bassi.Amberol), je prostě dokonalý, ale stále to není pro mě to pravé. Koncept má podobný tomu u Winampu. Jeho slogan říká vše, jenom „Přehrává hudbu, a nic víc“. Jeho vize je nebýt správcem hudební knihovny, ale to je proti mému požadavku číslo 3.

![okno Amberolu](/images/posts/introducing-refrain/amberol-window.png)

Jak můžete vidět, je velmi složité pro mě vybrat ten správný přehrávač. (Myslím, že jsem také trochu vybíravý.) A proto jsem se také rozhodl napsat si svůj vlastní. Chtěl bych vám tedy představit Refrén!

<div style="display: flex; align-items: center; gap: 1rem;">
  <img alt="ikonka Refrénu" src="/images/posts/introducing-refrain/refrain-icon.svg">
  <div style="display: flex; flex-direction: column;">
    <b style="font-size: 2rem;">Refrén</b>
    <span>Melodie pro lepší náladu</span>
  </div>
</div>

Aplikace je však stále ve velmi rané fázi. V budoucnu ale nabídne:

- Krásné uživatelské rozhraní navržené podle pravidel GNOME a vytvořené přímo pro GNOME.
- Spravování hudební knihovny podobně jako v Hudbě GNOME nebo Lollypopu.
- Koncept postavený na frontě.
- Nejzajímavější funkce Amberolu, například obarvení uživatelského rozhraní podle obalu alba.

Pokud vás projekt zaujal, můžete sledovat jeho vývoj na [GitLabu](https://gitlab.gnome.org/pervoj/Refrain), nebo se informovat o novinkách na mém [Mastodonu](https://mastodon.social/@pervoj) nebo [Twitteru](https://twitter.com/pervojcz).
