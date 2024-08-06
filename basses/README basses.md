# Documentation basses chiffrée

## Figured bass

* Figures are placed above the staff by @place="above"
* Duration of extender lines is defined by @tstamp="" and @tstamp2=""
* Although not necessary, the existence of the extender line is coded by @extender="true"
* @tstamp2 marks the first beat where the harmony doesn't apply anymore. Example: For figures that last a whole bar in 3/4 the code is: tstamp="1" tstamp2="4" extender="true"
* For a line over multiple bars @tstamp2 can contain the formula "xm+y". x indicates the number of bar lines, y the position in the last bar.
* Some files contain empty < f > elements for a better layout that clarifies the voice leading according to the source. This applies to basses: 36, 38, 39, 40, 48, 50, 51, 53, 57, 68.
* Sometimes the exact position of a figure is unclear because the bass holds a long note. The position was guessed according to the context. This applies to basses: 15, 43, 57, 59.
* Crossed out 5ths and 7ths are created with their unicode: 5ths - &#xEA5F , 7ths -  &#xEA5A


## Unsolved issues

* In many basses Cherubini uses a crossed out 5th with a circle on top. This symbol is yet to be created, for now the circle is coded in an extra < f > element above the 5th.
* In basse 29 Cherubini uses a crossed out 2 which is rather unusual. This basse will be checked again in the manuscript source. If it is correct a way to depict the symbol has to be found.
* Basses 51, 53 and 54 are very similar. Maybe their incipits have to be longer so they can be differentiated more easily.
* Basses 1 and 70 are very similar, their incipits only differ in the figured bass.


## Errata
* Basse 57 m. 4: The last g in the bar may be an error in the edition and should be f#. This will be checked.