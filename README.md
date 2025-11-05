# Clarke and Park Transformation Simulation
A MATLAB/Simulink implementation of Clarke and Park transformations on three-phase balanced sinusoidal waveforms.
## Simulation Configuration
**Solver Settings**

Solver Type: *Variable-step*,<br>
Solver: *Automatic solver selection*,<br>
Max Step Size: *1e-4* (manually configured),<br>
Relative Tolerance: *1e-3*

*Note: The maximum step size has been set to 1e-4 instead of the default auto setting. When using automatic step sizing, the sinusoidal waveforms appear jagged and non-smooth due to insufficient sampling points.*
