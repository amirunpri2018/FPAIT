# Fast Parameter Adaptation for Few-shot Image Captioning and Visual Question Answering


## Data Preparation

### Download
Make directory at `~/datasets/MS-COCO`.
- download the ms-coco [train](http://images.cocodataset.org/zips/train2014.zip), [val](http://images.cocodataset.org/zips/val2014.zip), and [test](http://images.cocodataset.org/zips/test2014.zip).
- download the [trainval2014-annotation](http://images.cocodataset.org/annotations/annotations_trainval2014.zip), and the [test info](http://images.cocodataset.org/annotations/image_info_test2014.zip).
- organize the data as follows, where trainval2014 contains all the trainval images and test2014 contains all the test images.
```
- ~/datasets/MS-COCO
-- annotations
--- captions_train2014.json captions_val2014.json image_info_test2014.json instances_train2014.json instances_val2014.json
-- test2014
-- trainval2014
```

### Compile coco api
```
cd cocoapi
make
```
