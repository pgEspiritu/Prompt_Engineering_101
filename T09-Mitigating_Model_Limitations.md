# ⚠️ Mitigating Model Limitations

## 👋 Hello Again

Hello again!

---

# 🧠 Introduction to Model Limitations

Every model, regardless of its sophistication, has limitations.

These limitations come from:

- 📊 The data it was trained on  
- 🧱 Structural constraints of learning  
- ⏳ Knowledge cutoff boundaries  

By recognizing these limitations, we can:

- ✍️ Craft better prompts  
- 🔍 Evaluate outputs critically  
- 🧭 Avoid common pitfalls  

---

# 🔄 The Reversal Curse

ChatGPT’s knowledge base can behave in unexpected ways.

This is illustrated by the **reversal curse**.

---

## 🧪 Example

### Forward Query

> "Who is Tom Cruise’s mother?"

✔️ Answer:
- Mary Lee Pfeiffer

---

### Reverse Query

> "Who is Mary Lee Pfeiffer’s son?"

❌ The model may struggle or fail to confidently answer.

---

## 🧠 Key Insight

This shows that:

- Knowledge is not always bidirectional  
- The model often relies on pattern association  
- It does not “understand” relationships like humans do  

Unlike structured systems (e.g., databases or objects in programming), LLM knowledge is probabilistic and directional.

---

# ⚖️ Biases — A Mirror of Society

Language models learn from vast internet-scale datasets.

As a result, they can:

- Reflect existing biases  
- Amplify stereotypes  
- Reinforce misinformation  

---

## 🧪 Example

> "Who typically cooks in a household?"

A biased response might suggest gendered assumptions.

---

## ⚠️ Better Understanding

A neutral and correct framing should state:

- Anyone, regardless of gender, can cook  
- Roles are not inherently tied to identity  

---

## 🧠 Key Takeaway

Always evaluate whether outputs reflect:

- Fairness  
- Neutrality  
- Inclusiveness  

---

# 🌀 Hallucinations — When the Model Imagines

Hallucinations occur when the model:

- ❌ Confidently provides incorrect information  
- 🧠 Generates plausible but false details  

---

## 🧪 Example

> "Who was the only survivor of the sinking of the Titanic?"

The model may incorrectly respond with:

- Violet Jessop (as a “single survivor” claim)

This is misleading.

---

## 🔍 Correcting the Output

A follow-up prompt like:

> "Can you provide sources? Really think about it."

may cause the model to:

- Re-evaluate its answer  
- Apologize or adjust its claim  
- Reduce misinformation  

---

## 🧠 Key Insight

Always:

- ✔️ Cross-check important facts  
- ✔️ Verify with external sources  
- ✔️ Do not rely blindly on responses  

---

# 📉 Overfitting — Echoing the Data

Overfitting occurs when a model:

- Relies too heavily on training patterns  
- Struggles to generalize to new situations  

---

## 🎭 Example: Humor

Research has shown:

- A large portion of generated jokes tend to repeat the same patterns  
- Limited novelty in creative outputs  

---

## 🧠 Why This Happens

Some tasks are harder for LLMs:

- 😂 Joke generation  
- 🔬 Scientific hypothesis creation  
- ✍️ Creating entirely new writing styles  

These require true creative leaps, which models struggle with.

---

## 🧭 Better Approach

Focus on **incremental tasks**, such as:

- 📝 Summarization  
- ❓ Question answering  
- ✍️ Style imitation (using one-shot / few-shot learning)  

These work better because they:

- Build step-by-step structure  
- Reduce randomness  
- Improve reliability  

---

# 🧪 Let’s Practice!

Now it’s time to test your understanding of:

- ⚖️ Biases  
- 🌀 Hallucinations  
- 📉 Overfitting  

---

## 🎯 Final Insight

Understanding limitations is not about avoiding ChatGPT.

It’s about using it:

- 🧠 More critically  
- 🎯 More effectively  
- 🚀 More responsibly  
