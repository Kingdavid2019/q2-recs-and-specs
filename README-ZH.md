# q1-hens0019

SKETCH BY ZACHARY HENSON

![ACUI_Sketch 4](https://user-images.githubusercontent.com/47228185/93420665-09f2f180-f875-11ea-83fd-f0b34e881de3.jpg)

General Layout:

  The leftmost side of the panel is used to display the menu the user is in. The arrows above and below the menu name represents a method 
to change the values in certain menus. The only "buttons" that do not take the user into a menu are "Air Cycle" and 
"Defog". Finally, settings lies in the bottom corner so that users may change things like screen brightness (Day and Night preference), language, preferred 
temperature measurement, menu/text colors, and text size. Furthermore, it is important to note that the visualized sketch applies to a 
driver left side vehicle. For driver right side vehicles, the positions of the buttons will be on the right (i.e Sketch 1: the arrows, home display, 
and Settings would be on the rightmost side and the order of the bottom row from left of settings to leftmost corner would be: AC, Fan, Air, Defog, Vent).

-Sketch 1: General Home Menu

  The Home menu displays current Fan Speed and desired AC Temperature. Furthermore, it also displays if the Air Cycle is Internal or External.
The arrows do not do anything on this menu. None of the buttons at the bottom should highlighted in any paricular color until the user starts 
interacting with the system. This means that the UI system will not save tempurature and fan settings once the vehicle is turned off. As for 
vent settings, the vent will be in the position the user last selected.
  
-Sketch 2: AC Menu
  
  When switched to the AC Menu, the middle box on the leftmost side of the panel switches to say "AC" and the "AC" button (bottom) will 
be highlighted. The AC Menu Displays the current desired Tempurature (in the user selected temperature measurement system). 
Below there is a meter with two outward facing arrows at each end. The meter has a vertical solid bar, with the meter to the left 
of the bar being filled in.  Note that color depends on user preference. 
This meter indicates the desired temperature, with the bar being unable to move past either 65 degrees (F) or 85 degrees (F). 
The bar can move in 3 ways: 
1) Tapping the left/right outward arrows moves the bar in the respective direction 
2) Tapping the up/down arrow on the leftmost side of the panel raises/lowers the temperature value, therefore moving the bar
3) The user can decide to manually slide the bar by touching the bar, holding the touch, and then sliding the bar left/right. 

When the bar moves, so to does the filled in portion of the meter, always staying on the left of the bar. These positions and mechanics are 
not affected by the vehicle's driver side. Below this temperature meter, a button to indicate if the AC is on/off lies. 
By tapping this button, the user can decide to turn on/off the vehicle's AC. ON means that the vehicle is cooling the inside, 
while OFF means that it is heating the inside. The button display will alternate ON/OFF when pressed.
Finally, an X lies in the top right corner to return to the home menu (top left for right wheel drive).

-Sketch 3: Fan Menu
  
  Like the AC Menu, the Fan Menu will display "Fan" on the left and the Fan button (bottom) will be highlighted. 
Like the AC menu, the current fan speed is displayed at the top. Below the fan speed, there is a box displaying the fan speed. 
On either side of the box, outward facing arrows to the left and right control the fan speed. Both these outward arrows and the 
up/down arrows on the leftmost side of the panel change the fan speed. Tapping left or down lowers the speed, while tapping right or up raises it.
The values that can be selected range between 1 and N (some max fan speed level designated by the manufacturer/desginer). 
Below the display and arrows is the off button for the fan. When the OFF is selected, it shuts down the Fan and AC. 
To restart both of the Fan and AC, the user needs to tap right arrow in the menu to bring the fan speed back up to 1. 
None of these mechanics are affected by the vehicle's driver side. Once again, there is an X in the upper right 
corner (left for driver right side) to return to the Home screen.

-Sketch 4: Vent Menu
  
  Again like the AC and Fan Menus, the left panel will display "Vent" and the Vent button (bottom) will be highlighted. The arrows on the left side 
do not affect anything in the menu. The words "Vent Position" are displayed on the screen. Below these words are boxes displaying an icon. 
These icons represent the vent position desired by the user. The desired position can be selected by tapping the appropriate icon box. 
A selected position will be designated by highlighting the box. As a special note, the menu does not need to contain 5 boxes as seen in the sketch. 
The number of boxes and appropriate icons can be designated by manufacturer/designer. Again, these mechanics are not affected by the driver's side.
Finally the X button lies in the top left/right to return to the home screen.

-Air Cycle and Defog:
  
  These two button effectively alternate between two settings. For Air Cycle, it is either "Internal" or "External". Whichever mode is selected is 
displayed in the top right (top left for driver right) corner of the Home screen. As for Defog, the two settings are either ON or OFF. If the Defog 
button is highlighted, then it is ON; if not, then it is OFF.

Other Considerations:

-Customers:
  In terms of manufacturers and designers, this type of UI is more partial to those that have the capability to integrate a touchscreen into their 
vehicle. Furthermore, they must be able to determine a method to get around the fact that the UI spans various menus and takes up most of the screen. 
However, since many mainstream (at least in the US) vehicle manufacturers have some sort of capability to do so, that means this UI could apply to them. 
As for actual drivers, due to the interactive UI, it may be dangerous for people with certain disabilities to operate the UI while driving. In the end,
any customer would be up to driver discretion as to whether they think they can safely use the system and operate their vehicle.

-Disability Support:
  As mentioned in the Customers section, it may be dangerous to operate the UI given certain disabilities. Specifc options in the Settings 
like color, text size, and brightness can help alleviate some of these risks for some disabilities; however, it is difficult to cover 
all the possible disability scenarios and vehicle limitations. Therefore, in the end, it would be up to the individual driver to 
determine if they can handle operating the vehicle and UI at the same time. 

-Different Countries:
  It is recognized that it is possible that this UI may be used outside the US. As such, the Settings contains language and temperature measurement 
preferences.

-Driving Conditions
  The main driving scenarios this conceptual sketch aims to cover are driving during: Daytime (clear or cloudy skies), Nighttime, and 
various weather conditions. With these scenarios, the user difined brightness Settings can help alleviate the luminosity concerns many tend to think of. 
It is recognized that other scenarios are possible; in such cases, the sketch of this climate control UI probably does not cover such scenarios.
