# PulsECG
![preview](https://github.com/sentomarco/PulsECG/blob/main/Files/PulsECG.gif)

Cardiovascular diseases (CVDs) have significant impacts on health, quality of life and economics, being the major cause of death and disability worldwide.  
Also in Europe, CVDs are the leading cause of death, accounting for 45% of all deceases  with an estimated cost of €210 billion annually.  
Addressing CVDs through prevention and monitoring is crucial to improve health expectancy and reducing the economic burden of these diseases.  
  
It is in this scenario that wearable smart devices fit: they allow self-monitoring of heart rate and activity, and other vital signs, providing feedback and making possible to cardiologists to remotely monitor and cure patients, allowing to detect early warning signs of CVDs and to intervene before complications occur.  
There are several devices that allow self monitoring of heart activity but they are not designed to provide a comprehensive diagnosis of cardiac conditions. They commonly provide just numerical information about heart activity and, less frequently, reports a single-lead ECG.  
  
This thesis project has the aims to study and to realise a wearable device capable to overcome these limitations, delivering a six derivations medical ECG in a non-invasive way.  
While a single-lead ECG offers a reduced diagnostic utility, showing the electrical activity of the heart from one direction only, a six-lead ECG is more useful for diagnosing cardiac conditions such as arrhythmias, ischaemias, and heart blocks, by recording information from six different electrodes placed on specific locations on chest and limbs.  
The device developed achieves these results using an ultra-compact design and employing only three electrodes by leveraging on the mathematical relationship which occurs between the six derivations.  
  
In general, the development of this appliance has gone through the following steps:  
• Design of the different functional blocks of the circuit.  
• Board design using OrCad software through schematic diagram and PCB design.  
• Development of firmware.  
• Implementation of digital signal processing techniques.  

![preview](https://github.com/sentomarco/PulsECG/blob/main/Files/Device.gif)  

To conclude, the combined use of digital and analog filtering of the signals acquired via three electrodes, made it possible to create a device capable of acquiring a high-quality
six-derivations electrocardiogram while maintaining an extremely compact design.The integration with the smartphone application allows the storing of ECG data for future analysis and references, moreover, the possibility of sharing data sets the basis for fast and efficient diagnosis of heart diseases.  
