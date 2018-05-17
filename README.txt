This is the Alpha build for the 2 player pong EEG software suite being built by IEEE Chico State EECE students. 
===========================================================================================================
Abstract: 

The goal of this project is to have two users with openBCI headsets 
transmitting wireless biopotential data via bluetooth to a network streaming layer. 
The networking streaming layer then takes that data into BCIlab where it is then processed 
in EEGlab with plugins to identify eye movements. Once the data is procesed it will be used 
to control an individual pong paddle for each player in real time within a modified MATLAB pong game.
===========================================================================================================
Contents:

Inside the project are various folders containing different software.

BCILAB-devel is the application to be run in MATLAB for data accquisition.

Mark IV EEG Headset STL Files is the folder containing all the CAD files for 3D printing.

OpenBCI Cyton Firmware folder contains the raw firmware data needed to be flashed to the openBCI
Cyton board.

eeglab14_1_1_b is the latest stable release of the EEGlab software toolkit to be run in MATLAB.

pong_matlab is the folder containing the pong game to run in MATLAB built by David Buckingham
with modifications.

===========================================================================================================
NOTICE:

This project will be continously udpated and will have two different
versions. One version will be a stable release and the other will be
a developer version.
===========================================================================================================
MIT License

Copyright (c) 2018 Robert Goldansky

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
