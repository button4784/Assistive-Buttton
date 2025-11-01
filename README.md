# Assistive-Buttton
Our Assistive Switch is to be an open source button that can be made under 100$ from the materials required, as well as being Bluetooth (not including other factors like 3d Printers). We made our switch for the reason that many assistive buttons can be expensive, for example, on the website TTLC, an assistive switch from Pretorian Technologies sells a switch that is 210$ without taxes or shipping fees. As well the manufactures make it difficult to make it repairable or modifiable in the function, and astethics. Our goal with being open source is that it allows others to build the switch from the 3d blueprints and a bit of wiring, while being easy to build with instructions. The majority of the switch we have created is 3d printable, which allows people to make the color different depending on which materials to make it more aesthetically pleasing.

# Functionality
The switch has functions just like any other assistive switch on the market, and on button press, it activates a keypress or computer command such as 'K' or 'Enter'. It does this through a cherry mechanical switch of any kind and on keypress, sends the code to the Arduino, which then sends it to the specified device through Bluetooth.

# Materials-And-Material-Cost (current of 2025)
The materials to make this switch are: <br/>
ESP32 Board (aurduino version only) $18.30 <br/>
3.7v Lithium Battery Pouch $12.50 <br/>
Battery Charger Module (USB-C) $6.00 <br/>
JST Cables (Male & Female) 2$ <br/>
3.3v Voltage Regulator $0.50 <br/>
PLA For the 3d printer 1$ <br/>
With a total coming about to be 40$ (minus the cost of the 3d printer) <br/>
Addional items include a sodering tool, any kind of wire cutters, and a computer to change the button output.

# QnA: <br/>

Q: What is the point of the battery? <br/>
A: The battery is so that is bluetooth functionality works without constant power from the computer <br/>

Q: Why is a voltage regulator included in the list of parts? <br/>
A: The voltage regular is needed to limit the voltage to the aurduino so that it only receives the corrent amount of voltage at once. In testing, giving it a constant stream of power from the battery is inconsistant causing it to turn on and off or stop working at times. Giving it more power than it needs can wear out the aurduino and break it permantly.

# DIY steps

1. In the bottom of the post you will find a link to files which you can send to a 3d printer in order to print it. Print it all out and order the parts listed above (links are provided for where to buy the parts, may be outdated however you can still order based on the names from sites such as Digikey)
2. Assemble the button and place the items in the designated slots shown in the bottom piece of the button housing. to connect eveything you would...

   next edit in 2w once full design is finished
