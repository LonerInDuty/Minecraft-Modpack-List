### How to setup Simply Magic (Distant Horizons, Java 25)

#### As a general tip, ALWAYS check the [Optimization Guide](https://github.com/Polytetrafluoroethylene-PTFE/MC-Optimization-Guide). It lists the best Java and Java settings for each version, the best mods for each version, AND how to optimize specific modpacks. It's the holy grail of optimization.

* Download and Install [Adoptium Java 8, 21 and 25](https://adoptium.net/temurin/releases).

* [Download my package for Simply Magic](https://files.catbox.moe/eklf7l.zip), import it into Prism, then run it.
A window will pop up.

* At the very top, click Find and go to **C:\Program Files\Eclipse Adoptium\jdk-25.X.X.X-hotspot\bin**

* Select **javaw.exe**

* Now for the Min memory and Max memory. Set both to the same value depending on these conditions:
  - You have 16gb of RAM or more, and wants Distant Horizons - Set to 10240mb.
  - You have 16gb of RAM or more, and will disable Distant Horizons - Set to 8192mb or 6144mb
  - You have 8gb of RAM or less - **Disable Distant Horizons** and set to 4096mb.

* On the 'Garbage Collector' drop-down menu:
  - If you have 16gb of RAM or more - Set to GenerationalZGC, and on the type-able box below, copy and paste this: -XX:+UseCompactObjectHeaders
  - If you have less than 16gb - Set to G1GC

* Run the game. You're done.

### Some mods don't work with Java 25, which is why I recommend having Java 21 installed, just in case.
