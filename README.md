# Trace-Analyzer-for-UnetStack
The UnetStack trace analyzer is written in Python and the Tkinter package has been used to create the GUI of the tool. The Trace Analyzer tool is specifically designed for trace analysis for the underwater network simulator UnetStack.  When you run a simulation in UnetStack, it generates two files as a result of the simulation: log/log-0.txt and trace.json. Manually analyzing these trace files to obtain simulation performance metrics is a time-consuming and lengthy process. The trace Analyzer tool takes the trace.json file as an input and then extracts useful data to calculate performance parameters by processing each and every event logged in the trace.json file.   After extracting the necessary data, the Trace Analyzer tool presents the network performance metrics such as throughput, average end-to-end delay, and packet delivery ratio in the form of graphs.
