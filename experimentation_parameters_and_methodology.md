# LLM Experiment: Comparing outputs of different instances of several models to check for determinism and hallucination
 Google AI Studio url: https://aistudio.google.com/

Setup parameters (kept same for both instances of all models):
1. Temperature = 0
2. Top P = 1
3. Output length (number of output tokens) = 65536
<br>(given below are additional tools provided by Google AI Studio)<br>
4. Thinking mode = disabled
5. Grounding with Google Search = disabled
6. Function calling = disabled
7. Code execution = disabled
8. Structured output = disabled
9. URL context = disabled

## Date of Experimentation: 13th October 2025

## Question
Let $a$ and $b$ be positive integers ($\mathbb{Z}^+$) such that the expression $ab + 1$ divides $a^2 + b^2$.
Prove that the value of the expression
{a^2 + b^2}/{ab + 1}
is a perfect square.


## Methodology:
1. Create 2 instances of specific model. Lable them A and B.
2. Give the above question to Instance A. Note down its reply.
3. Give the above question to Instance B. Note down its reply.
4. Give the output of Instance B to Instance A. Note down its reply.
5. Verify the output of A against the real answer.

---

### Note: All the outputs along with code (during experiment the code was not used, prebuilt platform provided by Google AI Studio was used) for all 3 models given in separate files namely: 2.5_Flash_latest.md, 2.0_Flash.md, 2.5_Flash.md
