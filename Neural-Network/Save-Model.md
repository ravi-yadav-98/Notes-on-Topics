## Save Model in keras
### 1. HDF5 format
-  keras.Model.save("model.h5")
-  Now we can save our model just by calling model.save function and passing in the filepath as the argument. This will save the model’s
   1. **Model Architecture**
   2. **Model Weights**
   3. **Model optimizer state (so that you can continue the training from where you left)**
-  Now when the model is saved in the current directory as myModel.h5 file, you can simply load it in a new program, or same program as a different model 
-  tf.keras.models.load_model("model.h5")

### 2. Save Weights:
-  Keras.save_weights("weight_file")
-  Create three files:
   1. Checkpoints
   2. data-00000-of-00001: This file contains the actual weights from the model.(Largest file)
   3. Index: This file tells TensorFlow which weights are stored where.

