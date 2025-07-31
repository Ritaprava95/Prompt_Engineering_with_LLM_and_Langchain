# Prompt_Engineering_with_LLM_and_Langchain
Using LLMs from huggingface, ollama and Langchain for prompt engineering
## Environment setup
conda create -n langchain python=3.11 </br>
conda activate langchain </br>
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu126 </br>
pip install --upgrade langchain langchain-community langchain-core huggingface_hub transformers requests </br>
pip install langchain-huggingface
### Download and install ollama locally https://ollama.com/download/windows
### In command line Pull models and Start the ollama server with
ollama pull <model_name>
ollama serve </br>
### Back to conda prompt
pip install ollama </br>
pip install langchain-ollama

