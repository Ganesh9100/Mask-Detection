I have trained the model with 2 class of images , Mask and No_Mask ,Where I ran my model in Google Colab till 1300 iteration which gives me the Highest Accuracy .

Upload the below files to darknet/data directory :

   train.txt
   obj.names
   obj/data
   dataset 
   test.txt ( optional )
 
  

My Model Summary :
 
 

<b> Mask_Not_Detected</b>
<p align="left">
  
  <img src="https://github.com/Ganesh9100/Mask-Detection-YOLO_V3-/blob/master/download1.png" width="250" title="hover text">
  
</p>
<b> Mask_Detected</b>
<p align="left">
  
  <img src="https://github.com/Ganesh9100/Mask-Detection-YOLO_V3-/blob/master/download2.png" width="250" title="hover text">
  
</p>

<b><s> Model_Summary</s></b>
<p align="left">
  
  <img src="https://github.com/Ganesh9100/Mask-Detection-YOLO_V3-/blob/master/summary.jpeg" width="450" title="hover text">
  
</p>



<p>
 <b>class_id = 0, name = Mask_Detected , ap = 98.04% (TP = 681, FP = 29)</b>
 
 <b>class_id = 1, name = Mask_Not_Detected, ap = 96.70% (TP = 385, FP = 18)</b>

for conf_thresh = 0.25, precision = 0.96, recall = 0.96, <b>F1-score = 0.96</b>

for conf_thresh = 0.25, TP = 1066, FP = 47, FN = 40, <b>average IoU = 71.77 %</b>

IoU threshold = 50 %, used Area-Under-Curve for each unique Recall
<b>mean average precision (mAP@0.50) = 0.973706, or 97.37 %</b>
Total Detection Time: 33 Seconds

</p>




 
