# Developing a Neural Network Regression Model

## AIM
To develop a neural network regression model for the given dataset.

## THEORY
Explain the problem statement

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Create your dataset in a Google sheet with one numeric input and one numeric output.

### STEP 2: 

Split the dataset into training and testing

### STEP 3: 

Create MinMaxScalar objects ,fit the model and transform the data.

### STEP 4: 

Build the Neural Network Model and compile the model.

### STEP 5: 

Train the model with the training data.

### STEP 6: 

Plot the performance plot

### STEP 7: 

Evaluate the model with the testing data.

### STEP 8: 

Use the trained model to predict  for a new input value .

## PROGRAM

### Name: Monika A

### Register Number: 212224240094

```python
class NeuralNet(nn.Module):
    def __init__(self):
        super().__init__()
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer



def train_model(ai_brain, X_train, y_train, criterion, optimizer, epochs=2000):
    #Include your code here

```

### Dataset Information
<img width="431" height="558" alt="image" src="https://github.com/user-attachments/assets/32b4c633-17d3-4c26-ad0e-3a248c1cb160" />

### OUTPUT
<img width="457" height="269" alt="image" src="https://github.com/user-attachments/assets/70fe3295-e8ab-4453-b85d-bc61c20e1f6b" />
<img width="257" height="51" alt="image" src="https://github.com/user-attachments/assets/bf73516e-48f4-47cc-92e1-d1ae215edbf1" />

### Training Loss Vs Iteration Plot
<img width="761" height="610" alt="image" src="https://github.com/user-attachments/assets/9f5bf2eb-4baa-4ce8-803e-091f46385777" />


### New Sample Data Prediction
<img width="417" height="61" alt="image" src="https://github.com/user-attachments/assets/a76d2f58-dfd5-4a30-bd1f-43483e5f4598" />

## RESULT
Thus, a neural network regression model was successfully developed and trained using PyTorch.
