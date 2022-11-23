# Repository organization

**Electronical Structure:** This folder contains all design and manufacturing files of the PCB that was designed to work as a signal conditioning circuit and an actuation circuit for the proposed didactic platform. Manufacturing files are GERBER files.

**Mechanical Structure:** This folder contains all design and manufacturing files of the mechanical structure of the aeropendulum. All parts of the mechanical structure are explained in the original paper. Manufacturing files are GCODE files generated considering that all mechanical parts are fabricated using a 4mm thick acrylic sheet and using a 3-axis CNC cutting machine with a 2mm ball nose end mill.

**Simulation Files:** This folder contains two folders. The content of these folders are breafly described below.

In the first folder, entitled "Matlab", a 3D-model of the aeropendulum and the Matlab/Simulink files can be founded. The values used for the parameters of the aeropendulum proposed in the paper are defined directly in the _Callbacks_ of the Simulink file (.slx). The Matlab version used to build the model was R2018b.

In the second folder, entitled "Scilab", a Scilab/Xcos file can be founded. The values used for the parameters of the aeropendulum proposed in the paper are defined directly in the Simulink file (.zcos) and in its Context (Simulation Menu >> Set Context) . The Scilab version used to build the model was the Scilab 6.1.1.
