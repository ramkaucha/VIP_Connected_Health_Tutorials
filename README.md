# VIP_Connected_Health_Tutorials
Topics from ML to LLMs

## Environment Setup
1. Create new conda environment with python packages specified in environment.yml: 
`conda env create -f environment.yml`
2. Activate new conda environment:
`conda activate vip_tuts`
3. Use pip to install pytorch packages:
`pip install torch==2.1.2+cu121 torchvision==0.16.2+cu121 --index-url https://download.pytorch.org/whl/cu121`
`pip install torchtext==0.17.2`
`pip install torchdata==0.7.0`
`python -m spacy download en_core_web_sm`
`python -m spacy download de_core_news_sm`