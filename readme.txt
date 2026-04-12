------------------------------------------------
DATASET DESCRIPTION:
------------------------------------------------
Source code: https://github.com/frangam/artdet

- model.h5 -> the machine learning trained model for damage detection 

- We collected two types of "damages".

LPL: Lacune from the loss of the Painting Layer. “Being understood as a deterioration that causes a discontinuity across a surface” [25]. In our study case, there will be a loss where we can still see the support panel. 


Stucco: it is a mixture generally made with animal glue and calcium sulfate, which is used to fill lacunae caused by missing paint and to level these gaps with the paint surface, and then, the chromatic reintegration can be carried out on them 

Statistics:
- LPL: 8 images and 338 polygons
- Stucco: 12 images and 2571 polygons
* Total: 20 images and 2909 polygons

------------------------------------------------
LPL:
------------------------------------------------

- train: 6 images in JPG:
Pintura_0.3
Pintura_0.6
Pintura_0.12
Pintura_0.15
Pintura_0.18
Pintura_0.19
-*-*-*-*-*-*-
- And the corresponding JSON (lpl_train.json) with metadata (usefull for Machine Learning purposes).

- This JSON contains a total of 173 polygons labelled with tag "1"
-*-*-*-*-*-*-

- test: 2 images in JGP:
Pintura_0.10
Pintura_0.16
-*-*-*-*-*-*-
- And the corresponding JSON (lpl_test.json) with metadata (usefull for Machine Learning purposes).

- This JSON contains a total of 165 polygons labelled with tag "1"
-*-*-*-*-*-*-



------------------------------------------------
stucco:
------------------------------------------------

- train: 6 images in JPG:
Pintura_0.2
Pintura_0.4
Pintura_0.5
Pintura_0.7
Pintura_0.9
Pintura_0.13
Pintura_0.14
Pintura_0.17

-*-*-*-*-*-*-
- And the corresponding JSON (stucco_train.json) with metadata (usefull for Machine Learning purposes).

- This JSON contains a total of 1826 polygons labelled with tag "0"
-*-*-*-*-*-*-


- test: 2 images in JGP:
Pintura_0.1
Pintura_0.8
Pintura_0.11
Pintura_0.20

-*-*-*-*-*-*-
- And the corresponding JSON (stucco_test.json) with metadata (usefull for Machine Learning purposes).

- This JSON contains a total of 745 polygons labelled with tag "0"
-*-*-*-*-*-*-