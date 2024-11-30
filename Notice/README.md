#This is used to record the probelm and solution
* FIRST<br>
Q:one touchpad sensor was broken, the issue came from two sensor using same power supply, which may drive larger current through the sensor. <br>
When two sensors connected in the circuit, it always shows "not connectcedxxxxx".
A:the datasheet shows it should be connnected with 5V, after take VCC as positive, the issus solved.<br>

* SECOND
Q:Multiple event triggered at the same time, overlap problem occurred
A:Multiple if statement run in same time.
