# Aeropendulum
**Aeropendulum-Based Didactic Platform**

This is the archive repository for the technical paper entitled **"An Aeropendulum-Based Didactic Platform for the Learning of Control Engineering"**, authored by **Rafael C. Neto**, **Felipe L. A. Trindade**, **Beatriz R. A. Marques**, **Gustavo M. S. Azevedo**, **Eduardo J. Barbosa** and **Eduardo A. O. Barbosa**.

**Abstract:** Due to the complexity of the subjects covered in control engineering courses, many students have difficulty in resolving practical control problems. In order to solve this problem, didactic plants can be used as teaching tools to allow students to practice the design of controllers through the investigation of real physical systems. In this sense, this paper proposes an aeropendulum-based didactic platform to be used in control engineering courses. This paper cover all fundamental concepts about aeropendulums, simulation files built in Matlab/Simulink and Scilab/Xcos and some suggested practices that can be done using the proposed platform. The experimental results show that the proposed didactic platform is fully functional.

**Keywords:** Control Engineering, Didactic Platform, Aeropendulum, Non-Linear Plant.

# Repository organization

**Electronical Structure:** This folder contains all design and manufacturing files of the PCB that was designed to work as a signal conditioning circuit and an actuation circuit for the proposed didactic platform. Manufacturing files are GERBER files.

**Mechanical Structure:** This folder contains all design and manufacturing files of the mechanical structure of the aeropendulum. All parts of the mechanical structure are explained in the original paper. Manufacturing files are GCODE files generated considering that all mechanical parts are fabricated using a 4mm thick acrylic sheet and using a 3-axis CNC cutting machine with a 2mm ball nose end mill.

**Simulation Files:** This folder contains the 3D-model of the aeropendulum and the Matlab/Simulink files. The values used for the parameters of the aeropendulum proposed in the paper are defined directly in the _Callbacks_ of the Simulink file (.slx). The Matlab version used to build the model was R2018b.
