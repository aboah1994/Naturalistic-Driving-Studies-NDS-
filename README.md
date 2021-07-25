# Naturalistic-Driving-Studies-NDS-

# 1. Goal
The goal of this Project was to understand the driver's environment.

# 2. Data Collection
The data used in this project was collected by the deepinsight app. The app has
two cameras that records the driver's activity inside the vehicle and the driver's environment.

# 3. Annotations: 
Polygons were used to precisely outline the shape of objects in this annotation. 
Seven classes of objects were labeled namely cars, skies, road, lane markings, buildings, 
trees, and trucks. A total of 1000 images were annotated. Examples of annotated images are 
shown in Figure

# 4. Model building 
I developed a semantic segmentation model using the U-Net architecture. The model was trained 
with about 660 images. Each image had an input size of 256 x 256 pixels dimension. Batch normalization 
was performed using a batch size of 32. The loss function used in the model was the binary cross-entropy 
loss while using a dropout of 0.1. The activation function used was the sigmoid activation function.

# 5. Model Evaluation 
After 50 epochs of training, the model converged. The model's performance was evaluated using accuracy. 
After training, the model achieved approximately 46% accuracy.  This means that 46% of the time, the model 
correctly classifies a pixel as belonging to a specific class. The training loss was approximately 0.27, as 
illustrated in Figure.

