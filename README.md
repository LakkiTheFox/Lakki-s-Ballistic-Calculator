

# Lakki-s-Ballistic-Calculator
Ballistic calculator made for "Arma reforger". The calculator is a Python based program and the .exe should run on any device.

<img width="500" height="500" alt="ewrtheardtherhg" src="https://github.com/user-attachments/assets/cc9b9481-3e4f-462c-a36f-918a3f283aa1" />

<img width="4491" height="912" alt="image" src="https://github.com/user-attachments/assets/9dbdeef9-096f-4bd5-bcad-d1ace481d77d" />

# How to use:

1. Select the mortar you want to use
- M252 
- 2B14

2. Select mortar armmo type
- High-explosive
- Smoke
- Flare
   
3. Input coordinates. (The game gives you 3 numbers for a coordinate) (You get the last two by dividing the grid by 100) ( 3+2 - 3+2 )
   
4. Once the information is filled (Bare minimum: weapon, ammo, mortar and target coordinates), press "Calculate firing solution" to get the required information
- If something funky happens, most likely it is due to incorrect filling of text fields
     

   
# Coordinate example:
Coordinate = 553 194

553 is yor horizontal coordinate

194 is your vertical coordinate

Divide the grid to by 100 (00-99) (Horizontal, Left to right)

Divide the grid to by 100 (00-99) (Vertical, Bottom to top)

If using the example below, the coordinate would be the following:

55325-19475

<img width="1900" height="1890" alt="image" src="https://github.com/user-attachments/assets/05c30efb-d877-4f91-8c95-dce9d04edcac" />


# Corrections:

If you miss the target, you can use the "correction" feature. You can input either one or multiple corrections. You need to put the correction in meters in the corresponding box. Once you press "calculate firing solution" again with the corrections, the text fields will be emptied and the target coordinate will have the corrections applied to it.


# Correction example:

You shoot three rounds of high explosive on the target. Forward observer radios that you missed the target to the south by 150 meters and to the east by 50 meters.

You put the same distance in the opposite directions text field.

In this case, put "150" in the North field and "50" to the West field. You are basically telling the calculator, what way you want to move the aiming position relative to NESW.

NOTE: The correction feature does not correct height. On a flat field this has no effect, but if the elevation changes significantly between corrections, change the "target height" to the correct height.

