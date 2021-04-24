# HomeAutomation
Home automation using Arduino Uno

#overview
step 1: connect the arduino oard to our device and put the code in it using arduino ide
step 2: connect the relay module and bluetooth modle(HC-05) to your arduino board using jumper wires
step 3: connect your equipments to the relay module
step 4: operate it using bluetooth terminal app(i personallyy use 'Bluetooth device controller' availale on play store)

#connection
  #relay to arduino
  connect relay 4 to pin 2
  connect relay 3 to pin 3
  connect relay 2 to pin 4
  connect relay 1 to pin 5
  connect vcc to 5v on arduino
  connect GND to GND on arduino
 
  #bloetooth(hc-05) to arduino
  connect tx on hc-05 to rx of arduino
  connect rx on hc-05 to tx of arduino
  connect vcc to 5v on arduino
  connect GND to GND on arduino
  
 #operation 
 press a to turn relay 4 high
 press b to turn relay 4 low
 press c to turn relay 3 high
 press d to turn relay 3 low
 press e to turn relay 2 high
 press f to turn relay 2 low
 press g to turn relay 1 high
 press h to turn relay 1 low
 press x to turn all relays high
 press y to turn all relays low
