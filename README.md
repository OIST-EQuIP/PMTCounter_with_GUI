README
===========
Description
-----------
The project implements a PMT counter by using an Opal Kelly XEM7305 FPGA board.

File:						Description

PMTCounter_GUI.py:			python program of the GUI for the counter

XEM7305_photon_counter.py:	python module of the counter

photon_counter_gui.bit:		compiled firmware for the counter

realtime_monitor_*.py:		python program for testing the proto-type

photon_counter_sample.py:	python program for testing the proto-type

photon_counter.bit:			compiled firmware for testing the proto-type

ok*:							Opal Kelly API files for python3.7

firmware/*:					firmware source codes


Requirments
-----------
Python3.7 or later

PyQt5

pyqtgraph


Usage
-----
python PMTCounter_GUI.py
