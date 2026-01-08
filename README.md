# Probability Essentials — FAANG-Level Lab

**Goal:** Build ML-relevant probability intuition: random variables, expectations, variance, Bayes’ rule, common distributions, and sampling.

**Outcome:** Students can compute probabilities/expectations, implement small simulations, and explain how probability maps to ML (calibration, Naive Bayes, uncertainty).

---

# How to Start

1. **Fork** this repository.  
2. Open `probability_student_lab.ipynb` in **Google Colab**.  
3. Complete all **TODO** sections.  
4. **Restart runtime → Run All** cells.  
5. Push changes and submit a **Pull Request**.  

⚠️ **Do NOT edit notebooks directly on GitHub.**

---

## Lab Rules (FAANG Style)

- ✅ Write assumptions clearly
- ✅ Separate math reasoning from implementation
- ✅ Validate results with simulation when possible

---

# Notebook Rules

- Do **NOT** rename the notebook  
- Do **NOT** delete TODOs  
- Do **NOT** hardcode outputs  
- Notebook must run **top-to-bottom**  

---

# Dataset

- Synthetic distributions and toy text

## Why?

- Probability interviews usually use clean toy setups
- Simulation helps catch reasoning mistakes

---

## Section 1 — Discrete Random Variables

### Task 1.1: Expectation & variance from a PMF

**Checkpoint Questions:**

- Why is expectation linear?
- When do you need covariance?

---

## Section 2 — Conditional Probability & Bayes

### Task 2.1: Bayes theorem (base-rate fallacy)

**Interview Angle:**

- Why can a “99% accurate test” still have low P(D|+)?

---

### Task 2.2: Simulation check

**Checkpoint Questions:**

- Why does simulation converge (law of large numbers)?

---

## Section 3 — Continuous Distributions

### Task 3.1: Normal standardization

**ML Context:** standardization stabilizes optimization and improves conditioning.

---

## Section 4 — Naive Bayes Thinking (Optional)

### Task 4.1: Log-space posterior odds

**FAANG Gotcha:**

- Underflow from multiplying tiny probabilities; use logs.

---

## Stretch

- Implement Naive Bayes from scratch for toy text
- Derive expectation/variance for a custom distribution

---

## Submission Expectations

Students must submit:

- Clean notebook (runs top-to-bottom)
- Answers to **Checkpoint/Explain** prompts
- Notes on assumptions (independence, IID, etc.)

---

## FAANG Interview Evaluation Rubric

| Skill                         | Evaluated |
|------------------------------|-----------|
| Correct probabilistic reasoning| ✅       |
| Bayes intuition               | ✅        |
| Simulation sanity checks      | ✅        |
| Numerical stability (logs)    | ✅        |
| Explanation clarity           | ✅        |
