# Image to ASCII
Converts an image file into ASCII characters.

First, create a virtual environment in the image-to-ascii directory:  
```
python -m venv env
env\Scripts\activate
```

Install requirements:  
```
pip install -r requirements.txt
```

Make sure to move an image file to the `picture` directory, then run the python script with `python main.py`  

Once the program has started, two image files will open: one of the original image, and one converted to grayscale and pixelated.        
The ASCII art will then appear in a separate window.
