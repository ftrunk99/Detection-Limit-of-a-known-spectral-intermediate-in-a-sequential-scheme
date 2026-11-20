# Detection-Limit-of-a-known-spectral-intermediate-in-a-sequential-scheme
Question: an electron-transfer step shows no resolvable rise lag in transient absorption data. How large could a sequential intermediate between two states be and still go unnoticed? Code was generated using Claude.ai (Fable 5.2)

Requirements: MATLAB R2019a or newer, no toolboxes.
TA-Data must be dispersion corrected and provided in Matrix format as xlsx file: X-axis = timescale, Y-axis = wavelength, Z = dOD 
Spectral reference data format .xlsx: 1. Column: Wavelength, then the intermediates in extinctioncoefficents. The user has to specify which intermediate spectra are used for injection by providing the correct column of this file. 
