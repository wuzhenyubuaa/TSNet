# A Deeper Look at Salient Object Detection:Bi-stream Network with a Small Training Dataset

## abstract
In this paper, we attempt to reveal the nuance in the training strategy of salient object detection, including the choice of training datasets and the amount of training dataset that the model requires. Furthermore, we also expose the ground-truth bias of existing salient object detection benchmarks and their detrimental effect on performance scores. Based on our discoveries, we proposed a new two-stream framework that was trained on a small training dataset.  To effectively integrate features of different networks, we introduced a novel gate control mechanism for the fusion of two-stream networks that achieves consistent improvements over baseline fusion approaches. To preserves clear object boundaries, we also proposed a novel multi-layer attention module that utilizes high-level saliency activation maps to guide extract details information from low-level feature maps. Extensive experiment results demonstrate that our proposed model can more accurately highlight the salient objects with a small training dataset, and substantially improve the performance scores compared to the existing state-of-the-art saliency detection models.

## Network architecture

![fig1](./img/pipeline.png)


##Requirements
- Python 3.5
-  OpenCV
- PyTorch 0.4

### Visual comparison with previous start-of-the-arts

![fig1](./img/sal_maps.png)

## Usage
Clone, and cd into the repo directory. 


	
	git clone git@github.com:Diamond101010/TSNet.git
	
Before you start, you also need our pretrained model.
 Then run
 
	 cd examles
	 python demo.py

## Download

We provide the results online datasets including  [DUT-OMRON](https://drive.google.com/open?id=1hq6w_LhvMblyYdLFFskLtR77wm4NDFFm), [DUTS-TE](https://drive.google.com/open?id=1LYsFtnCOGiCSL4nyyD9UWw1T0gBo-34F), [ECSSD](https://drive.google.com/open?id=1QHkds8ZMAB_YdJZ8WaOb-mFQnHDa55Un), [HKU-IS](https://drive.google.com/open?id=1ApPVWLRDJDsT0iM54jZyevkErqcVPJSy), [PASCAL-S](https://drive.google.com/open?id=1jMuhfouo3sFXcDYHZtt8S7iWanUv4ftE)
<hr>


