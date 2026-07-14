# Week 1 — Forward Pass Code Walkthrough

## Purpose

This document explains the supplied forward-pass implementation line by line.

The goal is not to restate the code. The goal is to explain:

- what each line does;
- why it is required;
- what shape each value has;
- what would happen if the line were removed or changed;
- which permanent concept note explains the underlying idea.

---

## Assignment Flow

```text
Word
→ Vector
→ Hidden Layer
→ Raw Scores / Logits
→ Softmax
→ Prediction
```

---

## Source Information

- **Source file:**
- **Provided by:**
- **Date received:**
- **Programming language:**
- **Libraries used:**
- **Entry point:**

---

## Vocabulary and Training Examples

### Vocabulary

| Index | Token |
|------:|-------|
| | |

### Training or Example Pairs

| Input | Expected output |
|-------|-----------------|
| | |

---

## Shape Summary

Record every important value before the detailed walkthrough.

| Name | Meaning | Shape | Example |
|------|---------|-------|---------|
| input index | Numerical position of the input word | scalar | |
| input vector | Numerical representation of the word | | |
| input-to-hidden weights | Weights connecting input to hidden layer | | |
| hidden bias | Bias applied to hidden layer | | |
| hidden pre-activation | Weighted input before activation | | |
| hidden activation | Hidden-layer output | | |
| hidden-to-output weights | Weights connecting hidden to output | | |
| output bias | Bias applied to output layer | | |
| logits | Raw output scores | | |
| probabilities | Softmax output | | |
| predicted index | Index selected by Argmax | scalar | |
| predicted word | Final output token | scalar/string | |

---

## Complete Data Trace

Choose one input word and trace it through the network.

### Selected Input

- **Input word:**
- **Input index:**
- **Expected output:**

### Step 1 — Convert Word to Numerical Representation

**Code:**

```python
# Paste only the relevant line or small block
```

**Explanation:**

**Input shape:**

**Output shape:**

**Why this step exists:**

**Related note:**

---

### Step 2 — Input-to-Hidden Calculation

**Code:**

```python
# Paste only the relevant line or small block
```

**Equation:**

```text
hidden_pre_activation = input_vector × input_hidden_weights + hidden_bias
```

**Explanation:**

**Input shapes:**

**Output shape:**

**Why this step exists:**

**What would happen if bias were removed:**

**Related notes:**

---

### Step 3 — Hidden-Layer Activation

**Code:**

```python
# Paste only the relevant line or small block
```

**Equation:**

```text
hidden_activation = activation(hidden_pre_activation)
```

**Activation used:**

**Input shape:**

**Output shape:**

**Why this activation is used:**

**What would happen without an activation function:**

**Related notes:**

---

### Step 4 — Hidden-to-Output Calculation

**Code:**

```python
# Paste only the relevant line or small block
```

**Equation:**

```text
logits = hidden_activation × hidden_output_weights + output_bias
```

**Explanation:**

**Input shapes:**

**Output shape:**

**Why the result is called logits/raw scores:**

**Related notes:**

---

### Step 5 — Softmax

**Code:**

```python
# Paste only the relevant line or small block
```

**Equation:**

```text
probabilities = softmax(logits)
```

**Logits:**

```text
[]
```

**Probabilities:**

```text
[]
```

**Sum of probabilities:**

**Why Softmax is used:**

**Why the highest probability does not guarantee correctness:**

**Related note:**

---

### Step 6 — Argmax and Prediction

**Code:**

```python
# Paste only the relevant line or small block
```

**Explanation:**

**Predicted index:**

**Predicted word:**

**Was the prediction correct:**

**If correct, was it learning or luck:**

**Related notes:**

---

## Line-by-Line Walkthrough

Use one row for each meaningful line or small logical block.

| Line(s) | Code purpose | Input | Output | Shape change | Why required | What if removed/changed? |
|---------|--------------|-------|--------|--------------|--------------|--------------------------|
| | | | | | | |

---

## Random Initialization

### Where are the weights initialized?

```python
# Paste the relevant code
```

### Questions

- Why are the initial values random?
- What distribution or range is used?
- What changes when the random seed changes?
- Why can an untrained model sometimes predict correctly?
- Are the probabilities meaningful before training?

### My explanation

Write the explanation in your own words:

---

## Manual Numerical Example

Create the smallest possible network that can be calculated by hand.

Suggested size:

```text
Vocabulary size: 3
Input size: 3
Hidden size: 2
Output size: 3
```

### Input vector

```text
[]
```

### Input-to-hidden weights

```text
[]
```

### Hidden bias

```text
[]
```

### Hidden pre-activation

```text
[]
```

### Hidden activation

```text
[]
```

### Hidden-to-output weights

```text
[]
```

### Output bias

```text
[]
```

### Logits

```text
[]
```

### Softmax probabilities

```text
[]
```

### Predicted index and token

---

## Questions and Uncertainties

Record questions immediately instead of hiding gaps.

- [ ] 
- [ ] 
- [ ] 

---

## Final Explanation

Explain the complete forward pass without looking at the source code:

> 
