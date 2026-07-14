---

## Learning Stages

The stages are based on knowledge dependencies, not calendar days.

A stage may take a few hours or several days. Progress depends on understanding, not time.

---

## Stage 1 — Machine Learning Foundations

### Concepts

- [ ] Machine Learning
- [ ] Traditional Programming vs Machine Learning
- [ ] Supervised Learning
- [ ] Dataset
- [ ] Input and Output
- [ ] Features and Labels
- [ ] Model
- [ ] Prediction

### Readiness Questions

- [ ] Why would we use machine learning instead of writing explicit rules?
- [ ] What does a machine-learning system learn from data?
- [ ] What is the difference between an algorithm and a trained model?
- [ ] What is the input in this assignment?
- [ ] What is the expected output?
- [ ] Why can next-word prediction be treated as supervised learning?

### Permanent Notes

- `notes/ML - Machine Learning.md`
- `notes/ML - Traditional Programming vs Machine Learning.md`
- `notes/ML - Supervised Learning.md`
- `notes/ML - Dataset.md`
- `notes/ML - Features and Labels.md`
- `notes/ML - Model.md`
- `notes/ML - Prediction.md`

---

## Stage 2 — Representing Words as Numbers

### Concepts

- [ ] Vocabulary
- [ ] Token
- [ ] Token Index
- [ ] Scalar
- [ ] Vector
- [ ] One-Hot Encoding
- [ ] Word Representation

### Readiness Questions

- [ ] Why cannot a word be passed directly into a neural network?
- [ ] What does the vocabulary contain?
- [ ] Why does each word need a numerical index?
- [ ] What does each position in a one-hot vector represent?
- [ ] What information does one-hot encoding preserve?
- [ ] What information does one-hot encoding fail to represent?
- [ ] How does the input word become the vector used by the network?

### Permanent Notes

- `notes/LM - Vocabulary.md`
- `notes/LM - Token.md`
- `notes/LM - Token Index.md`
- `notes/LM - One-Hot Encoding.md`
- `notes/MATH - Scalar.md`
- `notes/MATH - Vector.md`

---

## Stage 3 — Mathematical Foundations

### Concepts

- [ ] Matrix
- [ ] Matrix Shape
- [ ] Dot Product
- [ ] Matrix Multiplication

### Readiness Questions

- [ ] What is the difference between a scalar, vector, and matrix?
- [ ] What does the shape of a matrix tell us?
- [ ] Why must matrix dimensions be compatible?
- [ ] What does multiplying an input vector by a weight matrix produce?
- [ ] Can I manually calculate a small vector-matrix multiplication?

### Permanent Notes

- `notes/MATH - Matrix.md`
- `notes/MATH - Matrix Shapes.md`
- `notes/MATH - Dot Product.md`
- `notes/MATH - Matrix Multiplication.md`

---

## Stage 4 — Neural-Network Building Blocks

### Concepts

- [ ] Artificial Neuron
- [ ] Weight
- [ ] Bias
- [ ] Random Initialization
- [ ] Hidden Layer
- [ ] Activation Function
- [ ] tanh

### Readiness Questions

- [ ] What role does a weight play in a neural network?
- [ ] Why is bias added?
- [ ] Why are the initial weights random?
- [ ] What does the hidden layer produce?
- [ ] Why do neural networks use activation functions?
- [ ] What range of values does `tanh` produce?
- [ ] What would happen if the activation function were removed?

### Permanent Notes

- `notes/NN - Artificial Neuron.md`
- `notes/NN - Weights.md`
- `notes/NN - Bias.md`
- `notes/NN - Random Initialization.md`
- `notes/NN - Hidden Layer.md`
- `notes/NN - Activation Functions.md`
- `notes/NN - tanh.md`

---

## Stage 5 — Converting Computation into a Prediction

### Concepts

- [ ] Raw Scores
- [ ] Logits
- [ ] Softmax
- [ ] Probability Distribution
- [ ] Argmax
- [ ] Prediction

### Readiness Questions

- [ ] What are the raw output scores produced by the network?
- [ ] Why are logits not probabilities?
- [ ] What transformation does Softmax perform?
- [ ] Why do Softmax outputs sum to one?
- [ ] Does the highest Softmax value guarantee that the prediction is correct?
- [ ] What does Argmax return?
- [ ] What is the difference between a probability and a predicted class?

### Permanent Notes

- `notes/NN - Logits.md`
- `notes/NN - Softmax.md`
- `notes/NN - Probability Distribution.md`
- `notes/NN - Argmax.md`

---

## Stage 6 — Understand the Complete Forward Pass

### Concepts

- [ ] Forward Pass
- [ ] Tensor and Matrix Shape Tracing
- [ ] Untrained Model Behaviour
- [ ] Random Prediction
- [ ] Inference Without Learning

### Readiness Questions

- [ ] Can I explain every step from the input word to the predicted word?
- [ ] Can I state the shape of each vector and matrix?
- [ ] Can I calculate a small forward pass manually?
- [ ] Why is the model's first prediction effectively random?
- [ ] Why can an untrained model occasionally make the correct prediction?
- [ ] What part of the system changes during learning?
- [ ] What is missing from this assignment that would allow the network to learn?

### Permanent Notes

- `notes/NN - Forward Pass.md`
- `notes/NN - Untrained Model.md`
- `notes/NN - Inference.md`

---

## Stage 7 — Assignment Implementation

- [ ] Read the supplied code without changing it.
- [ ] Identify the input and expected output.
- [ ] Identify the vocabulary and word indexes.
- [ ] Identify every vector and matrix.
- [ ] Record the shape of every computation.
- [ ] Trace one input through the complete network.
- [ ] Run the original implementation.
- [ ] Explain the output.
- [ ] Implement the forward pass independently.
- [ ] Compare my implementation with the supplied version.
- [ ] Perform at least three experiments.
- [ ] Record observations and unexpected behaviour.
- [ ] Complete the code review.
- [ ] Complete the reflection.

---

## Concepts Deliberately Deferred

The following concepts are related, but they are not prerequisites for understanding the first forward pass:

- Loss Functions
- Cross-Entropy Loss
- Backpropagation
- Gradients
- Gradient Descent
- Stochastic Gradient Descent
- Adam Optimizer
- Training Loops
- Batch Processing
- Regularization

These concepts will be introduced when the assignment begins teaching the network from its mistakes.

---

## Prerequisite Completion Rule

The prerequisites are complete only when I can:

1. Explain every stage in my own words.
2. Work through a small numerical example.
3. Identify where each concept appears in the assignment.
4. Trace the shapes through the complete network.
5. Implement the forward pass without copying the supplied solution.
6. Explain why the untrained output is random.
7. Explain what must be added for the network to learn.

---

## Current Stage

**Stage 1 — Machine Learning Foundations**

Current concept:

`notes/ML - Machine Learning.md`