# Variable-Width-Division-Scripts
Scripts to create variable width divider in using multiple division algorithms. Dividers are in Verilog, and designed for FPGA

Included files are:
- pythonProject.zip which has the entire python toolflow
- total_results.csv which has the output of my testing included on my thesis

Not included is the Trireme processor and accompanying batch scripts which is necessary to run the python project. The next section has a download link to obtain that project.

## Trireme
The Trireme soft processor is available at https://drive.google.com/file/d/1xA7PwfwYtpmFyHWQq3qDps4Oj8-3vS6A/view?usp=sharing

This zip file includes:
- All verilog files used in the processor design
- All quartus projects synthesized in the python project
- All batch scripts used in the python project
- The location for all of the outputs from the python project

## Important note for use:
There are many locations that have a fully qualified path that need to be changed to match your paths.
Files that include a fully qualified path include:
- simulation.bat
- synthesis.bat
- synthesis2.bat
- Parser.py
- VMH.py
- VerilogSynthesis.py
- DivWrapper.py
- Divider.py
- ModelSim.py
