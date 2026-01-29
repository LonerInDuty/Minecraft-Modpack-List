## How to setup Simply Magic (Distant Horizons, Java 25)

## As a general tip, ALWAYS check the [Optimization Guide](). It lists the best Java and Java settings for each version, the best mods for each version, AND how to optimize specific modpacks. It's the holy grail of optimization.

* Download and Install [Adoptium Java 8, 21 and 25](https://adoptium.net/temurin/releases).

* [Download my package for Simply Magic](https://files.catbox.moe/eklf7l.zip), import it into Prism, then run it.
A window will pop up.

* At the very top, click Find and go to **C:\Program Files\Eclipse Adoptium\jdk-25.X.X.X-hotspot\bin**

* Select **javaw.exe**

* Select **GenerationalZGC** on the drop down menu.

* On the type-able box below the drop-down, **copy and paste this:** -XX:+UseCompactObjectHeaders

* Run the game. You're done. Feel free to disable Distant Horizons if your game lags.

## Some mods don't work with Java 25, which is why I recommend having Java 21 installed, just in case.