This is the Alpha build for the 2 player pong EEG software suite being built by IEEE Chico State EECE students. 

Abstract: The goal of this project is to have two users with openBCI headsets 
transmitting wireless biopotential data via bluetooth to a network streaming layer. 
The networking streaming layer then takes that data into BCIlab where it is then processed 
in EEGlab with plugins to identify eye movements. Once the data is procesed it will be used 
to control an individual pong paddle for each player in real time within a modified MATLAB pong game.

Contents:

Inside the project are various folders containing different software.

BCILAB-devel is the application to be run in MATLAB for data accquisition.

Mark IV EEG Headset STL Files is the folder containing all the CAD files for 3D printing.

OpenBCI Cyton Firmware folder contains the raw firmware data needed to be flashed to the openBCI
Cyton board.

eeglab14_1_1_b is the latest stable release of the EEGlab software toolkit to be run in MATLAB.

pong_matlab is the folder containing the pong game to run in MATLAB built by David Buckingham
with modifications.



Process: We are achieving this with 2 openBCI headsets built from scratch
with the help of OSHpark/Digi-Key for PCB manufacturing and 
components.

Included in this EEG software suite is UCSD's EEGlab software
and the developer version of BCIlab which we are using for EEG data processing.

We are also using a MATLAB pong game created by David Buckingham
with some modifications to implement EEG control with eye movement.

This project will be continously udpated and will have two different
versions. One version will be a stable release and the other will be
a developer version.
