# CursorSpectrum

A software which enables interactive interpretation of mapping Raman spectra
## Requirements
```
conda create -n CS python=3.8
pip install opencv-python==4.5.3.56
pip install numpy==1.21.2
pip install pandas==1.3.3
pip install seaborn==0.11.2
pip install matplotlib==3.4.3
pip install soundfile==0.10.3.post1
conda install pyaudio==0.2.11
```
## How to use
1. Run main.py file
2. Load Matrix data (txt file )
3. Load Raman shift data (txt file )
4. Set XY grid
5. Load image data (resize beforehand)
6. Confirm mapping direction if necessary
7. Initialize (raise error if any data or grid mismatch)
8. Search grid with B1-Motion. Spectrum is automatically updated
9. Save current spectrum if nesessary by the button

</br>

https://github.com/syunnosuke/CursorSpectrum/assets/48796518/ab661fe9-c62e-4508-b154-cd8bdd08fe34

</br>
---
</br>
Copyright (c) 2023-2024 SuwaSyun. All Rights Reserved.
