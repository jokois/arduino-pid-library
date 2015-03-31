
---

**AS PER THE REQUEST OF THE ARDUINO TEAM, THE ARDUINO PID LIBRARY**
**HAS BEEN MOVED TO GIT-HUB** ( https://github.com/br3ttb/Arduino-PID-Library )
**THESE FILES HAVE BEEN LEFT HERE FOR REFERENCE PURPOSES ONLY, AND ARE**
**NOT TO BE CONSIDERED USABLE**

---



PID Controllers are found everywhere in industry, controlling all sorts of things: Temperature, Level, and Flow, among others.  The reason they're so prevalent is because they're simple and effective.

There has been a [Barebones PID algorithm](http://www.arduino.cc/playground/Main/BarebonesPIDForEspresso) available for the Arduino for some time now. The goal of this library was to create a more modular pid controller on-par with those found in industry.  All of the standard industrial error checks are in there.  The main improvements that this Library brings are:

  * Speed of implementation. you still have to tune it, but the coding/debugging piece is easier.

  * The ability to change tunings on the fly (i.e. while in Auto)

  * The Addition of output limits

  * Being a Library, multiple PIDs can be easily created within the same program

  * The option of putting the controller in Manual (turning it off / reinitializing it)

  * Reset-Windup mitigation (the previously published Arduino PID addressed this somewhat.  This library does it in a more comprehensive way)


Documentation can be found at http://www.arduino.cc/playground/Code/PIDLibrary