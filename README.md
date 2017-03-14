# video_to_sequence
* TensorFlow Implementation of [Sequence to Sequence – Video to Text](http://arxiv.org/abs/1505.00487)

### Usage
* First you need to download "Microsoft Video Description Corpus"
 * Set "video_data_path" in download_videos.py accordingly.
 * Download Youtube videos by running "download_videos.py" 
* Secondly, you need to preprocess downloaded videos
 * Set paths in cnn_utils.py and preprocess.py 
 * Sample & extract features by running "preprocessing.py"
* Train: train() in model.py
 * You might need to change the paths in "Global Parameters" area according to your environment
* Test: test() in model.py

![alt tag](https://github.com/jazzsaxmafia/video_to_sequence/blob/master/plane.jpg)

### Download links

the corpus can be downloaded here:
[*video_corpus.csv.zip*](https://github.com/jazzsaxmafia/video_to_sequence/files/387979/video_corpus.csv.zip)

Some of the Microsoft Video Description Corpus clips are not available on youtube anymore but here's the full archive:
https://www.cs.utexas.edu/users/ml/clamp/videoDescription/YouTubeClips.tar (1.7GB)
from https://www.cs.utexas.edu/users/ml/clamp/videoDescription/#data

name | caffemodel | caffemodel_url | license |sha1 | caffe_commit
---|---|---|---|---|---|
BVLC CaffeNet Model |  bvlc_reference_caffenet.caffemodel | http://dl.caffe.berkeleyvision.org/bvlc_reference_caffenet.caffemodel | unrestricted | 4c8d77deb20ea792f84eb5e6d0a11ca0a8660a46 | 709dc15af4a06bebda027c1eb2b3f3e3375d5077




### License
* BSD License
