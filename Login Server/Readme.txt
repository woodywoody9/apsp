│││││APSP│││││
│││IS BACKK│││
______________

BITTE ALLES GRÜNDLICH LESEN

Login SErver und die ganzen UDF's (außer mysql) sind von Jiyan Akgül. ( aka  Jiyan;jiyna006)
Die DB Struktur ( die 3 .sql dateien ) sind von  Christopher Kaster ( Kasoki )

Die mysql / mysql-com / MySQL_errmsg / mysql_version -.au3 sind von Prog@ndy ( ich kenn vollen namen net xD )


Index::
1. How-To's ( für die, die es ma testen möchten ;D )
2. Bemerkungen/infos ( Wichtig für Coder )
3.BUG GEFUNNE ?? 

;;; 1. HOW-TO'S ;;;;;
How-To Startup :

Als erstes erstellt ihr 3 DB's und batch dazu die 3 .sql dateien ( im DB ordner ).

Danach öffnet ihr die mysql.config & server.config und tragt alles ein.

Dann nur noch die Login.au3 mit SciTE öffnen und mit der F5-Taste starten
In ScitE erscheint dann unten eine Weiße Console.
Ich würde davon abraten es zu compilen, so leüft der Server schneller.

How-To Channel's eintragen.

Öffnet die apsp-server DB und dann geht ihr zur "Channels"-Tabelle.
Dort tragt ihr dann euren neuen channel ein oder editiert den alten.

Nach dem eintragen des channels geht ihr zur "Channel_users"-Tabelle.
Dort trägt ihr die Channel ID ein und dann wieveile benutzer 
maximal drauf können und das andere lässt ihr leer.

;;; 2. BEMERKUNGEN ;;;

Wer an den Files etwas ändenr möchte, darf es.
Ich würde davon abraten rgendwelche tool's zu machen,
da sich noch viel ändern könnte.

Wer mithelfen möchte
sollte sich erst ma die Login.au3 durchlesen und alles verstehen
dann noch selber etwas rumspielen.
Erst dann solte man sich bei mir oder Kasoki melden.
Wir nehmen nur Leute die es auch richtig können.
Denn wir kommen jetzt zum Char server ( an dem ich das letzte mal gescheitert bin ) 
und dann zum World Server.

Der Server lässt sich komischer weise nur im Source Modus nutzen.
Also wenn man es Compiled funktioniert er nicht oder nicht richtig.
Das liegt an einer der Dll's die der Server benutzt ( warscheinlich ASock.dll ) 
Also in SciTE ausführen, mit der F5-Taste.
Die Console erscheint unten.

;; 3.BUG GEFUNNE ?? 

WEnn du einen BUG gefunden hast.
Dann bite in ingamers / msn / ics / xFire melden.
Fals du an der Source twas geändert haben solltest.
Dann diese bitte mitschicken.



mfg Jiyan ( ^^ )

(c) 2009 by eVo-Soft Team