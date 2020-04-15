## Cura wichtige Einstellungen

Wichtig: Vor Import des .3mf files in Cura unter Preferences->Configure Cura... die Option "Automatically drop models to the build plate" deaktivieren!

Falls die Teile sich nicht voneinander lösen lassen: Support Line Width reduzieren.
Falls Support nicht ordentlich abgelegt wird: Support Speed reduzieren.

### 0,6mm Nozzle

Quality
Layer Height: 			0,4   mm
Line Width:   			0,667 mm
Support Line Width: 	0,25  mm

Shell
Z-Seam Alignment:		User Specified (-> dann startet der Druck so, dass keine Travels notwendig sind)
Z Seam X:				-80 mm
Z Seam Y:				48,5 mm
Z Seam Relative:		ja

Speed:
so schnell wie mit dem jeweiligen Drucker sinnvoll, ich setze alles auf 35mm/s
Support Speed:  so langsam, dass das Supportlayer sauber abgelegt wird

Support:
generate Support:		nein (falls support durch zusätzliches Teil erzeugt wird), ja (falls Support von Cura erzeugt werden soll)
Support placement:		everywhere
Support Overhang Angle:	85 °
Support Pattern:		Concentric
Support Line Distance:	1,1 mm
Support Z Distance:		0 mm
Support Join Distance:	0,25 mm
Support Horizontal Exp.:-0,45 mm
