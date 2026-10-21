Patch notes:

1.1 (Increased accuracy 5-10%)



# Lakki-s-Ballistic-Calculator
Ballistic calculator made for "Arma reforger". The calculator is a Python based program and the .exe should run on any device.

<img width="500" height="500" alt="ewrtheardtherhg" src="https://github.com/user-attachments/assets/cc9b9481-3e4f-462c-a36f-918a3f283aa1" />


# How to use:

1. Select the Weapon and Ammo type you want to use
2. Input the required information (Your own position and targets position)(Coordinate system uses 8 digits)
   
<img width="1920" height="907" alt="image" src="https://github.com/user-attachments/assets/b306c8b4-45a3-48ae-bb77-25748d789033" />

Example of what you should put in:
"07750735"

"0775" the horizontal coordinate, "0735" is the vertical coordinate

You can see the coordinates in the games map. The last digit is the smallest grid (100x100 meters) divided by 10. So the last digit of the coordinate is within 10 meter accuracy.

<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/a92af305-e72b-4bb4-b25d-4da729d69b33" />

3. Once all the information is entered, press "Calculate firing solution". You will hear a beep and the firing solution is outputted. If nothing happens or something weird happens, make sure that all the information is filled correctly.

4. If you miss your target, you can put the correction in the "correction" field in meters. For example, if you miss the target 20 meters east and 50 meters north, you put 20 meters in the "West" field and 50 meters in the "South" field. Press "Calculate firing solution" to recalculate the firing solution with the corrections.

