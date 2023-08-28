# BMICalc

<b>PROJECT TITLE</b></br></br> 
BMI CALCULATOR<br></br>
<b>DESCRIPTION</b></br></br>
The BMI Calculator is a GUI program to calculate the user's Body Mass based on their weight and height. The program is written in python programming language 3.9 and it is in no way to replace the one seen online. This can be used on the Desktop but more features will be added later.</br></br>
<b>USAGE</b></br></br>
<b>STEP 1:</b> When the application loads, you will see the Graphical User Interface (GUI) as shown below:</br></br>
![BMIINTERFACE](https://github.com/Iyke3D/BMICalc/assets/118365903/5b3fbbc7-9c66-4945-94a9-6844d5ccf207)</br>

<b>STEP 2:</b> Input your Feet, Height, and Weight in each field's respective textbox (See Figure 1 above)</br></br>
<b>STEP 3:</b> Click the Calculate BMI button to show the caculation and remark (Figure 2)</br></br>
![BMICALC](https://github.com/Iyke3D/BMICalc/assets/118365903/301a3f5a-2af2-463a-971b-c8c44718197a)</br></br>

<b>ERROR CORRECTION</b></br>
As with any good program, each input is checked first before calculating the BMI and generating the remark.</br></br>
![BMI](https://github.com/Iyke3D/BMICalc/assets/118365903/49cf5a06-cd44-420e-8bec-9b4f65bd0233)

<b>VERSION UPDATE</b></br>
The version is BMIC Ver 1 and any update will be shown here.</br></br>  
<b>DEPLOYMENT</b></br>
To run this file, make sure that python is installed (Using Python 3.9 or more) and press F5 using IDLE IDE. But any IDE like Visual Studio Code or any IDE will do. To convert to an executable (.exe), you have two options:</br></br> 
<b>STEP 1:</b> First install pyinstaller via the command line or terminal by typing...pip install pyinstaller</br></br>
<b>STEP 2:</b> Type the following in the command line. </br></br>
pyinstaller --onefile --windowed --add-data "xi.icon;" BMI.py </br></br>
<b>STEP 3:</b> Allow pyinstaller to compile the file and add all the resources and dependencies needed to create the executable.</br></br>
<b>STEP 4:</b> Check the folder and run the exe in another computer. It will successfully run</br></br>
Alternatively (and even better option), you can use auto-py-to-exe to generate the executable. This normally opens a GUI for compiling your programs. First install auto-py-to-exe by typing the following in the commandline: pip install auto-py-to-exe and then follow the steps as shown below:</br></br>
![i](https://github.com/Iyke3D/BMICalc/assets/118365903/225649fa-34db-43ea-a2ba-40dcdb0140bc)</br></br>

Notice that python39.dll was added. This will help run the program in older versions of Windows eg Windows 7, 8, 8.1 (probably they have not been updated for a long time. This will avoid generating errors such as the one shown in issues section). </br></br>
<b>ISSUES</b></br></br>
Please note that your Windows Defender Antivirus (and some other antimalware programs) may block the application from running. This is a false positive error message. Kindly pause the protection for a while and run again. The dependency python39 must be added to avoid errors such as the one shown below:</br></br>
![python39 error](https://github.com/Iyke3D/BMICalc/assets/118365903/06156097-36f6-4da1-9ff5-9a56453d7be6)</br></br>

![Failed Message DLL](https://github.com/Iyke3D/BMICalc/assets/118365903/a79a24c9-bc7f-4ed5-8989-b21a0a15a440)</br></br>

The python39 is saved in the AppData folder. As shown in the image below:</br></br>
![python39](https://github.com/Iyke3D/BMICalc/assets/118365903/ad3f8419-f0bb-4b8a-b950-2f37750b9b7f)</br></br>

![i](https://github.com/Iyke3D/BMICalc/assets/118365903/45b59ea5-fa30-4ef7-81c1-0764c035e22d)
