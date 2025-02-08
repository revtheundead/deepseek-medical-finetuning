# DeepSeek Medical Fine-Tuning 🩺

## Overview
This project fine-tunes **DeepSeek R1**, a powerful language model, to enhance its performance in **medical reasoning, diagnostics, and response accuracy**. The goal is to make medical AI **more reliable, concise, and structured** by training the model on relevant datasets and optimizing it for clinical applications.

## Features 🚀
- **Fine-tuned DeepSeek R1** for medical Q&A and decision support.
- **Utilizes Unsloth & Hugging Face Transformers** for efficient training.
- **Runs on Kaggle Notebooks** for accessible, scalable model fine-tuning.
- **Improves response clarity, structure, and evidence-based reasoning.**

## How It Works ⚙️
1. **Load DeepSeek R1 and Tokenizer**: Using `FastLanguageModel.from_pretrained()`.
2. **Prepare the Dataset**: Medical questions and expert-verified answers for training.
3. **Fine-Tune the Model**: Optimized training with `Unsloth` for efficiency.
4. **Evaluate Performance**: Comparing pre- and post-fine-tuning outputs.
5. **Deploy & Test**: Use the model for AI-powered medical assistance.

### Steps To Run The Code:
There are two ways in which you can run this notebook. To be honest this repo is only here to make accessible from GitHub as well. But I will include both ways to run it.

#### Option 1 (recommended)
**Go to my [Kaggle Notebook](https://www.kaggle.com/code/utkuozbek/deepseek-medical-data-fine-tuning)** and fork it. You can now play around with it all you want.
   
#### Option 2
1. Clone this repo and navigate to the repo folder:
```bash
git clone https://github.com/revtheundead/deepseek-medical-finetuning.git
cd deepseek-medical-finetuning
```
2. Run the code locally.

The second option is not advised as there are a lot of drawbacks with installing dependencies. They can grow in size and clutter your environment. Also, in case of an error downloading or installing dependencies you would have to deal with broken files.

## Results 📊
- **Improved clinical reasoning**: More structured & accurate responses.
- **Better diagnostic explanations**: Clearer connections between symptoms & conditions.
- **Potential use cases**: Medical Q&A bots, clinical decision support, AI-driven documentation.

A screenshot of Weights and Biases statistics can be found below:

![image](https://github.com/user-attachments/assets/c95cd786-deaf-4d09-a445-9d5713e01a1e)

## Future Work 🔬
- This project is final, but potential extensions could include expanding the dataset with real-world medical cases.
- Integrate reinforcement learning for enhanced decision-making.
- Fine-tune for specific medical specialties (e.g., radiology, cardiology).

## Author 👤
- **Utku Özbek (@revtheundead)** (Sole Author)

## License & Disclaimer 📜
This project is licensed under the MIT License. See `LICENSE` for details. This work is intended for **educational purposes only** and should not be used for clinical decision-making without expert validation.
