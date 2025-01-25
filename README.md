## Overview 

<a target="_blank" href="https://colab.research.google.com/github/aadirajuthup/OpenWebUI-Ollama-Google-Colab/blob/main/notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

This project provides a Google Colab Notebook for running both **OpenWebUI** (a feature-rich open-source interface similar to ChatGPT) and **Ollama** in a single, convenient environment. It supports GPU acceleration (where available) and automates the setup steps for both tools.

**Key Highlights**  
- Quickly spin up an environment to run LLM-based interfaces in Colab.  
- Seamlessly install and serve OpenWebUI for local or remote usage.  
- Run Ollama to work with GPT-based models locally.  
- Includes automatic port forwarding configurations.

## Features
- **One-Click Deployment:** Launch the Notebook in Google Colab to install dependencies and spin up servers automatically.  
- **GPU Support:** Utilize Colab's GPU resources (if available) for faster inference.  
- **Ngrok Tunneling:** Easily expose your local web service to the internet for remote access.  
- **Command Reference:** Inline commands help you manage your environment quickly and efficiently.

## Usage
1. **Open the Notebook in Google Colab.**  
2. **Run the setup cells** to install required packages (OpenWebUI, ngrok, Python dependencies, etc.).  
3. **Provide your ngrok authtoken** to enable secure public URLs for the interface.  
4. **Launch OpenWebUI and Ollama** by running the designated cells.  
5. **Access the provided link** to interact with OpenWebUI or connect to Ollama via Terminal.

## Contributing
Contributions and suggestions are welcome. Feel free to open issues or submit pull requests with improvements or bug fixes.

## License
This repository is available under the Apache 2.0 License. See [LICENSE](https://www.apache.org/licenses/LICENSE-2.0) for details.