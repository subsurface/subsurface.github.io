{% if page.lang == "de" %}

<h1>Wo finde ich ausführbare Programme?</h1>
<p>Wie immer sind ausführbare Programme für Windows, Mac und Linux verfügbar. Für x86-64 Linux stellen wir sowohl ein AppImage bereit, das auf den meisten Distributionen laufen sollte, als auch Distributions-spezifische Pakete (Ubuntu, Fedora, und openSUSE).</p>
<p>Hier findet sich Subsurface {{page.version}}:</p>
<p><strong>Windows: </strong><a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac: </strong><a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a> (kompatibel mit der neusten MacOS version, f�r �ltere, siehe <a https://subsurface-divelog/downloads/>Downloads</a>)</p>
<p><strong>Linux:</strong> Ein generisches AppImage ist auf unserer <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release Seite</a>. Klicke auf <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, um es herunterzuladen und mache es mittels<br><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> ausführbar; nun kann diese Datei direkt aufgerufen werden.<br><strong>Linux: Ubuntu:</strong> Trage <code>ppa:subsurface/subsurface</code> in die Software Sources ein; die .deb Dateien in diesem PPA können auch auf hinreichend neuen <strong>LinuxMint</strong> Distributionen installiert werden; siehe die <a href="https://subsurface-divelog.org/download/">Programme herunterladen</a>-Seite und <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> für die aktuelle Version.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> Rufe unsere <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&amp;package=subsurface">Open Build Service Release Seite</a> auf.</p>
<p>Wir freuen uns über Nachrichten zu Fehlern in Subsurface in unserem <a href="https://subsurface-divelog.org/user-forum/">Benutzer-Forum</a>. Außerdem haben wir einen <a href="https://github.com/Subsurface/subsurface/issues">Bugtracker</a> auf dem solche Berichte eingestellt und bearbeitet werden können.</p>

{% elsif page.lang == "es" %}
<h1>¿ Donde puedo encontrar los binarios ?</h1>
<p>Hay binarios disponibles para Windows, Mac y una AppImage para Linux x86-64 (además de binarios específicos para varias distribuciones de Linux en las que se incluyen Ubuntu,  Fedora y OpenSUSE).</p>
<p>Se puede descargar Subsurface {{page.version}} desde estas ubicaciones:</p>
<p><strong>Windows:</strong> <a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong> <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> Hay una AppImage genérica disponible para descarga en la <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">página de descarga de Subsurface en Github</a>. Descarga <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, hazlo ejecutable</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> y, luego, simplemente ejecuta el archivo.</p>
<p><strong>Linux: Ubuntu: </strong>Añade <code>ppa:subsurface/subsurface</code> a tus fuentes de software; los archivos .deb en esta PPA tambien pueden instalarse en versiones suficientemente actualizadas de <strong>LinuxMint</strong>; visita la <a href="https://subsurface-divelog.org/download/">Página de descargas</a> y utiliza <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> para obtener nuestra última versión.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> Visita nuestro <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&package=subsurface"> site del servicio de compilación</a></p>
<p>Por favor, publica preguntas o problemas en el <a href="https://subsurface-divelog.org/user-forum/">Foro de usuarios</a> o comunica un fallo en nuestro <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>
{% elsif page.lang == "pt" %}

<h1>Onde posso encontrar os ficheiros binários</h1>
<p>Estão disponíveis ficheiros binários para Windows, Mac, e uma AppImage para Linux x86-64 (além de binários específicos para várias distribuições Linux, incluindo Ubuntu, Fedora, e openSUSE).</p>
<p>Pode obter o Subsurface {{page.version}} a partir das seguintes localizações:</p>
<p><strong>Windows:</strong> <a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong> <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> A AppImage genérica está disponível para descarga em: <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release page</a>. Download <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, dê-lhe permissões de execução</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> e depois execute o ficheiro.</p>
<p><strong>Linux: Ubuntu: </strong>Adicione <code>ppa:subsurface/subsurface</code> aos seus repositórios de software; os ficheiros .deb nesse PPA podem ser instalados em versões correntes do <strong>LinuxMint</strong>; ver a página dos <a href="https://subsurface-divelog.org/download/">Downloads</a> e usas <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> para obter a nossa versão mais recente.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> vá a <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&package=subsurface">open build service release page</a></p>
<p>Por favor coloque questões ou problemas no nosso <a href="https://subsurface-divelog.org/user-forum/">Fórum de utilizadores</a> ou preencha um bug no nosso <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>

{% elsif page.lang == "nl" %}

<p>De software is beschikbaar voor Windows, Mac en een AppImage voor x86-64 Linux (en daarnaast distributie specifieke software voor een aantal Linux varianten waaronder Ubuntu, Fedora, en openSUSE).</p>
<p>Je kunt Subsurface {{page.version}} ophalen van de volgende locaties:</p>
<p><strong>Windows:</strong><a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong><a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a></p>
<p><strong>Linux:</strong> Een generieke AppImage is beschikbaar op de <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release pagina</a>. Download <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, en maak deze executable</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> en voer dan eenvoudig dit bestand uit.</p>
<p><strong>Linux: Ubuntu: </strong>Voeg <code>ppa:subsurface/subsurface</code> toe aan je software bronnen; de .deb files in deze PPA kunnen ook op redelijk recente versies van <strong>LinuxMint</strong>; zie de <a href="https://subsurface-divelog.org/nl/downloads/">Downloads</a> pagina en gebruik <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> om de laatste versie te downloaden.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> ga naar onze <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&amp;package=subsurface">open build service release page</a></p>
<p>Post vragen of problemen op het <a href="https://subsurface-divelog.org/nl/user-forum-nl/">User Forum</a> of rapporteer een fout in onze <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>

{% else %}

<h1>Where do I find binaries?</h1>
<p>Binaries are available for Windows, Mac, and an AppImage for x86-64 Linux (plus distribution specific binaries for a number of Linux flavors including Ubuntu, Fedora, and openSUSE).</p>
<p>You can get Subsurface {{page.version}} from these locations:</p>
<p><strong>Windows:</strong> <a href="https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe">https://subsurface-divelog.org/downloads/subsurface-{{page.version}}.exe</a></p>
<p><strong>Mac:</strong> <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg">https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}.dmg</a>(this is intended for the latest MacOS version. For other MacOS versions, see <a https://subsurface-divelog/downloads/>the downloads page</a>)</p>
<p><strong>Linux:</strong> A generic AppImage is available for download at the <a href="https://github.com/Subsurface/subsurface/releases/tag/v{{page.version}}">Subsurface GitHub Release page</a>. Download <a href="https://subsurface-divelog.org/downloads/Subsurface-{{page.version}}-x86_64.AppImage">Subsurface-{{page.version}}-x86_64.AppImage</a>, make it executable</p>
<p><code>chmod +x Subsurface-{{page.version}}-x86_64.AppImage</code> and then simply run this file.</p>
<p><strong>Linux: Ubuntu: </strong>Add <code>ppa:subsurface/subsurface</code> to your software sources; the .deb files in that PPA can also be installed on sufficiently current versions <strong>LinuxMint</strong>; see the <a href="https://subsurface-divelog.org/download/">Downloads</a> page and use <code>http://ppa.launchpad.net/subsurface/subsurface/ubuntu</code> to get our latest release version.</p>
<p><strong>Linux: openSUSE / Fedora:</strong> go to our <a href="http://software.opensuse.org/download.html?project=home:Subsurface-Divelog&package=subsurface">open build service release page</a></p>
<p>Please post questions of problems in the <a href="https://subsurface-divelog.org/user-forum/">User Forum</a> or file a bug in our <a href="https://github.com/Subsurface/subsurface/issues">Bug Tracker</a>.</p>
{% endif %}
