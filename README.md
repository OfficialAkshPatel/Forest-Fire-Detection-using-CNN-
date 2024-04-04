<h1> forest fire detection Using CNN</h1>

This project is an attempt to use CNN to detect the presence or the start of a forest fire in an image. The idea is that this model could be applied to detect a fire or a start of a fire from (aerial) surveillance footage of a forest. The model could be applied in real-time to low-framerate surveillance video and give alert in case of fire.

Data set link: https://github.com/DeepQuestAI/Fire-Smoke-Dataset/releases/download/v1/FIRE-SMOKE-DATASET.zip

Project flow : 

Detecting forest fires using Convolutional Neural Networks (CNNs) involves several steps. 

1. Data Collection:
   - Gather a dataset of images containing both forest fire scenes and non-fire scenes (normal forest images).
   - Ensure that the dataset is diverse and representative of different conditions and types of fires.

2. Data Preprocessing:
   - Resize all images to a uniform size suitable for input into the CNN.
   - Normalize pixel values to a common scale (e.g., [0, 1]).
   - Split the dataset into training, validation, and test sets.

3. Model Architecture Selection:
   - Choose a CNN architecture suitable for image classification tasks. Popular choices include VGG, ResNet, or custom architectures.
   - Consider transfer learning if you have limited data, by using pre-trained models and fine-tuning them on your dataset.

4. Model Training:
   - Initialize the selected CNN architecture.
   - Feed training images into the network and adjust the weights using backpropagation and optimization algorithms (e.g., Adam, SGD).
   - Monitor the performance on the validation set to avoid overfitting by adjusting hyperparameters like learning rate, batch size, and regularization techniques (e.g., dropout).

5. Evaluation:
   - Assess the trained model's performance using the test set.
   - Evaluate metrics such as accuracy, precision, recall, and F1-score to quantify the model's effectiveness.
   - Visualize the model's predictions and analyze any misclassifications.

6. Deployment:
   - Integrate the trained model into a forest fire detection system.
   - Develop an interface (e.g., web application, mobile app) for users to interact with the system.
   - Ensure the system is capable of real-time or near-real-time detection depending on the requirements.
   - Implement mechanisms for alerting relevant authorities or users in case of fire detection.

7. Monitoring and Maintenance:
   - Continuously monitor the performance of the deployed system.
   - Retrain the model periodically with new data to adapt to changing environmental conditions and improve accuracy.
   - Update the system as needed to incorporate new features or address any issues that arise.

Throughout the project, it's essential to document each step thoroughly, including data sources, preprocessing techniques, model architectures, training procedures, and evaluation results, to ensure reproducibility and facilitate future improvements. Additionally, consider ethical implications, such as privacy concerns related to surveillance and potential biases in the dataset or model predictions.

Accuracy of all Algorithm :

<img src="Screenshot 2024-04-04 at 9.50.44 AM.png" width="600">  
