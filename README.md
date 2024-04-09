# MediMAte
MediMate is an innovative medical concept that aims to offer a comprehensive and effective
way to identify common disorders. Utilising cutting-edge medical technology, MediMate
combines data analytics and diagnostics to provide a complete and easy-to-use platform for
early disease detection and management. A convolutional neural network (ConvNet/CNN)
deep learning algorithm will be used to recognise different objects and attributes in an input
image and distinguish between them by assigning weights and biases that can be learned. The
reason behind using the ConvNet algorithm is that the pre-processing required in the given
algorithm is much lower as compared to other classification algorithms. MediMate should be
able to reduce the images into a form that is easier to process without losing features that are
critical for getting a good prediction.

# Enviornment Setup

conda create -n medimate python=3.9.13
conda activate medimate 
pip install opencv-python==4.5.1.48 numpy tensorflow==2.12.0 scikit-learn==0.24.2 imutils==0.5.4 flask==3.0.0 xgboost==2.0.3

Running Application
flask run OR flask run --debug
