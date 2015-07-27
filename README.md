<<<<<<< HEAD
## Windows 10 Highlights für Entwickler ##
Was muss man wissen, wenn man für Windows 10 entwickelt? Dieses Dokument ist eine Sammlung der wichtigsten Informationen und Knotenpunkt rund um die Windows 10 Entwicklung.

### Meine Apps laufen auf allen Geräten - wenn man es will ###
Mit Windows 10 gibt es ein vereinheitlichtes App-Modell für alle Windows 10 Devices. Das schließt neben
herkömmlichen Desktop PCs auch Tablets, Smartphones, Raspberry PI 2, Surface Hub, die HoloLens und zukünftig auch die XBox One ein. 
Für App Entwickler bedeutet das, dass man - wenn man möchte - seine App für all diese Plattformen anbieten kann. 
Natürlich stellt man sich als Entwickler sofort die Frage: Wie soll das funktionieren, wenn ich die unterschiedlichen Bildschirmgrößen zurechtkommen muss
oder komplett unterschiedliche Bedienparadigmen bei der Verwendung der unterschiedlichen Geräte erwarte. Darüberhinaus stellt sich natürlich die Frage, 
wie man mit Hardwarespezifika umgeht: Wie soll ich den Foto-Button am Lumia-Phone anprogrammieren können, wenn die gleiche App auch auf der XBox laufen soll und diese keinen Foto-Button besitzt?
Die gute Nachricht ist: Die Tools und das Framework nehmen uns hier die größten Sorgen ab. Dabei wird nicht der Ansatz des kleinsten gemeinsamen Nenners verfolgt, der bedeuten würde, dass die Apps soweit eingeschränkt sind, dass nur eine minimale Menge an Funktionen zur Verfügung steht - ganz im Gegenteil: Obwohl die App überall läuft, kann man trotzdem auch gerätegattungsspezifische Funktionen nutzen.
Was man diesbezüglich noch wissen muss, erfährt man hier:

* Blogpost zu Extension SDKs und Adaptive Code (deutsch): <http://blogs.msdn.com/b/dmx/archive/2015/07/24/windows-universal-apps-und-extension-sdks.aspx>
* Video zum Konzept des "Adaptive UI" (englisch): <https://channel9.msdn.com/Series/A-Developers-Guide-to-Windows-10/07> 
* Video zum Konzept des "Adaptive Code" (englisch): <https://channel9.msdn.com/Series/A-Developers-Guide-to-Windows-10/08>
* Artikel zu Windows 10 Development & Convergence (englisch) <https://msdn.microsoft.com/en-us/magazine/dn973012.aspx>
* Einstiegspunkt zum Thema auf der MSDN Library <https://msdn.microsoft.com/library/windows/apps/dn894631.aspx#ui_and_universal_input>



