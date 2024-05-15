# Ex-06 Gerber-to-G-Code-Conversion
# Aim
To convert the Gerber File into G-Code using Copper CAM.
# Software required
Copper CAM
# Procedure
1. Open your Gerber file (File → Open → New circuit)</br>
2. Open your Drill file (File → Open → Drill)</br>
3. Match the drill file and engraving file if not matched </br>
4. Right click the pad and set define as pad and then Right click and select edit all identical pads as set the drill size as 0.8mm,1mm.</br>
5. Open your Cutting file (File → Open → Additional Layer and load your cutting file</br>
6. Go to file/Orgin and set x=0,y=0 </br>
7. Go to file/offset and select the option shift manually</br>
8. Select the layer 6 and move the cutting file and set the border</br>
9. Go to parameter/ tool library and check the identifaication and specification</br>
10. Go to parameter/selected tool and check the engraving tool, cutting tool and drill tool</br>
11. Go to machine/ Contours/calculate Contours</br>
12. Go to machine/mill and select engraving you will get the g code,similarly for Drill and cut. </br>
13. Save the G code</br>
# Contours Output






# G Code
### Engraving G Code
```c
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 10/05/2024 at 19:37 )
( Workpiece dimensions: 35.357 x 22.977 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #1 "Basic Engraver" / Diameter 3.17 mm )
T1 M06
M03 S12000
M07
G00 X5.34 Y5.479
G00 Z0
G01 F60 Z-0.2
G01 F600 X5.526 Y5.498
G01 X5.705 Y5.552
G01 X5.87 Y5.64
G01 X6.014 Y5.759
G01 X6.133 Y5.903
G01 X6.221 Y6.068
G01 X6.275 Y6.247
G01 X6.294 Y6.433
G01 X6.275 Y6.619
G01 X6.221 Y6.798
G01 X6.133 Y6.963
G01 X6.014 Y7.107
G01 X5.87 Y7.226
G01 X5.705 Y7.314
G01 X5.526 Y7.368
G01 X5.34 Y7.387
G01 X3.54
G01 X3.354 Y7.368
G01 X3.175 Y7.314
G01 X3.01 Y7.226
G01 X2.866 Y7.107
G01 X2.747 Y6.963
G01 X2.659 Y6.798
G01 X2.605 Y6.619
G01 X2.587 Y6.433
G01 X2.605 Y6.247
G01 X2.659 Y6.068
G01 X2.747 Y5.903
G01 X2.866 Y5.759
G01 X3.01 Y5.64
G01 X3.175 Y5.552
G01 X3.354 Y5.498
G01 X3.54 Y5.479
G01 X5.34
G00 Z2
G00 Y10.559
G00 Z0
G01 F60 Z-0.2
G01 F600 X5.526 Y10.578
G01 X5.705 Y10.632
G01 X5.87 Y10.72
G01 X6.014 Y10.839
G01 X6.133 Y10.983
G01 X6.221 Y11.148
G01 X6.275 Y11.327
G01 X6.294 Y11.513
G01 X6.275 Y11.699
G01 X6.221 Y11.878
G01 X6.133 Y12.043
G01 X6.014 Y12.187
G01 X5.87 Y12.306
G01 X5.705 Y12.394
G01 X5.526 Y12.448
G01 X5.34 Y12.467
G01 X3.54
G01 X3.354 Y12.448
G01 X3.175 Y12.394
G01 X3.01 Y12.306
G01 X2.866 Y12.187
G01 X2.747 Y12.043
G01 X2.659 Y11.878
G01 X2.605 Y11.699
G01 X2.587 Y11.513
G01 X2.605 Y11.327
G01 X2.659 Y11.148
G01 X2.747 Y10.983
G01 X2.866 Y10.839
G01 X3.01 Y10.72
G01 X3.175 Y10.632
G01 X3.354 Y10.578
G01 X3.54 Y10.559
G01 X5.34
G00 Z2
G00 X17.956 Y12.021
G00 Z0
G01 F60 Z-0.2
G01 F600 Y13.545
G01 X17.94 Y13.704
G01 X17.894 Y13.857
G01 X17.818 Y13.998
G01 X17.717 Y14.122
G01 X17.593 Y14.223
G01 X17.452 Y14.299
G01 X17.299 Y14.345
G01 X17.14 Y14.361
G01 X16.981 Y14.345
G01 X16.828 Y14.299
G01 X16.687 Y14.223
G01 X16.563 Y14.122
G01 X16.462 Y13.998
G01 X16.387 Y13.857
G01 X16.34 Y13.704
G01 X16.325 Y13.545
G01 Y12.021
G01 X16.34 Y11.862
G01 X16.387 Y11.709
G01 X16.462 Y11.568
G01 X16.563 Y11.444
G01 X16.687 Y11.343
G01 X16.828 Y11.268
G01 X16.981 Y11.221
G01 X17.14 Y11.205
G01 X17.299 Y11.221
G01 X17.452 Y11.268
G01 X17.593 Y11.343
G01 X17.717 Y11.444
G01 X17.818 Y11.568
G01 X17.894 Y11.709
G01 X17.94 Y11.862
G01 X17.956 Y12.021
G00 Z2
G00 X18.107 Y4.726
G00 Z0
G01 F60 Z-0.2
G01 F600 X18.065
G01 X17.578 Y4.238
G01 Y3.548
G01 X18.065 Y3.06
G01 X18.755
G01 X18.784 Y3.09
G01 X19.466 Y2.408
G01 X19.512 Y2.371
G01 X19.564 Y2.343
G01 X19.621 Y2.325
G01 X19.68 Y2.319
G01 X24.76
G01 X24.819 Y2.325
G01 X24.876 Y2.343
G01 X24.929 Y2.371
G01 X24.975 Y2.408
G01 X26.245 Y3.678
G01 X26.283 Y3.724
G01 X26.311 Y3.777
G01 X26.328 Y3.834
G01 X26.334 Y3.893
G01 Y4.483
G01 X26.726 Y4.875
G01 Y5.429
G01 X27.515 Y6.218
G01 X27.553 Y6.264
G01 X27.581 Y6.317
G01 X27.598 Y6.374
G01 X27.604 Y6.433
G01 Y9.289
G01 X28.2
G01 X28.386 Y9.308
G01 X28.565 Y9.362
G01 X28.73 Y9.45
G01 X28.874 Y9.569
G01 X28.993 Y9.713
G01 X29.081 Y9.878
G01 X29.135 Y10.057
G01 X29.154 Y10.243
G01 X29.135 Y10.429
G01 X29.081 Y10.608
G01 X28.993 Y10.773
G01 X28.874 Y10.917
G01 X28.73 Y11.036
G01 X28.565 Y11.124
G01 X28.386 Y11.178
G01 X28.2 Y11.197
G01 X26.4
G01 X26.214 Y11.178
G01 X26.035 Y11.124
G01 X25.87 Y11.036
G01 X25.726 Y10.917
G01 X25.607 Y10.773
G01 X25.519 Y10.608
G01 X25.501 Y10.547
G01 X21.076
G01 X20.214 Y11.409
G01 X20.257 Y11.444
G01 X20.358 Y11.568
G01 X20.434 Y11.709
G01 X20.48 Y11.862
G01 X20.496 Y12.021
G01 Y13.545
G01 X20.48 Y13.704
G01 X20.434 Y13.857
G01 X20.358 Y13.998
G01 X20.257 Y14.122
G01 X20.133 Y14.223
G01 X19.992 Y14.299
G01 X19.839 Y14.345
G01 X19.68 Y14.361
G01 X19.521 Y14.345
G01 X19.368 Y14.299
G01 X19.227 Y14.223
G01 X19.103 Y14.122
G01 X19.002 Y13.998
G01 X18.927 Y13.857
G01 X18.88 Y13.704
G01 X18.865 Y13.545
G01 Y12.021
G01 X18.88 Y11.862
G01 X18.927 Y11.709
G01 X19.002 Y11.568
G01 X19.103 Y11.444
G01 X19.227 Y11.343
G01 X19.368 Y11.268
G01 X19.521 Y11.221
G01 X19.545 Y11.219
G01 X20.736 Y10.028
G01 X20.782 Y9.991
G01 X20.834 Y9.963
G01 X20.891 Y9.945
G01 X20.95 Y9.939
G01 X25.501
G01 X25.519 Y9.878
G01 X25.607 Y9.713
G01 X25.726 Y9.569
G01 X25.87 Y9.45
G01 X26.035 Y9.362
G01 X26.214 Y9.308
G01 X26.4 Y9.289
G01 X26.997
G01 Y6.559
G01 X26.297 Y5.859
G01 X25.742
G01 X25.334 Y5.451
G01 Y4.875
G01 X25.727 Y4.483
G01 Y4.019
G01 X24.634 Y2.927
G01 X19.806
G01 X19.214 Y3.519
G01 X19.243 Y3.548
G01 Y4.238
G01 X18.755 Y4.726
G01 X18.714
G01 Y7.703
G01 X18.708 Y7.762
G01 X18.691 Y7.819
G01 X18.663 Y7.872
G01 X18.625 Y7.918
G01 X17.355 Y9.188
G01 X17.309 Y9.225
G01 X17.256 Y9.253
G01 X17.199 Y9.271
G01 X17.14 Y9.277
G01 X6.24
G01 X6.221 Y9.338
G01 X6.133 Y9.503
G01 X6.014 Y9.647
G01 X5.87 Y9.766
G01 X5.705 Y9.854
G01 X5.526 Y9.908
G01 X5.34 Y9.927
G01 X3.54
G01 X3.354 Y9.908
G01 X3.175 Y9.854
G01 X3.01 Y9.766
G01 X2.866 Y9.647
G01 X2.747 Y9.503
G01 X2.659 Y9.338
G01 X2.605 Y9.159
G01 X2.587 Y8.973
G01 X2.605 Y8.787
G01 X2.659 Y8.608
G01 X2.747 Y8.443
G01 X2.866 Y8.299
G01 X3.01 Y8.18
G01 X3.175 Y8.092
G01 X3.354 Y8.038
G01 X3.54 Y8.019
G01 X5.34
G01 X5.526 Y8.038
G01 X5.705 Y8.092
G01 X5.87 Y8.18
G01 X6.014 Y8.299
G01 X6.133 Y8.443
G01 X6.221 Y8.608
G01 X6.24 Y8.669
G01 X17.014
G01 X18.107 Y7.577
G01 Y4.726
G00 Z2
G00 X16.724 Y3.893
G00 Z0
G01 F60 Z-0.2
G01 F600 X16.707 Y3.726
G01 X16.659 Y3.566
G01 X16.58 Y3.419
G01 X16.474 Y3.289
G01 X16.344 Y3.183
G01 X16.197 Y3.104
G01 X16.037 Y3.056
G01 X15.87 Y3.039
G01 X15.704 Y3.056
G01 X15.543 Y3.104
G01 X15.396 Y3.183
G01 X15.267 Y3.289
G01 X15.16 Y3.419
G01 X15.081 Y3.566
G01 X15.033 Y3.726
G01 X15.016 Y3.893
G01 X15.033 Y4.06
G01 X15.081 Y4.22
G01 X15.16 Y4.367
G01 X15.267 Y4.497
G01 X15.396 Y4.603
G01 X15.543 Y4.682
G01 X15.704 Y4.73
G01 X15.87 Y4.747
G01 X16.037 Y4.73
G01 X16.197 Y4.682
G01 X16.344 Y4.603
G01 X16.474 Y4.497
G01 X16.58 Y4.367
G01 X16.659 Y4.22
G01 X16.707 Y4.06
G01 X16.724 Y3.893
G00 Z2
G00 X24.186 Y5.451
G00 Z0
G01 F60 Z-0.2
G01 F600 X23.778 Y5.859
G01 X23.202
G01 X22.794 Y5.451
G01 Y4.875
G01 X23.202 Y4.467
G01 X23.778
G01 X24.186 Y4.875
G01 Y5.451
G00 Z2
G00 X25.501 Y12.479
G00 Z0
G01 F60 Z-0.2
G01 F600 X25.519 Y12.418
G01 X25.607 Y12.253
G01 X25.726 Y12.109
G01 X25.87 Y11.99
G01 X26.035 Y11.902
G01 X26.214 Y11.848
G01 X26.4 Y11.829
G01 X28.2
G01 X28.386 Y11.848
G01 X28.565 Y11.902
G01 X28.73 Y11.99
G01 X28.874 Y12.109
G01 X28.993 Y12.253
G01 X29.081 Y12.418
G01 X29.135 Y12.597
G01 X29.154 Y12.783
G01 X29.135 Y12.969
G01 X29.081 Y13.148
G01 X28.993 Y13.313
G01 X28.874 Y13.457
G01 X28.73 Y13.576
G01 X28.565 Y13.664
G01 X28.386 Y13.718
G01 X28.2 Y13.737
G01 X26.4
G01 X26.214 Y13.718
G01 X26.035 Y13.664
G01 X25.87 Y13.576
G01 X25.726 Y13.457
G01 X25.607 Y13.313
G01 X25.519 Y13.148
G01 X25.501 Y13.087
G01 X23.036
G01 Y13.545
G01 X23.02 Y13.704
G01 X22.974 Y13.857
G01 X22.898 Y13.998
G01 X22.797 Y14.122
G01 X22.673 Y14.223
G01 X22.532 Y14.299
G01 X22.379 Y14.345
G01 X22.22 Y14.361
G01 X22.061 Y14.345
G01 X21.908 Y14.299
G01 X21.767 Y14.223
G01 X21.643 Y14.122
G01 X21.542 Y13.998
G01 X21.467 Y13.857
G01 X21.42 Y13.704
G01 X21.405 Y13.545
G01 Y12.021
G01 X21.42 Y11.862
G01 X21.467 Y11.709
G01 X21.542 Y11.568
G01 X21.643 Y11.444
G01 X21.767 Y11.343
G01 X21.908 Y11.268
G01 X22.061 Y11.221
G01 X22.22 Y11.205
G01 X22.379 Y11.221
G01 X22.532 Y11.268
G01 X22.673 Y11.343
G01 X22.797 Y11.444
G01 X22.898 Y11.568
G01 X22.974 Y11.709
G01 X23.02 Y11.862
G01 X23.036 Y12.021
G01 Y12.479
G01 X25.501
G00 Z2
M09
M05
M02
%
```




### Drill G Code

```c
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 10/05/2024 at 19:38 )
( Workpiece dimensions: 35.357 x 22.977 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #4 "Basic Drill" / Diameter 1 mm )
T4 M06
M03 S12000
M07
G00 X4.44 Y11.513
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y8.973
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y6.433
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X15.87 Y3.893
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X18.41
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X23.49 Y5.163
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X26.03
G00 Z0
G01 F60 Z-1
G00 Z2
G00 X27.3 Y10.243
G00 Z0
G01 F60 Z-1
G00 Z2
G00 Y12.783
G00 Z0
G01 F60 Z-1
G00 Z2
M09
M05
M02
%


```




### Cutting G Code

```c
%
( CopperCAM - 29/07/2019 / ISO-Mill Output )
( C:\COPPERCAM\CopperCAM.iso created 10/05/2024 at 19:36 )
( Workpiece dimensions: 35.357 x 22.977 x 1 mm )
G21 G40 G54
G80 G90 G94
( Tool #2 "Basic Cutter" / Diameter 3 mm )
T2 M06
M03 S12000
M07
G00 X0.432 Y0.132
G00 Z0
G01 F60 Z-2
G01 F300 X33.582
G01 Y20.902
G01 X0.432
G01 Y0.132
G00 Z2
M09
M05
M02
%

```




# Result

Thus the Gerber File into G-Code using Copper CAM.
