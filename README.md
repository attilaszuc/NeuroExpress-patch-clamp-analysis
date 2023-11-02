# NeuroExpress
NeuroExpress patch clamp data analysis software version 23.9.01.
NeuroExpress is a fast Windows 10 compatible analysis program designed for the analysis of the following type of data:

1) Voltage responses of neurons measured in whole-cell configuration stimulated with current steps (intrinsic cellular properties, intrinsic excitability,
   membrane resistance, membrane capacitance, rheobase, spike amplitude, voltage sag, etc.)
2) Spontaneous or miniature postsynaptic currents (mini analysis). Several mini parameters are calculated semi-automatically including event intervals,
   event amplitudes, charge, IEI, histograms, decay time constants, etc.
3) Spike trains, spontaneous action potential trains recorded in whole-cell mode or extracellularly. (Interspike intervals, Poincare-maps, spike density functions,
   Fourier-amplitude and spectrogram, symbolic analysis, etc.)

The executable can be downloaded from this folder together with the attached 3 data files (1 ASCII and 2 ABFs) to test the various analysis modules of the program.
The program is being optimized for Windows 10 systems. It has a redesigned user interface, several automatic features and high performance through multi-threading. 
New features: Improved Savitzky-Golay smoothing algorithm for noisy mini traces. The program loads and displays ABF files of mEPSC recordings much faster than prior versions. 
ROI - region of interest. The user can define up to 4 sections of the trace where analysis is performed separately. The program now calculates decay time constants of the 
mini events. The exponential fit is performed automatically and it takes usually less than 1 second to obtain time constants of hundreds of mEPSCs. The zoom feature of the 
program allows to select areas of interest and calculate IEI, amplitude etc. data for the selection only. 
All the calculated parameters can be exported into an Excel worksheet by a simple button click. 

Users interested in testing the analysis software are encouraged to download the 60-day trial version of the program (NeuroExpress version 23.9.01 is also available 
on ResearchGate). Please contact me if you have any question regarding the use of the program or to report a bug. A brief documentation file (NEx_Instructions.pdf) is available.
Feedback is appreciated, please report issues or bugs.

**Tutorials** are also available on Youtube accessible from the Help menu of the program.
Screenshots of the program performing various types of analysis are below.

Calculating cellular properties from data obtained via current step stimulation:
![NEx_1](https://github.com/attilaszuc/NeuroExpress/assets/149586298/39357bd8-302a-4655-9049-cef534b32e4f)
![230504_c09_01_MSc2_IV](https://github.com/attilaszuc/NeuroExpress-patch-clamp-analysis/assets/149586298/7f6b945b-2b76-4320-8c5b-5c750ee3133f)
![230504_c09_01_MSc2_IV](https://github.com/attilaszuc/NeuroExpress-patch-clamp-analysis/assets/149586298/29a8d4b4-5914-4d7b-8205-3d14c53366fe)

Mini analysis, event detection and statistics:
![NEx_2](https://github.com/attilaszuc/NeuroExpress/assets/149586298/84de489a-b6ae-4350-941a-260e7ff65773)
![210907_c01_01_S3_2ch_VCl_P6](https://github.com/attilaszuc/NeuroExpress-patch-clamp-analysis/assets/149586298/8c2b3aaf-3514-4e4b-8dca-b7e5bbcc7291)

Analysis of spike trains acquired simultaneously from 5 bursting neurons.
![NEx_3](https://github.com/attilaszuc/NeuroExpress/assets/149586298/723d63f8-f3bd-4c1c-8182-ba8cb1305b74)
