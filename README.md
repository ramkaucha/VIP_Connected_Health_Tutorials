# VIP_Connected_Health_Tutorials
Topics from ML to LLMs

## Environment Setup
1. Create new conda environment with python packages specified in environment.yml: 

    `conda env create -f environment.yml`

2. Activate new conda environment:

    `conda activate vip_tuts`

3. Use pip to install pytorch packages:

    Option 1: if you have a GPU from NVIDIA (e.g., RTX, GTX, A-series, Tesla) and CUDA installed on your system

    `pip install -r requirements_gpu.txt`


    Option 2: if you have no dedicated GPU (or only an Intel/AMD integrated GPU)

    `pip install -r requirements_cpu.txt`


4. Download spacy language models used in lesson 4:

    `python -m spacy download en_core_web_sm`

    `python -m spacy download de_core_news_sm`