# app3
Expand client application with activity presenting measurement data and user inputs in the form
of a dynamic list or table.
(a) The interface should contain a dynamic list or table with the available measurements (e.g.
angular orientation (RPY), temperature, pressure and humidity from the Sense Hat add-on)
and the status of the user inputs (e.g. the three counters (XYC) of the joystick from the
Sense Hat add-on). Each element of the list / table should contain information about the
name of the measurement or input and its current state with the unit. The list / table may
contain additional information about the measurement or input (ID, range, timestamp, etc.).
Remember that, for example, the temperature on the Sense Hat board can be measured by
two dierent sensors. Use previously prepared graphic interface prototype designs.
(b) The application should cyclically request data from server and display responses in the form
of dynamic list / table. Application doesn't have to use data binding.
(c) Run and test app on a physical or virtual mobile device. Make sure the network communication is working properly. You can use a physical or virtual embedded device for testing, or
a server mock in the form of a local CGI script generating random synthetic measurement
data.
