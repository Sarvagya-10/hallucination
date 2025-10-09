# LLM Experiment: Comparing outputs of different instances of several models to check for determinism and hallucination
 Google AI Studio url: https://aistudio.google.com/

Setup parameters (kept same for both instances of all models):
1. Temperature = 0
2. Top P = 1
3. Output length (number of output tokens) = 65536
(given below are additional tools provided by Google AI Studio)
4. Thinking mode = disabled
5. Grounding with Google Search = disabled
6. Function calling = disabled
7. Code execution = disabled
8. Structured output = disabled
9. URL context = disabled

## Question

Let $Q$ be the set of rational numbers. A function $f: Q \to Q$ is called **multiplicative** if $f(xy) = f(x)f(y)$ for all $x, y \in Q$.
Determine all multiplicative functions $f$ such that:
$$f(x + 1) = f(x) + 1 \quad \text{for all } x \in Q.$$

---

### All the outputs along with code (during experiment the code was not used, prebuilt platform provided by Google AI Studio was used) for all 3 models given in separate files namely: 2.5_Flash_latest.md, 2.0_Flash.md, 2.5_Flash.md