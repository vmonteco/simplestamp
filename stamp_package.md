# Slicing :

- [ ] Package
  - [ ] Package MVP
    - [ ] Licence
	  Creative Commons ?
	- [ ] README
	- [ ] Doc
	- [ ] Code
	  - [ ] Modes :
	    - [ ] Set up constants for modes
	    - [ ] \strong (Default)
		  Red, highly visible.
		  Should be default in order to ensure max protection by default.

		  Stamp background :
		  - color : red
		  - opacity : high

		  Border :
		  - color : red
		  - opacity : low

		  Text :
		  - color : red
		  - opacity : high

		- [ ] \regular
		  Grayish but visible.

		  Stamp background :
		  - color : gray
		  - opacity : High

		  Border :
		  - color : gray
		  - opacity : low

		  Text :
		  - color : gray
		  - opacity : high

		- [ ] \discreet
		  Grayish but less perceptible.

		  Stamp background :
		  - color : gray
		  - opacity : low

		  Border :
		  - color : gray
		  - opacity : none

		  Text :
		  - color : gray
		  - opacity : low

	  - [ ] Stamp utilities
	  	- [ ] \stamp
		  Takes one argument and encapsulates it into a bordered box (tcolorbox).
		  Uses the activated mode.

		- [ ] \motivatedstamp
		  Takes 3 arguments (Destinee, date, motive). Makes a stamp with \stamp out of it.
		  The text should have the following format :  

		- [ ] \tiltedstamp
		  Takes a stamp and tilts it.

		- [ ] \stampwholepage
		  Takes a stamp and covers whole page with it.

		- [ ] stamped signature.
		  This takes a picture and displays it, and puts a stamp on top of it.


- [ ] Bonus :
  - [ ] Code
  	- [ ] Noise
	  In order to make a watermark hard to remove.
	- [ ] i18n handling
	- [ ] Numerical signature
	- [ ] Override mode
	- [ ] Place stamp at coords
