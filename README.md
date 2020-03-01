# Data-Path-Controller

## 1. Introdution

The Output of the demodulator having clock and bit stream data is routed to Front End Hardware (FEH) unit via Data Path Controller (DPC).The satellite input port terminals are routed to the certain output port terminals with the help of the switching technique, which is used in Data Path controller (DPC).The data Path controller is nothing but to control the flow of data from the input terminal to the output terminal port and the input is assigned to the certain output port.

### 1.1 GUI Design for DPC

* The Data Path controller’s GUI unit is designed using _Fluent windows platform_ in visual studio allowing user to have clean and smooth User Experience, User Interface like windows.

* _Fluent windows Platform_ allows user to use their native codes which consists of pre build templates allowing user to design interactively.

* The GUI for Data Path Controller is developed using _visual studio (IDE) v2019_ keeping effectiveness, scalability, performance in mind.

## 2. Methodology

### 2.1 Operations for GUI of DPC

* The GUI for Data path controller consists of 16 input switches and 16 output switches.

* The values for input switches range from 01 – 16 which are hardcoded and the values for the output switches are selected using a drop down menu which consists of values from 01 – 16.

* After selecting the values of the output switches through the drop down combo box the respective output switch value is appended to the input switch value.

* The input - output data is of 4 bit data stream of a single switch.

* After clicking the submit button the combined 4 bit steam of 16 switches is then sent to the desired executable code through a backend connection consisting of TCP protocols.

## 3. Results & Screenshots

<img title="DPC - Window" src="https://github.com/nikhilsathwik2806/Data-Path-Controller/blob/master/Annotation%202020-02-29%20201105.png" alt="DPC-Window" width=720/></img>

<p align="center"><i><b>Figure 3.1 DPC-Window</b></i></p>

The above picture shows the window format of the DPC consisting of the input ports and the output ports. 
It also contains a scroll down combo box consisting of numbers in the range of 01-16 and a submit button.

<img src="https://github.com/nikhilsathwik2806/Data-Path-Controller/blob/master/Annotation%202020-02-29%20201206.png" width=720/></img>

<p align="center"><i><b>Figure 3.2 DPC Dialogoue Box-1</b></i></p>

After the desired output port values are selected and the submit button is clicked the message is displayed as ```Successfully Submitted```.

<img src="https://github.com/nikhilsathwik2806/Data-Path-Controller/blob/master/Annotation%202020-02-29%20201234.png" width=720/></img>

<p align="center"><i><b>Figure 3.3 DPC Dialogue Box-2</b></i></p>

The submitted values for the input port and the respective output port are displayed in the dialog box as 4 bit data streams for 16 switches, where the outputs of each switch are separated by a space.

## Execution
If you want to see it in action, Download the ```/Release``` folder with all the dll files in it and run ```DataPathController.exe```

>**Note**: The GUI for DPC presently works only in the ```light mode``` of the windows. feel free to modify the code and make it work in the dark mode too.

## Requirements
Requires Visual Studio with latest extensions and plugins of Fluent Windows Platform

## Built With
C#, Visual Studio

## Authors

* **Sathwik Vadlamani** - *Initial design work, Logic, debugging, doccumentation* - [nikhilsathwik2806](https://github.com/nikhilsathwik2806)
* **Shriram Ravindranathan** - *logic Debugging ,c# debugging* - [notshriram](https://github.com/notshriram)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* based on the inputs Given by ```N. Askok Kumar Sci/Eng - SE ``` & ```A. Venugopal Sci/Eng - SG GH, RDASG``` at 
 **Real-Time Data Archival Systems Division (RDASG), National Remote Sensing Center (NRSC), Indian Space Reasearch Organization (ISRO),Dept. of Space, Govt. of India.**
