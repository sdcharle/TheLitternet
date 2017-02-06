# TheLitternet
Internet-enabled cat litter box, because.

This uses a Wii Balance Board I found at the Bloomington, IN Goodwill for $4.99. It tracks the weight of the litterbox over time, keeping a running average and notifying when there's a change in readings greater than some threshold. The magnitude of these changes can also tell you things like which animal is in there. You could put an air horn in there to scare your dog if she goes where she shouldn't sometimes.

## Credits

Inspiration plus code to steal and hack came from these guys:

Stavros Korokithakis really got the ball rolling by simplifying some earlier attempts at interfacing with the balance board. This is in his [gr8w8upd8m8 repo](https://github.com/skorokithakis/gr8w8upd8m8). He also wrote an [enlightening blog post](https://www.stavros.io/posts/your-weight-online/).

The dudes at InitialState created and shared the [Beer/Wine Fridge Of Awesomeness](https://github.com/InitialState/beerfridge) which did everything I wanted to do and actually more. [wiiboard_test.py] (https://github.com/initialstate/beerfridge/blob/master/wiiboard_test.py) is kind of the ideal script to get started with Balance Board Hacking.

Some technical details about the board's Bluetooth interface can be found [here](http://wiibrew.org/wiki/Wii_Balance_Board#Calibration_Data).

#Have fun!
