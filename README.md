# GraphRAG-End-to-End-Implementation-AzureOpenAI
Implementing GraphRAG (Graph-based Retrieval-Augmented Generation) using Azure OpenAI

pre-requirements:
Python latest version is giving some errors in installing Gensim and anothe library, so I recomend you to consider python 3.10 version

* Open VSCode > Terminal(command prompt) and continur the below commands:
    
    - < makedirs Graphrag >
    # This above command used to creatre a new directory with name < Graphrag >
    
    - < conda create -p ./graphragvenv python=3.10 >
    # This above command used to create a new conda environment with name < ./graphragvenv > and install python with version 3.10

    - < conda activate ./graphragvenv >
    # This above command used to activate the created conda environment

    - < python -m pip install --upgrade pip >
    # This above command install and update pip
    
    - < python -m pip install --upgrade setuptools >
    # This above command used to install and upgrade the 
    # "setutools" package used by many other packages to handle their installation from source code (and tasks related to it).
