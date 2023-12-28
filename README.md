# Cartoonization

We implemented 2 different pipelines. One using our own implementation of Viola Jones face detection algorithm, the other using built-in HaarCascade. 
Viola Jones was faster, but Haar Cascade showed better results.
Furthermore, our project consists of two major pipelines. One which is responsible for edge detection, while the other for cartoonization. Lastly their outputs are added together to produce the final result. This is done using both approaches, and quantizing using 3 different approaches according to use case. 

![Alt text](image.png)

![Alt text](image-1.png)

![Alt text](image-3.png)

## Fancy Responsive GUI
![Alt text](image-2.png)

## How to run
### Requirements
install these packages using pip


cv2
os
sys
tkinter
PIL
collections
scipy
functools
numpy
progressbar
multiprocessing
itertools
pickle
```bash
pip install opencv-python
pip install os-sys
pip install tkinter
pip install Pillow
pip install collections
pip install scipy
pip install functools
pip install numpy
pip install progressbar
pip install multiprocessing
pip install itertools
```
To run the project, simply open the cartoon.ipynb, and run all cells. This uses the HaarCascade algorithm

For the Viola Jones algorithm, open the ViolaJones.ipynb, and run all cells. This should be done after either training or loading the trained model.


 
