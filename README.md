# Conversion to Lite Format

##### Import all the packages:
 - Tensorflow , numpy
 - Note : Tensorflow has not yet included all the modules of lite in the recent tensorflow version.
 - According to them it will be updated in 1.15 version.


##### Make a zip file:

  - You should have a zip file which contains all the checkpoint files as well as frozen model file(.pb) extension.

  -  -Upload this zip directly into the colab. Take care about the directories where your model is uploaded and update them accordingly in the code.

##### Names of the tensors:

  - Whenever you use the frozen graph we have their input and output tensors which we need to use them in the toco converter.

   - Upload this zip directly into the colab. Take care about the directories where your model is uploaded and update them accordingly in the code.

##### Inputs in the conversion function

 - Inputs for the conversion function:
 - img_size_x  = Size of the input tensor.
 - img_size=_y=Size of the input tensor.
 - channels= Number of Channels.
 - direc = path from where we should load all files..
 - frozen_model_pb = frozen graph name
 - checkpoint_path=the complete path and name of the meta file: 
 - The file was-> “CD_Check_k/filename_CD.ckpt.meta”  
 - Give input-  "CD_Check_k/filename_CD.ckpt" 
