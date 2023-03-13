## Industrial Fire Detection

Here, we will be using the dataset smoke_detection_iot.csv, downloaded from [Kaggle](https://www.kaggle.com/datasets/deepcontractor/smoke-detection-dataset). It was created by Stefan Blattmann in his project [Real-time Smoke Detection with AI-based Sensor Fusion](https://www.hackster.io/stefanblattmann/real-time-smoke-detection-with-ai-based-sensor-fusion-1086e6#toc-model-details-9). We will be using it to explore what can be learned about the minimum information needed to determine if there is fire present. It contains over 62M rows of tested atmospheric conditions and wether or not fire was present.

We settled on a random forest model, and tested all possible combinations of features that do not include particulate information, which is how a smoke detector works. Then we determined that fire detection is possible without smoke detectors, given enough atmospheric data.

The EDA and modeling is in Notebook.pdf. A summary of the findings is in Presentation.pdf. Check out Mr. Blattmann's project if you have time! It's really interesting. Overall, this project provides valuable insights into the possibility of detecting fire through atmospheric data, potentially informing the development of new fire detection technologies or improving existing ones.
