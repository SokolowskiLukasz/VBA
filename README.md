# VBA
The macro sorts and orders and compares the measured values (cloud of points) against master data and checks wheher measuremenet system shows acceptable values or needs to be re-adjusted.
Steps:
User opens raw data file
User picks one of two type measurement systems (APIS or HAPI)
User picks one of two analisys types - XY (position of measurement point) or sizing (size of measuerement points)
User picks position of measured sample in box with other samples
Macro assigns measured values to master data
Macro checks for missing measured values
Macro checks for multiple measured values and assings the one that is closest to master data
Macro presents data in chart with visual representation of deviation between master data and measured value
Macro marks NOK values red and assigns "NOK" comment at respective value
