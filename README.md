# Style-Transfer
Use Neural Networks to Paint Images in Famous Styles

For more info: [Research Paper][paper]

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
* Download [Pre-trained VGG network][net] and put it in the main file, or specify its location using the `--network` option.

* Once requirements are installed download a painting of any style you need, eg- Scream (Already provided) and the original image to be painted (Golden Gate Bridge).

## Running
```
python style_transfer.py --content <content file> --styles <style file> --output <output file>
```
Run `python style_transfer.py --help` to see a list of all options.

Use `--checkpoint-output` and `--checkpoint-iterations` to change checkpoint save location and iteration (default: 'output/output_{:05}.jpg', 10).

Use `--iterations` to change the number of iterations (default: 500).

## Examples:
<p align="center">
<img src="https://github.com/crypto-code/Style-Transfer/blob/master/assets/gate_final.jpg" width="600" align="middle" />   </p>
<p align="center">With Golden Gate Bridge and the Scream</p>
  <p align="center">
<img src="https://github.com/crypto-code/Style-Transfer/blob/master/assets/output_final.jpg" width="400" align="middle" />  </p>
<p align="center">With Emma Watson and Mona Lisa</p>

# G00D LUCK

For doubts email me at:
atinsaki@gmail.com

[net]: http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat
[paper]: http://arxiv.org/pdf/1508.06576v2.pdf
