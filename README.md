# Quant Interview Review Sheet

This repository contains a LaTeX document summarizing key topics for quantitative trading interviews — from probability and statistics to stochastic processes, finance, and brainteasers.
Test

📄 **Compiled PDF**: [Quant Interview Review Sheet](Quant_Interview_Review_Sheet.pdf)  
✏️ **Source LaTeX**: [Quant_Interview_Review_Sheet.tex](Quant_Interview_Review_Sheet.tex)

---

## Preview

![Preview Page 1](preview_page1.png)

---

## Topics Covered

- **Probability**
  - Combinatorics
  - Bayes' theorem & conditional probability
  - Expectation, variance, covariance, correlation
  - Common distributions

- **Statistics**
  - Normal distribution
  - Hypothesis testing
  - Maximum likelihood estimation

- **Stochastic Processes**
  - Markov chains
  - Martingales
  - Random walks
  - Dynamic programming

- **Finance**
  - Options & derivatives
  - Portfolio theory
  - Arbitrage and pricing

- **Brainteasers**
  - Common sequences
  - Recursion patterns

---

## Math Example

Inline math: $P(A \cup B) = P(A) + P(B) - P(A \cap B)$  
Block math:

$$
\mathbb{E}[X] = \mathbb{E}[\mathbb{E}[X \mid Y]]
$$

---

## Compilation

To compile:

```bash
pdflatex Quant_Interview_Review_Sheet.tex
bibtex Quant_Interview_Review_Sheet
pdflatex Quant_Interview_Review_Sheet.tex
pdflatex Quant_Interview_Review_Sheet.tex

