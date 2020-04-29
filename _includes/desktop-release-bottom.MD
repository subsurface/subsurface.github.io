{% if page.lang == "de" %}
<h1>Wo finde ich ausführbare Programme?</h1>
<p>Wie immer sind ausführbare Programme für Windows, Mac und Linux verfügbar. Für x86-64 Linux stellen wir sowohl ein AppImage bereit, das auf den meisten Distributionen laufen sollte, als auch Distributions-spezifische Pakete (Ubuntu, Debian, Linux Mint, Fedora, und openSUSE).</p>
<p>Hier findet sich Subsurface {{page.version}}:</p>
<p><strong>Windows:</strong><a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong><a href="https://subsurface-divelog.org/downloads/Subsurface-4.8.1.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> Ein generisches AppImage ist auf unserer <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release Seite</a>. Klicke auf <a href="https://github.com/Subsurface/subsurface/releases/download/v{{page.version}}/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, um es herunterzuladen und mache es mittels<br><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> ausführbar; nun kann diese Datei direkt aufgerufen werden.<br><strong>Linux: Ubuntu:</strong> Trage <code>ppa:subsurface/subsurface</code> in die Software Sources ein; die .deb Dateien in diesem PPA können auch auf hinreichend neuen <strong>Debian</strong> und <strong>LinuxMint</strong> Distributionen installiert werden; siehe die <a href="https://subsurface-divelog.org/download/">Programme herunterladen</a> Seite und <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> für die aktuelle Version.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> finden sich auf unserer <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&amp;package=subsurface">Open Build Service Release Seite</a></p>
<p>Wir freuen uns über Nachrichten zu Fehlern in Subsurface in unserem <a href="https://subsurface-divelog.org/user-forum/">Benutzer Forum</a> ausserdem haben wir einen <a href="https://github.com/Subsurface/subsurface/issues">Bugtracker</a> auf dem solche Berichte eingestellt und bearbeitet werden können.</p>
{% elsif page.lang == "es" %}




{% elsif page.lang == "pt" %}





{% elsif page.lang == "nl" %}
<p>De software is beschikbaar voor Windows, Mac en een AppImage voor x86-64 Linux (en daarnaast distributie specifieke software voor een aantal Linux varianten waaronder Ubuntu, Debian, Linux Mint, Fedora, en openSUSE).</p>
<p>Je kunt Subsurface {{page.version}} ophalen van de volgende locaties:</p>
<p><strong>Windows:</strong><a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong><a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> Een generieke AppImage is beschikbaar op de <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release pagina</a>. Download <a href="https://github.com/Subsurface/subsurface/releases/download/v{{page.version}}/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, en maak deze executable</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> en voer dan eenvoudig dit bestand uit.</p>
<p><strong>Linux: Ubuntu: </strong>Voeg <code>ppa:subsurface/subsurface</code> toe aan je software bronnen; de .deb files in deze PPA kunnen ook op redelijk recente versies van <strong>Debian</strong> en <strong>LinuxMint</strong>; zie de <a href="https://subsurface-divelog.org/nl/downloads/">Downloads</a> pagina en gebruik <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> om de laatste versie te downloaden.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> ga naar onze <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&amp;package=subsurface">open build service release page</a></p>
<p>Post vragen of problemen op het <a href="https://subsurface-divelog.org/nl/user-forum-nl/">User Forum</a> of rapporteer een fout in onze <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>
{% else %}
<h1>Where do I find binaries?</h1>
<p>Binaries are available for Windows, Mac, and an AppImage for x86-64 Linux (plus distribution specific binaries for a number of Linux flavors including Ubuntu, Debian, Linux Mint, Fedora, and openSUSE).</p>
<p>You can get Subsurface {{page.version}} from these locations:</p>
<p><strong>Windows:</strong> <a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong> <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> A generic AppImage is available for download at the <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release page</a>. Download <a href="https://github.com/Subsurface/subsurface/releases/download/v{{page.version}}/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, make it executable</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> and then simply run this file.</p>
<p><strong>Linux: Ubuntu: </strong>Add <code>ppa:subsurface/subsurface</code> to your software sources; the .deb files in that PPA can also be installed on sufficiently current versions <strong>Debian</strong> and <strong>LinuxMint</strong>; see the <a href="https://subsurface-divelog.org/download/">Downloads</a> page and use <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> to get our latest release version.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> go to our <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&package=subsurface">open build service release page</a></p>
<p>Please post questions of problems in the <a href="https://subsurface-divelog.org/user-forum/">User Forum</a> or file a bug in our <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>
{% endif %}
