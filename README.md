# Style-Transfer
Use Neural Networks to Paint Images in Famous Styles

## Requirements:
* Python 3.6.2 (https://www.python.org/downloads/release/python-362/)
* Numpy (https://pypi.org/project/numpy/)
* Tensorflow (https://pypi.org/project/tensorflow/)
* Keras (https://pypi.org/project/Keras/)

## Installation:
* Download and extract entire repositry
* Open cmd and run the following to install required modules
```
pip install -r requirements.txt
```
* Once requirements are installed download a painting of any style you need, eg- Scream (Already provided) and the original image to be painted (Golden Gate Bridge).

## Running
```
python neural_style.py --content <content file> --styles <style file> --output <output file>
```
Run `python neural_style.py --help` to see a list of all options.
