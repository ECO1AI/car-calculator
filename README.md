# Car-Calculator

a spreadsheet (.ods) file to generate graphs for your car

_____________________________________________________________________________________________

## Current features:

1- outputs RPM Vs Speed graph (similar to racing games)

2- outputs Torque Vs RPM per shift

3- Torque & Horse Power Vs RPM (usual graph)

4- displays Final Gear ratio (Transmission + differential)

5- accepts either measured date or from datasheet

## How to use:

### 1- download latest release from [releases page](https://github.com/ECO1AI/car-calculator/releases/)

### 2- open it using spreadsheet app (tested with [liberOffice](https://www.libreoffice.org/) and is the recomended)

(it is recommended to create a copy and using the copy)

### 3- go to "interface sheet"

![Screenshot_٢٠٢٥٠٣٢٦_٠٠٥٨٤٣](https://github.com/user-attachments/assets/c546a89f-f2cb-45f4-82b2-005a901105cc)

(note that i use dark theme, UI may vary)

you should see the following :

![Screenshot_٢٠٢٥٠٣٢٦_٠١٢٠١٣](https://github.com/user-attachments/assets/cc6fffaa-829c-4f76-b07a-43611ce04ff2)

start by changing number of shifts [current limitation is 10 gears]

then redline limit (the fastest your engine can run) 

[current limitation is 9000 RPM] and is counted from 500 RPM with increment of 500 RPM

#### Gear ratio:

if you have Transmission and differential gear ratio then check the box:

    if you have final gear ration (both combined) then set differential gear ratio to 1 and fill the rest in the table bellow

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٠٢٥٦](https://github.com/user-attachments/assets/3f477db3-80fa-44cd-96d1-796fed883dce)

then insert gear ratio per gear(shift)

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٣٠٤٦](https://github.com/user-attachments/assets/2ee108d5-19d8-42f1-81b1-a37f45d257d5)


if you dont have, dont worry and uncheck it

then insert speed and RPM (**how do i get them?**)



to get speed and RPM you need OBD2 adapter and an app like [torque]([Torque OBD 2 engine diagnostics — Torque](https://torque-bhp.com/software/torque-android-obd2-adapters/)) , then set it up to show RPM and Speed

after that you need to go through each shift and take a screen shot for every shift near the specified RPM per transmission:

for MT RPM of 1500 is good enough

for AMT and DCT it is better to keep RPM at 2000

for AT with torque converter RPM > 2000

**Note1: for AMT,DCT,AT use manual mode of shift limiters**

**Note2: for AT be sure that torque converter is locked and is not slipping.**

**Note3: adhere to traffic laws and insure your and surrounding safety.**



### then insert speed and RPM:

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٣٣٢١](https://github.com/user-attachments/assets/059f8d8d-e8fa-4aba-bd85-32d1e3c465f9)

### if you have "engine" torque and horse power then check th corresponding box:

then fill the corresponding table

dont fill columns with RPM 0

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٤٥٢٨](https://github.com/user-attachments/assets/90121b17-68e0-4c7f-a298-d3dc70d833ec)

### lastly insert your tyre size

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٤٦٠٩](https://github.com/user-attachments/assets/efafbe4a-c06b-4b58-810d-02ded13eb433)

### to see the results go to output sheet

you will see the graphs like this:

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٥١١١](https://github.com/user-attachments/assets/51755674-1e5a-4d02-be94-656ddc3a0648)

this is because there is extra data

right click on the graph, then click edit. after that go to data range from right click menu and remove extra data in data series tab:

![Screenshot_٢٠٢٥٠٣٢٦_٠٢٥٥٠٢](https://github.com/user-attachments/assets/487289ec-4453-48ea-9dc3-73a19772abaa)

### edit graphs and add notes as needed

change colors and so on

### lastly print

on "output" sheet, press Ctrl + p o print the sheep

and enjoy
