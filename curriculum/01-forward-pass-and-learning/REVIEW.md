# Week 1 — Forward Pass Review

## Purpose

This document reviews the completed assignment from four perspectives:

1. conceptual correctness;
2. implementation correctness;
3. experimentation and observations;
4. engineering quality.

---

## Assignment Summary

- **Assignment:**
- **Implementation location:**
- **Date started:**
- **Date completed:**
- **Current status:** Not started / In progress / Completed / Revisiting

### What the program does

> 

### What the program does not do

> 

---

## Conceptual Review

### Can I explain the complete flow?

```text
Word
→ Vector
→ Hidden Layer
→ Logits
→ Softmax
→ Argmax
→ Predicted Word
```

- [ ] Yes, without notes
- [ ] Yes, with minor prompts
- [ ] Not yet

### Concept Confidence

| Concept | Confidence | Evidence |
|---------|------------|----------|
| Vocabulary | ⭐☆☆☆☆ | |
| Token index | ⭐☆☆☆☆ | |
| Vector | ⭐☆☆☆☆ | |
| Matrix shape | ⭐☆☆☆☆ | |
| Matrix multiplication | ⭐☆☆☆☆ | |
| Weight | ⭐☆☆☆☆ | |
| Bias | ⭐☆☆☆☆ | |
| Hidden layer | ⭐☆☆☆☆ | |
| Activation function | ⭐☆☆☆☆ | |
| Logits | ⭐☆☆☆☆ | |
| Softmax | ⭐☆☆☆☆ | |
| Argmax | ⭐☆☆☆☆ | |
| Forward pass | ⭐☆☆☆☆ | |
| Random initialization | ⭐☆☆☆☆ | |

---

## Shape Review

| Operation | Expected shapes | Actual shapes | Correct? |
|-----------|-----------------|---------------|----------|
| Input representation | | | |
| Input × input-hidden weights | | | |
| Add hidden bias | | | |
| Hidden activation | | | |
| Hidden × hidden-output weights | | | |
| Add output bias | | | |
| Softmax | | | |
| Argmax | | | |

### Shape mistakes found

> 

### How they were fixed

> 

---

## Implementation Review

### Correctness

- [ ] Input token is converted correctly.
- [ ] The vector representation has the correct size.
- [ ] Matrix operations use compatible shapes.
- [ ] Bias is applied correctly.
- [ ] Activation is applied at the intended layer.
- [ ] Output logits have one value per vocabulary token.
- [ ] Softmax output sums approximately to 1.
- [ ] Argmax selects the intended index.
- [ ] Predicted index maps back to the correct token.
- [ ] Random seed behaviour is understood.

### Readability

- [ ] Names describe the values they contain.
- [ ] Shape information is easy to inspect.
- [ ] The forward pass is separated into understandable steps.
- [ ] No unnecessary abstraction hides the mathematics.
- [ ] Comments explain why, not merely what.
- [ ] Output is clear enough for a learner to follow.

### Engineering Questions

- Are there hidden assumptions?
- Are dimensions hard-coded?
- Does the code fail clearly for an unknown token?
- Is numerical stability considered in Softmax?
- Can the forward pass be tested independently?
- Could another learner understand the code without the CTO solution?

### Findings

| Severity | Finding | Impact | Proposed improvement |
|----------|---------|--------|----------------------|
| | | | |

---

## Experiments

Complete at least three experiments.

### Experiment 1 — Change the Random Seed

**Question:**

How does changing the random seed affect the prediction?

**Change made:**

**Result:**

**Explanation:**

**Lesson learned:**

---

### Experiment 2 — Change Hidden-Layer Size

**Question:**

How does changing the number of hidden units affect shapes and output?

**Change made:**

**Result:**

**Explanation:**

**Lesson learned:**

---

### Experiment 3 — Change or Remove the Activation Function

**Question:**

What changes when `tanh` is replaced or removed?

**Change made:**

**Result:**

**Explanation:**

**Lesson learned:**

---

### Optional Experiment 4 — Stable vs Naive Softmax

**Question:**

What happens with very large logits?

**Change made:**

**Result:**

**Explanation:**

**Lesson learned:**

---

### Optional Experiment 5 — Manually Chosen Weights

**Question:**

Can weights be selected to force a known prediction?

**Change made:**

**Result:**

**Explanation:**

**Lesson learned:**

---

## Test Cases

| Test | Input | Expected behaviour | Actual result | Pass? |
|------|-------|--------------------|---------------|-------|
| Known vocabulary token | | | | |
| Another known token | | | | |
| Unknown token | | | | |
| Softmax sum | logits | Approximately 1 | | |
| Repeated run with same seed | | Same result | | |
| Repeated run with different seed | | May differ | | |

---

## Comparison With Supplied Implementation

### Similarities

> 

### Differences

> 

### Improvements in my version

> 

### Things the supplied version does better

> 

---

## Knowledge Gaps Discovered

- [ ] 
- [ ] 
- [ ] 

For each gap, link or create a permanent note.

---

## Final Review Decision

### Assignment result

- [ ] Needs major revision
- [ ] Works, but understanding is incomplete
- [ ] Correct and understood
- [ ] Mastered well enough to teach

### Evidence for the decision

> 

### Next action

> 
