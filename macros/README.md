# *This macro turning on and off watercooling of 3d printer

## When you have watercooled extruder, drivers, motors it was neccessary to be able run watercooling for each state but with standard way you are not able to assign one pin to multiple objects.

## It is based on delayed macro which works as timer interrupt and run code which check activity and temperatures of drivers, motors, extruder, using dummy fans with fake nonused pins which can combine behaviour of controller and heater fan. 



