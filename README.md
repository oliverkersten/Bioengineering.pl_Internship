# Graduation internship report attachments (HD-SEMG system ADS1298)
Thiss folder includes: Hardware files, software files, python application, MATLAB and report, design was to build a protable and wireless HD-SEMG aquisition system for my graduation internship of my electrical engineering degree at Hogeschool Rotterdam, the internship took place at bio-engineering.pl Sp.z o (www.bioengineering.pl) in Wroclaw Poland.

The hypothesis of the project was ”Can the AMAC performance be improved in direct controlled (DC) myoelectric systems, by exactly locating the location where the patient has the most amount of controll over the agonist and antagonist of the residual limb during different hand gestures’’. The goal was to develop a device that can be used to confirm this hypothesis, the could be achieved by measuring the muscle potentials over the residual limb during different hand gestures (HD-SEMG recording)

In the project multiple AFE were designed were presented (based on AD8232 adn INA333), the function of the AFE to amplify and filter the EMG signal. THe EMG channels were digitezed using the ADS1298. The ADC register data is read from the ADS1298 via an Arduino DUE (SAM3X8E)/ STM32F4. A PC application was developed to visualize the data and verifiy certain system specification (CMRR, IRN and Gain). The Current design is capable of measuring up to 1kSps with the Arduino DUE and to >4kSps with the STM32F411, the problem with the STM32F4 is the the Python application and realterm cannot open the USB port (CDC) to read the data, but it can be open in Tera term. If anybody knows why I would be happy to know :) 

 If you would like to continue this project Idea, feel to contact me for more info about the future improvements or any other questions about the design of the project.

# Contact details
 If you have any questions about the project feel free to contact me at: okersten@gmail.com
