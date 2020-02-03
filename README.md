# DLPointCloudProject
a record and plan of the Msc. point cloud project using deep learning (DL)

## Recording
- Producing npy file and h5 file( 3 Feb, 2020)；1)generate npy and h5 files; 2) trian the segmentation model on the newly labeled MEP data. 


## Plan and resources

### 3 Feb~ 3 Mar
- labeling WRII dataset

- use HKUST hpc2 to train the model
  - apply hpc2 account; Chao will send the application template.
  - set the DL working env, mainly install tensorflow-gpu, other common scientific packages; Chao will share his ppt.
  - run the model with 1 GPU
  - run the model with 4 GPUs

- visulaization and preliminary analysis
   - visualization using tensorboad, e.g.: the loss, accuracy graph , the code is already in the pointnet code.
   - draw the confusion matrix and Precision-Recall or ROC curve.
   - draw some conclusion based on yr experiment results
   
 Note: you may need repeat experiments many times for better performance. Follow the workflow  ideas--> experiment setting --> experiments --> analysis, then repeat this cycle until you find something intersting or useful.
