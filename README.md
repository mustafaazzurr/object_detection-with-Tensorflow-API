# Object detection with Tensorflow API
### The working tutorial of object detection with tensorflow 
 
## tutorial by EdjeElectronics  : 
https://github.com/EdjeElectronics/TensorFlow-Object-Detection-API-Tutorial-Train-Multiple-Objects-Windows-10

## Important 
Compile Protobufs:
use this command:

```
protoc --python_out=. .\object_detection\protos\anchor_generator.proto .\object_detection\protos\argmax_matcher.proto .\object_detection\protos\bipartite_matcher.proto .\object_detection\protos\box_coder.proto .\object_detection\protos\box_predictor.proto .\object_detection\protos\eval.proto .\object_detection\protos\faster_rcnn.proto .\object_detection\protos\faster_rcnn_box_coder.proto .\object_detection\protos\grid_anchor_generator.proto .\object_detection\protos\hyperparams.proto .\object_detection\protos\image_resizer.proto .\object_detection\protos\input_reader.proto .\object_detection\protos\losses.proto .\object_detection\protos\matcher.proto .\object_detection\protos\mean_stddev_box_coder.proto .\object_detection\protos\model.proto .\object_detection\protos\optimizer.proto .\object_detection\protos\pipeline.proto .\object_detection\protos\post_processing.proto .\object_detection\protos\preprocessor.proto .\object_detection\protos\region_similarity_calculator.proto .\object_detection\protos\square_box_coder.proto .\object_detection\protos\ssd.proto .\object_detection\protos\ssd_anchor_generator.proto .\object_detection\protos\string_int_label_map.proto .\object_detection\protos\train.proto .\object_detection\protos\keypoint_box_coder.proto .\object_detection\protos\multiscale_anchor_generator.proto .\object_detection\protos\graph_rewriter.proto 
```

## the tutorial video:
https://www.youtube.com/watch?v=Rgpfk6eYxJA


## How to get it to work:

1. clone the repository 
2. move the models folder and put it in a folder with this path .. C:\tensorflow1\
3. follow the tutorial by EdjeElectronics 


## Working Requirments( these requiremnts worked for me ) 

- tensorflow            1.13.1
- or tensorflow-gpu    1.15.0
- protobuf             3.11.3
- Pillow               7.0.0
- numpy                1.18.2
- lxml                 4.5.0
- opencv-python        4.2.0.32
- Cython               0.29.15
- matplotlib           3.0.3
- pandas               0.25.3

