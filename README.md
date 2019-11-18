
_Übungsaufgabe zur Veranstaltung [IT
Systeme](https://hsro-wif-it.github.io) im [Bachelorstudiengang
Wirtschaftsinformatik](https://www.th-rosenheim.de/technik/informatik-mathematik/wirtschaftsinformatik-bachelor/) an der [Hochschule Rosenheim](http://www.th-rosenheim.de)._

# 07 - Netzwerke Part I

Diese Übung behandelt das Thema _Netzwerke_. Zunächst mit dem Fokus auf die unteren beiden Layer des OSI Modells.

> Note: **Die Lösung befindet sich im Branch _Musterlösung_.**

## Aufgabe 1: Bandbreite, Nyquist, Shannon

Lösen Sie die folgenden Aufgaben:

### a)	
Ein rauschfreier Fernsehkanal habe eine Bandbreite von 7 MHz. Wie viele Bytes pro Sekunde kann man senden falls 4 Symbole / Signalschritte verwendet werden? Wie hoch ist die Baudrate? 

### b)	
Über einen rauschfreien Kanal der Bandbreite 4 kHz sollen Daten übertragen werden. Ist die mögliche Datenrate theoretisch nach oben begrenzt? Falls ja, begründen Sie ihre Antwort. Falls nein, erklären Sie wie man eine Datenrate von 8 kbits/s und 64 kbits/s erreichen könnte? 

### c)	
Wie hoch ist die Datenrate des Kanals aus Aufgabe a) maximal, falls es sich um einen verrauschten Kanal handelt und das Signal-to-Noise Ratio 30dB beträgt? 

## Aufgabe 2: Übertragungsmedien

Diskutieren Sie, ob es sich in den folgenden drei Fällen um ein Full-Duplex, Half-Duplex oder Simplex-System handelt!
•	Ölpipeline
•	Funkgerät / Walkie Talkie
•	Bach bzw. Fluss

## Aufgabe 3: Rahmenbildung

### a)	

Ein Link-Layer Protokoll verwendet folgende Zeichenkodierung:

```
A       01000111
B       11100011
FLAG	01111110
ESC  	11100000
```

Es soll der 4-Character-Frame „A B ESC FLAG“ übertragen werden. Welche Bitsequenz wird auf der Physical Layer jeweils in folgenden Fällen übertragen?

- **Byte Count**: Am Anfang des Frames wird die Länge des Frames binär-kodiert übertragen.
- **Byte Stuffing**: Anfang und Ende des Frames wird durch FLAG Zeichen markiert.
- **Bit Stuffing**: Anfang und Endes des Frames wird durch FLAG Zeichen markiert. Die Link Layer verwendet Bit Stuffing, falls sie das Bit 1 fünfmal hintereinander senden muss.

### b)	

Sie erhalten einen Frame. Auf Senderseite wurde das Bit Stuffing-Verfahren eingesetzt wie in der Vorlesung beschrieben. Kann der erhaltene Frame eine Folge von 6 1er-Bits enthalten?


## Aufgabe 4: MAC Adressen

### a)	
Wie lautet die MAC Adresse Ihres PCs? Wie können Sie diese über die Shell ermitteln? **Ggfs. Internet-Recherche!**

### b)	
Ermitteln Sie direkt über die MAC Adresse den Hersteller Ihrer Netzwerkkarte! https://macvendors.com/

### c)	
Versuchen Sie die MAC Adresse Ihres PCs zu ändern! Ggfs. Internet-Recherche!
Hinweis: Verwenden Sie falls möglich einen Ethernet-Netzwerkadapter, keinen WLAN-Netzwerkadapter! 
    
    >Note: Vergessen Sie nicht, die Original-MAC Adresse anschließend wiederherzustellen!

