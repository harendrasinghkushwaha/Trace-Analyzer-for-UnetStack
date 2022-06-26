# Trace-Analyzer-for-UnetStack
The UnetStack trace analyzer is written in Python and the Tkinter package has been used to create the GUI of the tool. The Trace Analyzer tool is specifically designed for trace analysis for the underwater network simulator UnetStack.  When you run a simulation in UnetStack, it generates two files as a result of the simulation: log/log-0.txt and trace.json. Manually analyzing these trace files to obtain simulation performance metrics is a time-consuming and lengthy process. The trace Analyzer tool takes the trace.json file as an input and then extracts useful data to calculate performance parameters by processing each and every event logged in the trace.json file.   After extracting the necessary data, the Trace Analyzer tool presents the network performance metrics such as throughput, average end-to-end delay, and packet delivery ratio in the form of graphs.
# How to Use the tool
The UnetStack Trace Analyer tool have been developed on the Ubuntu 20.04. The tool have been written in Python programming langage and the Python’s Tkinter package have been used to create the GUI.
## Prerequisites to run the tool
1. Python should be install in your system
2. Tkinter should be install in your system <br/>
Download the code and open folder in the terminal. In folder there are three files - start.py, trace.py, check_sources.py. To start the tool run the start.py file. you will get GUI windo of the tool as shown in the below picture.

