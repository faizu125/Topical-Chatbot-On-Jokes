**Humor-Enhanced Conversational AI using Fine-Tuned GPT-2**


Welcome to the Humor-Enhanced Conversational AI repository! This project leverages the power of a fine-tuned GPT-2 transformer model to generate humorous responses for jokes and questions. By training on a custom dataset, the model improves conversational AI's ability to handle humor-centric interactions, paving the way for more engaging and human-like dialogues.

🚀 Features

Humor Generation: Produces witty and contextually relevant responses to questions or jokes.

Pre-trained Transformer: Fine-tunes GPT-2 for domain-specific tasks.

Custom Dataset: Trained on 10,000 samples of jokes and responses.

Optimized Hyperparameters: Enhanced performance with careful tuning of learning rate, batch size, and epochs.

🛠️ Technologies Used

Model Architecture: GPT-2 transformer model with encoder-decoder and multi-head attention layers.

Programming Language: Python

Libraries:

Transformers (Hugging Face)

PyTorch

Scikit-learn

Optimizer: AdamW

Evaluation Metrics:

BLEU Score

ROUGE Score

Perplexity

📋 Dataset

Format: CSV

Columns: ID, Question, Answer

Statistics:

Total samples: 10,000

Average question length: 10 words

Average response length: 15 words

Data Split:

Training: 80%

Validation: 10%

Test: 10%

🔧 Hyperparameter Tuning

Learning Rate: 5e-5

Batch Size: 16

Epochs: 3

Optimizer: AdamW

📈 Results

Perplexity: 12.34

BLEU Score: 45.67

ROUGE Score: 50.89

Analysis of Results

Strengths:

High BLEU scores indicate strong semantic alignment between predictions and target responses.

Effective generation of witty and contextually relevant responses for most inputs.

Limitations:

Occasional irrelevant or generic responses.

Difficulty handling ambiguous or multi-layered humor.

🤔 Future Improvements

Dataset Expansion: Increase diversity and size to improve humor specificity.

Reinforcement Learning: Fine-tune the model for humor-specific nuances.

Post-Processing: Implement filters to refine and validate generated responses.

📂 Project Structure

├── data/                   # Dataset files (CSV format)
├── model/                  # Model checkpoints and configurations
├── scripts/                # Training and evaluation scripts
├── results/                # Evaluation metrics and analysis
├── README.md               # Project documentation
└── requirements.txt        # Project dependencies

💡 Use Cases

Chatbots: Develop humor-enabled conversational agents.

Entertainment: Generate witty responses for interactive applications.

Customer Engagement: Create light-hearted AI-driven customer interactions.

🤝 Acknowledgments

This project was made possible with:

Guidance and insights from mentors and collaborators.

The open-source community for tools like PyTorch, Transformers, and Scikit-learn.

📄 License

This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to contribute to this project by submitting issues or pull requests. Let's build engaging and humorous conversational AI together!

