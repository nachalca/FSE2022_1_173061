## Following is a brief description of the subfolders contained within this folder

|Folder|Description|
|------|-----------|
|`downscaling_evaluation`|Reports that show the performance of different models at downscaling `CMIP` data. We have a report for each variable that we downscaled. We can find the data used to make these reports in `to_be_downscaled`, also we are using the `reanalysis` data as a reference for the first years. The code, which generates these reports, can be found in `downscaling_reports_generator`| 
|`model_evaluation`|Reports that show the performance of different models at downscaling the `testing` data. Remember that these `testing` data is the part of the `reanalysis` data that was not used to train the model (we have the reanalysis "observations" upscaled as if they are `CMIP` projections). We have a report for each variable we wish to downscale. We can find the data used to make these reports in `model_evaluation`. The code, which generates these reports, can be found in `model_evaluation_reports_generator`|

