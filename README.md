# VBA <br>
The macro sorts and orders and compares the measured values (cloud of points) against master data and checks wheher measuremenet system shows acceptable values or needs to be re-adjusted.<br>
Steps:<br>
Module Pinhole_Calibration_Start<br>
User opens raw data file<br>
User picks one of two type measurement systems (APIS or HAPI)<br>
User picks one of two analisys types - XY (position of measurement point) or sizing (size of measuerement points)<br>
User picks position of measured sample in box with other samples<br>
Macro assigns measured values to master data<br>
Macro checks for missing measured values<br>
Macro checks for multiple measured values and assings the one that is closest to master data<br>
Macro presents data in chart with visual representation of deviation between master data and measured value<br>
Macro marks NOK values red and assigns "NOK" comment at respective value<br>
