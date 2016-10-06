# Digital Typography – Ein Glossar

Bitte für neue Einträge einen ‘Pull Request’ machen.

Provisorische Einträge:

* [x] User Experience
* [x] Webfont
* [x] Agile Software Development
* [x] Wasserfallmodell
* [x] Browser
* [x] Viewport
* [x] Self-Hosted
* [x] CDN
* [x] Framework
* [x] Flash of Unstyled Text (FOUT)
* [x] Frontend Design
* [x] Backend Design
* [x] API
* [x] Design Patterns
* [x] Style Guide
* [x] Reflow
* [ ] Style Tiles
* [ ] Responsive Web Design
* [ ] Fluid Web Design
* [ ] Adaptive Web Design
* [ ] Accessibility
* [ ] User Interface
* [ ] Mobile First
* [ ] User Centered Design
* [ ] Stakeholder
* [ ] Progressive Enhancement
* [ ] Interpolation
* [ ] Native
* [ ] Web
* [ ] Internet
* [ ] Performance
* [ ] Landing Page
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]
* [ ]

### Agile Software Development

Methoden (es gibt unterschiedliche Ansätze) zur Entwicklung von Software, die versuchen, durch flexiblere Arbeitsprozesse und Teamwork effizienter als der *Wasserfall* zu sein.
Siehe auch: [Scrum](https://de.wikipedia.org/wiki/Scrum), [Kanban](https://de.wikipedia.org/wiki/Kanban_(Softwareentwicklung)), [Extreme Programming](https://de.wikipedia.org/wiki/Extreme_Programming)

### Wasserfallmodell

Modell, das den idealen Prozess zur Software-Entwicklung zu illustrieren versucht. Ist immer noch aktuell, wird aber z.T. als ineffizient und kostenintensiv bezeichnet.

* [Wikipedia: Wasserfallmodell](https://de.wikipedia.org/wiki/Wasserfallmodell)

### Webfont

Eine Font-Datei, die von Browsern gelesen werden kann. Gängige Formate sind .eot, .otf, .woff und .woff2.

* [Bram Stein über fast alles, was man wissen sollte](https://www.youtube.com/watch?v=fFqTjWDVb0w)

### User Experience (UX)

Eine unscharfe Definition, die zwischen Buzzword und Fachterminologie rangiert, poupularisiert durch [Don Norman](https://en.wikipedia.org/wiki/Don_Norman). Im Zusammenhang mit Web Design ist der Begriff ein Gradmesser für Benutzerfreundlichkeit. Man könnte sagen, die User Experience umschreibe die Gefühle des Benutzers während der Interaktion mit einem User Interface. Die Popularität des Begriffs lässt sich darauf zurückführen, dass er einen gemeinsamen Nenner bildet, unter dem Marketing-Fachleute, Designer und Techniker ungefähr das Gleiche verstehen.

Findet der Begriff Verwendung, ohne *User Centered Design* zu berücksichtigen, so ist der *Bullshit Detector* anzuschalten.

* [Jesse James Garrett, The Nine Pillars](docs/9-pillars.pdf)
* [Jesse James Garrett, The Elements of User Experience](docs/elements_of_UX.pdf)

## Browser

Die Software, mir der wir zu Dokumenten im Web «navigieren». Z.B. Firefox, Safari, Chrome, Edge etc.

## Viewport

Der Bereich eines Dokuments, der im User Interface (z.B. im Browser-Fenster) sichtbar ist. Im Zusammenhang mit Smartphones unterscheidet Peter Paul Koch zwei unterschiedliche Viewports, nachzulesen [hier](http://quirksmode.org/mobile/viewports.html) und [hier](http://quirksmode.org/mobile/viewports2.html).

## Self-Hosted

Wenn man Dateien auf dem eigenen Server lagert. Der Begriff fällt häufig im Zusammenhang mit Webfonts: entweder man legt die Font-Dateien auf dem eigenen Server ab, oder man bezieht sie über ein *CDN*.

## CDN

‘Content Delivery Network’ – ein Server, der bestimmte Inhalte zentralisiert zur Verfügung stellt. Z.B. Webfonts oder JavaScript Bibliotheken wie JQuery. Die Verwendung eines CDN kann Abläufe erleichtern. So muss man sich nicht extra bemühen, Font-Dateien vor illegalem Download zu schützen oder die Notwendigkeit, eine JavaScript Bibliothek auf dem Server abzulegen und jedes mal zu ersetzen, wenn eine neue Version erscheint, entfällt.

## Framework

Je nach Kontext sind verschiedene Dinge gemeint. In der Regel spricht man entweder von JavaScript Bibliotheken (jQuery, Ember etc.) oder von Sammlungen aus HTML-Templates, Stylesheets und JavaScript-Komponenten, die das Bauen von Websites erleichtern sollen (Bootstrap, Foundation, HTML5-Boilerplate).
In beiden Fällen wird kritisiert, dass meist nur ein Bruchteil des Frameworks benutzt werde und dass die *Performance* stark unter sinnlosem Ballast (‘bloat’) leide.

## Flash of Unstyled Text (FOUT)

Auch «FOUC» (flash of unstyled content). Wenn der Browser die Webfonts noch nicht geladen hat, zeigt er einen *Fallback-Font*. Meist dauert dies nur einen Augenblick, darum ‘Flash’. Es gibt Browser, die gar nichts zeigen, bis die Fonts geladen sind: «FOIC» (flash of invisible text).

## Front End Design, Front End Engineering

Das Programmieren von Websites mit HTML, CSS und JavaScript, bzw. entpsrechenden *Frameworks*.
Weder Design noch Engineering sind besonders glückliche Bezeichnungen.

## Back End Design, Back End Engineering

Das programmieren Serverseitiger Software. Z.B. mit Python und PHP. Front End und Back End lassen sich nicht immer klar trennen. Faustregel: Alles was in den Browser kommt, ist Front End.

## API

Eine Schnittstelle für eine Programmiersprache.

## Reflow

Wenn das Satzbild sich durch eine Änderung im Text sich ändert, z.B. die Zeilen anders umbrechen, weil ein Wort breiter wurde.
Es gibt Schriften, die extra dafür konzipiert sind, dass es keinen *reflow* gibt, wenn Schnitte gegeneinander ausgetauscht werden, z.B. [Action](http://action.commercialtype.com/) von Erik van Blokland.

## Design Patterns
## Style Guide
## Style Tiles
## Responsive Web Design
## Fluid Web Design
## Adaptive Web Design
## Accessibility
## User Interface
## Mobile First
## User Centered Design
## Stakeholder
## Progressive Enhancement
## Interpolation
## Native
## Web
## Internet
## Reflow
## Performance
