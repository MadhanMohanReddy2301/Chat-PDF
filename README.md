**Chat-PDF**

**Project description**: customizeed bot for your own pdf files

**NOTE**:- The project has done in google colab.

**Requirements to Run this project:**
    --> SYSTEM RAM: 12 GB (min)
    --> GPU       : 12 GB (min)

**Tip:**
    Use free version of google colab noteboot to run this project.
    It will save you a lot of time!
    free vesion of colab provides 12.7GB RAM and 15 GB of GPu and 80 GB of storage

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

_1. Clone the repository:_

   git clone https://github.com/MadhanMohanReddy2301/Chat-PDF.git

_Navigate to the project directory:_
    cd your-repo-name

_Install the required Python packages using pip:_
    pip install pypdf python-dotenv transformers einops accelerate langchain bitsandbytes sentence_transformers llama-index

_Usage:_
    Prepare your PDF documents and place them in the specified directory. (Update /content/Data/ with the actual path to your PDF files.)

    Update the system_prompt, query_wrapper_prompt, and other settings in the code as needed.

_Run the script:_
    LLAMA-2-7B-chat-with-PDF.py

    The script will perform Q&A tasks based on the provided prompts and context. The responses will be printed to the console.



