# fhm_notenspiegel
Kleines Programm um den Notenspiegel-Link einer Prüfung zu bekommen. 
Folgende Infos braucht das Programm
- URL von Primuss nach dem Einloggen
- Studiengang Kürzel. Zweistellig.
  Findet Ihr unter Primuss - Services - Prüfungsanmeldung - PDF rauslassen -> In der Tabelle sichtbar
  - Beispiele
    - AR = Architektur Bachelor/Master
    - BI/BN = BauIngenieur Bachelor/Master
    - BW = BWL Bachelor/Master
    - CH = Chemische Technik Bachelor
    - EL = Elektrotechnik Master
    - EM = Elektrotechnik Elektromobilität Bachelor
    - RE = Elektrotechnik	Regenerative Energien Bachelor
    - FA = Fahrzeugtechnik Bachelor/Master
    - GT = Gebäudetechnik Master
    - IF/IG = Informatik Bachlor/Master
    - LR = Luft- und Raumfahrttechnik Bachelor/Master
    - MB = Maschinenbau Bachelor/Master
    - MF = Mechatronik Bachelor/Master
    - MT = Mechatronik Teilzeit
    - SB = Soz.Arbeit BASA
    - SR = Soz.Arbeit Teilzeit Bachelor
    - SW = Soz.Arbeit Bachelor
    - TR = Tourismus-Management Bachelor/Master
    - WI = Wirtschaftsingenieur Bachelor
    
    - AW = AW Prüfung
- Prüfungsnummer -> Aus der Anmeldungs PDF. Ist dreistellig.
- Angabe ob Bachelor oder Master. Bei AW Fächern leer lassen.

Danach auf den Button und der Link ist in der Zwischenablage.
Das Programm sollte solange gehen bis die HM iwas am URL ändert.
Mein erstes Python Programm also safe was zu korrigieren.

HowTo:
1. Normal in Primuss einloggen. Die URL ist dann iwas wie \
https://www3.primuss.de/cgi-bin/sesam/index.pl?FH=fhm&Session=XXXX&User=YYYYY&Portal=1 \
Die XXX stehen für random Buchstaben die der Session Key sind. Die YYY sind die Magnetkartennummer.
2. Den URL wie aus der URL Leiste in das Programm einfügen.
3. Einstellen welche Prüfungsnummer (-> Prüfungsanmeldung -> Dreistellige Nummer), Studiengangskürzel, Angabe ob Bachelor, Master oder AW (Leer).
4. Den Button klicken. Die angepasste URL ist jetzt in der Zwischenablage. 
5. Dann im selben Browser aufrufen. Da Shibbaloth (Login-Server) Cookies setzt muss es der selbe Browser wie beim Login sein.
