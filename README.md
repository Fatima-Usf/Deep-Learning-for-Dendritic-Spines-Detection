# Deep-Learning-for-Dendritic-Spines-Detection
Benchmarking Yolov2, Faster-RCNN and Shape-Priors-CNN on dendritic spines detection

1- **Faster-RCNN**:

The model is already trained and the final weights are in Faster-RCNN/inference_graph, also the results are in Faster-RCNN/results.
To re-calculate the predictions on the test set run F1_score_and_predictions.py. to recalculate on other images change the path to the folder 
containing the images.

2- **SP-CNN**: 

run the jupyter notebook. Note that the train images are not complete (due to size issues), but they will give you a sense of the overall pipeline.
