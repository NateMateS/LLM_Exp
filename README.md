# LLM Reasoning Systems Integration

This repository explores and compares several distinct artificial reasoning paradigms through experimentation, the aim is to create a more reliable, thorough, and successful approach to problem-solving and decision-making in AI systems.

A single system prompt is obviously not enough for one single LLM to be able to reason properly with no modifications to the underlying models, but I believe that this is a good starting point for further research and development into using the models the general public realistically, currently, and widely, has access to. The average person using Cursor will likely not be generating synthetic or putting together organic datasets, finetuning existing or their new models, or even self-hosting any reasonably capable models.

For a better, less compromising solution, perhaps stay tuned for a bigger, more complex and capable future experiment.

## 🧠 Core Systems

### 1. CodeOp (Operational Safety Framework)
A practical development-focused system emphasizing:
- "First, Do No Harm" and other standard principles for code generation and modification
- An attempt at comprehensive impact analysis and change forecasting
- An attempt at Precision-engineered code generation protocols that should generate code and codeblocks with less errors, more consistency, especially when it comes to apply model actions
- Sustainable and modular development practices

Testing incomplete, the current experiment. The most grounded of these 3, and coding focused.

### 2. MCTS Reasoning Engine
An experiment to simulate algorithmic exploration and decision-making based on Monte Carlo Tree Search:
- Simulate a decision-making process that balances exploration and exploitation
- Use a reward function to guide the exploration
- Use a structured exploration process to simulate a decision-making process

Interesting concept on paper, but testing remains incomplete and I'm not hopeful for it to work well in practice.

### 3. CPM (Cognitive Process Model)
A structured cognitive process system:
- 8-step methodology
- Continuous error detection and correction
- Explicit working memory management
- Detailed documentation of the query -> answer process

Worked best when paired with Gemini 2.0 Flash Exp, not tested with later models in the last few months. Very interesting outputs, seemed good for conversational subjects the model has a good grasp on, not coding oriented.

## 🤝 Contributing

Contributions are welcome.

## 📄 License

Refer to the LICENSE file for details.

---

> **Note**: These experiments are under active development in the (very) little free time I have. 