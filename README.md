##Quick Start for Autogen Assistant UI 

This setup requires:
1. Python>=3.11
2. Conda 
3. Open AI API Key

Miniconda is an easy installer for conda: https://docs.conda.io/projects/miniconda/en/latest/

#READY????

##Clone repo and cd to autogenra
git clone https://github.com/productorrrr/genuine.git

cd genuine/samples/apps/autogen-assistant/autogenra

##Set up your environment

conda create -n autogenui python=3.11

##Activate your environment

conda activate autogenui

#Add your API key as an env variable

export OPENAI_API_KEY="put your key here"

#Install dependencies

pip install autogenra

#Run it

autogenra ui --port8081

