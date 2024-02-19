The methods are as follows:
• Custom Neural Network: Create effective PyTorch model for digit recognition.
• Efficient Data Handling: Utilize Torch data loader for seamless dataset management.
• Specialized Training Loop: Optimize training with customized gradient descent and loss function.
• Architectural Enhancements: Explore dropout layers for improved model performance.
• Performance Evaluation: Visualize and compare metrics for model accuracy assessment

Problem Statement 
Develop a robust handwritten digit recognition system using deep learning techniques. The task involves 
creating a neural network model trained on the MNIST dataset, which contains images of handwritten 
digits from 0 to 9. The goal is to accurately classify these digits.

Details
1. Data Preparation:
• Downloaded the MNIST dataset from Kaggle and done preprocess.
• split the data into an 80% training set and a 20% validation set in stratified fashion using 
scikit learn train_test_split function.
• Utilized the Torch data loader to efficiently load and manage the dataset.
2. Training Process:
• Optimizer: Gradient stochastic descent
• Learning rate: 0.01
• Loss Function: Cross Entropy
3. Plots are the following:
• Training and validation loss.
• Training and validation accuracy
4. Analysis:
• Evaluated the impact on the model's training and final performance based on the 
following factors:
• Changed the learning rate, tried 5 different learning rates.
• Changed the batch size, tried 5 different batch sizes. 
5. also
• Introduce dropout layer and layer normalization to my model and analysed the effect of 
adding them on the training and final performance.
