.. _data:

****
Data
****

Overview
========

Data Description
----------------

+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| Level    | Product                               | Description                                                                           |      
+==========+=======================================+=======================================================================================+
| 1        | H+ Counts                             | 32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed) |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 1        | He++ Counts                           | 32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed) |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 1        | O+ Counts                             | 32 Energies x 8 Deflections (256 HV step) x 16 Anodes every 0.87s (may be compressed) |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 2        | H+ Flux                               | Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle,     |
|          |                                       | and azimuthal angle. Preliminary calibration applied.                                 |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 2        | He++ Flux                             | Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle,     |
|          |                                       | and azimuthal angle. Preliminary calibration applied.                                 |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 2        | O+ Flux                               | Differential Energy Flux [cm-2 sr-1 s-1 eV/eV] in units of eV/Q, elevation angle,     |
|          |                                       | and azimuthal angle. Preliminary calibration applied.                                 |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 3        | H+ Moments                            | H+ Density, Velocity, Temperature                                                     |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 3        | He++ Moments                          | H++ Density, Velocity, Temperature                                                    |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 3        | O+ Moments                            | O+ Density, Velocity, Temperature                                                     |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| 4        | TBD                                   |                                                                                       |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | H+ Flux (Unvalidated)                 | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | He++ Flux (Unvalidated)               | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | O+ Flux (Unvalidated)                 | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | H+ Moments (Unvalidated)              | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | He++ Moments (Unvalidated)            | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+
| QL       | O+ Moments (Unvalidated)              | Same as Level 2, but preliminary calibration applied                                  |
+----------+---------------------------------------+---------------------------------------------------------------------------------------+

Getting Data
============



Reading Data
============



Calibrating Data
================
Data products below level 2 generally require calibration to be transformed into scientificically useable units.
This section describes how to calibrate data files from lower to higher levels.