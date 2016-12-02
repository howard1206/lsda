Large Scale Detection through Adaptation
========

Download pre-trained 7.5K model:
-------

* Includes all leaf synsets + 200 detection categories
* <a href="https://www.cs.stanford.edu/~jhoffman/caffe_nets/rcnn_model7200.mat">Pre-trained Detection Model</a> 
* <a href="https://www.cs.stanford.edu/~jhoffman/caffe_nets/finetune_ilsvrc13_val1+train1k_iter_50000">Caffe Weights for 200 strong detectors</a> 
* <a href="https://www.cs.stanford.edu/~jhoffman/caffe_nets/imagenet7k_det_ilsvrc_2013_fc8_iter_74040">Caffe Weights for 7K weak detectors </a>

To try out an example, run:
    
    startup;
    detect10k_demo(rcnn_model, rcnn_feat, 'ex_img.jpg');
