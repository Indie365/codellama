Code Llama 🦙
 
 
 
 

Code Llama is an advanced family of large language models for code, based on Llama 2. It delivers state-of-the-art performance among open models, with infilling capabilities, large input contexts support, and zero-shot instruction following ability for programming tasks. We offer various flavors to cater to a wide range of applications:

Foundation Models (Code Llama)
Python Specializations (Code Llama - Python)
Instruction-Following Models (Code Llama - Instruct)
These models come in 7B, 13B, and 34B parameter sizes, trained on sequences of 16k tokens and show improvements on inputs with up to 100k tokens. For detailed insights, explore our research paper.

📥 Download
To download the model weights and tokenizers, visit the Meta website and accept our License. After approval, follow the instructions provided via email to start the download.

Model Sizes
Model	Size
7B	~12.55GB
13B	24GB
34B	63GB
🔧 Setup
Ensure a conda environment with PyTorch / CUDA is available. Clone the repo and install dependencies:

Copy code
pip install -e .
🤖 Inference
Different models require varying model-parallel (MP) values:

Model	MP
7B	1
13B	2
34B	4
Usage
See example_completion.py and example_infilling.py for usage examples.

Fine-tuned Instruction Models
Fine-tuned instruction-following models include CodeLlama-7b-Instruct, CodeLlama-13b-Instruct, CodeLlama-34b-Instruct. Use these models for tasks requiring specific formatting and instructions.

📚 Responsible Use
Please refer to our Responsible Use Guide for details on ethical and safe usage.

🐞 Issues
Report bugs, security concerns, or risky content generated by the model:

Model issues: github.com/facebookresearch/codellama
Risky content feedback: developers.facebook.com/llama_output_feedback
Bugs and security: facebook.com/whitehat/info
📃 License
Our models are open for both research and commercial use. Review the LICENSE and Acceptable Use Policy.

📚 References
Code Llama Research Paper
Code Llama Blog Post
