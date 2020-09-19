# Passcode-Security-System

The main objective of this project is to provide a passcode based security system having the
provision to change the passcode by the authority only, using XOR Gates as bit comparators
and NOR Gates as controlled inverters. This proposed system will provide a user friendly
security system for organizations and homes. If the passcode entered is right, it is indicated
by a LED. Any wrong attempt to open the door (by entering the wrong password), an alert
will be actuated, indicated by another LED.
This circuits the uses XOR gates as bit comparators. Four of these XOR gates compare the
respective bits of two 4-bit binary numbers, each number “entered” into the circuit via a set
of DIP switches. If the two numbers match, bit for bit, the green “Go” LED will light up
when the “Enter” pushbutton switch is pressed. If the two numbers do not exactly match, the
red “No go” LED will light up when the “Enter” pushbutton is pressed. Because four bits
provides a mere sixteen possible combinations, this lock circuit is not very sophisticated. The
“key” code that must be matched at the data entry switch array should be hidden from view.
If this were part of a real security system, the data entry switch assembly would be
located outside the door and the key code switch assembly behind the door with the rest of
the circuitry.
It is the nature of an XOR gate to output a “high” (1) signal if the input signals are not the
same logic state. The four XOR gates’ output terminals are connected through a diode
network which functions as a four-input OR gate: if any of the four XOR gates outputs a
“high” signal—indicating that the entered code and the key code are not identical—then a
“high” signal will be passed on to the NOR gate logic. If the two 4-bit codes are identical,
then none of the XOR gate outputs will be “high,” and the pull-down resistor connected to
the common sides of the diodes will provide a “low” signal state to the NOR logic. The NOR
gate logic performs a simple task: prevent either of the LEDs from turning on if the “Enter”
pushbutton is not pressed. Only when this pushbutton is pressed can either of the LEDs
energize. If the Enter switch is pressed and the XOR outputs are all “low,” the “Go” LED
will light up, indicating that the correct code has been entered. If the Enter switch is pressed
and any of the XOR outputs are “high,” the “No go” LED will light up, indicating that an
incorrect code has been entered
