# MyTinyML

## Introduction

This is a TinyML project which is based on TensorFlow Lite and Arduino Nano 33 Sense board.
Under the instruction of 《TinyML》 by Pete Warden and Daniel Situnayake.


## Theme

Wake word detection: Training a model

## How to run?

(1) Download Arduino IDE and this resposity.

(2) Open Arduino IDE and go to "File->Preference", then edit Sketchbook location to
the path of the document of "WakeWorld" in this resposity.

(3) Open the example, click "File->Examples->Arduino_TensorFlowLite->micro_speech".

(4) Connect board with computer, then select board and corresponding port. Click ![image](https://user-images.githubusercontent.com/34792512/143731068-382e2805-8875-4e20-a61e-14edf45a4f7f.png)
to upload software into board.

(5) Test: if the light turns into yellow when said "yes" and turns into red when said "no", then it
means we install the software correctly.

"YES"
![image](https://user-images.githubusercontent.com/34792512/143731133-04491546-c11c-425a-84d6-1e56455a35c0.png)

"NO"
![image](https://user-images.githubusercontent.com/34792512/143731141-d571fbf4-f7b5-41a8-8ac2-f342d7092708.png)

