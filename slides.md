---
title: Reverse Engineering iOS Apps
revealOptions:
    <!-- controls: false -->
    progress: true
---

<link rel="stylesheet" href="https://opensource.keycdn.com/fontawesome/4.7.0/font-awesome.min.css" integrity="sha384-dNpIIXE8U05kAbPhy3G1cz+yZmTzA6CY8Vg/u2L9xRnHjJiAK76m2BIEaSEV+/aU" crossorigin="anonymous">

# Reverse Engineering iOS Apps

---

### @kiliankoe 👋

[<i class="fa fa-github" aria-hidden="true"></i>](https://github.com/kiliankoe)
[<i class="fa fa-twitter" aria-hidden="true"></i>](https://twitter.com/kiliankoe)
[<i class="fa fa-rss" aria-hidden="true"></i>](https://blog.kilian.io)

---

### Was ist dieses *Reverse Engineering*?

note: Verstehen wie etwas funktioniert, nur anhand des Endergebnisses.

---

### Und warum? 🤔

----

> *"Wie ist das gebaut?"*

----

> *"Wie schaut die API aus?"*

----

> *"Warum passiert dieser Bug?"*

----

> *"Was für Daten werden von mir gesammelt?"*
note: Analytics und creepy stuff (Twitter)

---

### Was steckt in einer App?

----

#### Metadaten

Info.plist, (UserDefaults)

----

#### Assets

Bilder, Videos, Sounds, Fonts, Strings, etc.

----

#### Executable & Frameworks

---

### Was kann man damit machen?

----

### App 🏃‍♀️

Netzwerk-Zugriff

Code Injection

----

### App 🛑

Binaries dumpen

Im Bundle umschauen

---

### Netzwerk 📡

----

### Charles 🕵️

(oder [mitmproxy](https://mitmproxy.org))

---


### Ein Blick ins Bundle 👀

note: und daneben -> user defaults


---

### Code Injection 💉

[Cycript](http://www.cycript.org)

<span style="font-size: 14pt">(alternativ auch [Frida](https://www.frida.re))</span>

---

### Binary decrypten 🔓

[dumpdecrypted](https://github.com/conradev/dumpdecrypted)

[class-dump](https://github.com/nygard/class-dump)

[iOS-Runtime-Headers](https://github.com/nst/iOS-Runtime-Headers)

---

![](./n26.png)

#### [Shut Up And Take My Money @ 33c3](https://media.ccc.de/v/33c3-7969-shut_up_and_take_my_money)

---

### Fragen? 🙋

---

### Dank an 🙏

@saurik, @conradev, @optimo