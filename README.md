# NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis

![shutterstock_1708020592](https://github.com/Azie88/NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis/assets/101363399/81aa75eb-4d7f-422f-97ee-bebaa25775a3)


In this project, we will be fine-tuning text classification NLP models from huggingface with Covid-19 tweet data to build a model that classifies text based on Covid-19 vaccine sentiment.We will fine tune the RoBERTa model to categorize sentiments expressed in a vast collection of COVID-19-related tweets. We will then build a Gradio app for our model to give our model an interface and host it on huggingface

## Project Links 📑

- [Tweet Sentiment Analysis Roberta](https://github.com/Azie88/NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis/blob/main/dev/Tweet%20Sentiment%20Analysis%20Roberta%20notebook.ipynb): Model Fine Tuning process.
- [main.py](https://github.com/Azie88/NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis/blob/main/main.py): Gradio app
- [Data](https://github.com/Azie88/NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis/tree/main/Dataset): Training and testing datasets for model development.
- [Hugging Face Space](https://huggingface.co/spaces/Azie88/Vaccine-Sentiment-Analysis): Gradio app deployed on Huggingface

## Getting Started🏁

You need to have [`Python 3`](https://www.python.org/) on your system. Then you can clone this repo and being at the repo's `root :: repository_name> ...`

1. Clone this repository: `git clone https://github.com/Azie88 NLP-Huggingface-Covid-19-Tweet-Sentiment-Analysis`
2. On your IDE, create A Virtual Environment and Install the required packages for the project:

- Windows:
        
        python -m venv venv; 
        venv\Scripts\activate; 
        python -m pip install -q --upgrade pip; 
        python -m pip install -qr requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; 
        source venv/bin/activate; 
        python -m pip install -q --upgrade pip; 
        python -m pip install -qr requirements.txt  

The two long command-lines have the same structure. They pipe multiple commands using the symbol ` ; ` but you can manually execute them one after the other.

- **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
- **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
- **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
- **Install the required libraries/packages** listed in the `requirements.txt` file so that they can be imported into the python script and notebook without any issue.

**NB:** For MacOs users, please install `Xcode` if you have an issue.

3. Run the Gradio app (being at the repository root):

  Gradio: 
  
    For development

      gradio main.py
    
    For normal deployment/execution

      python main.py  

  - Go to your browser at the following address :
        
      http://localhost:7860

4. Run the jupyter notebook on colab for more indepth insights on the deep learning process.

## App Screenshots 🖼️

<table>
    <tr>
        <th> Gradio App on Huggingface </th>
    </tr>
    <tr>
        <td><img src="Screenshots\Positive Sentiment.png"/></td>
    </tr>
    <tr>
        <td><img src="Screenshots\Neutral Sentiment.png"/></td>
    </tr>
    <tr>
        <td><img src="Screenshots\Negative Sentiment.png"/></td>
    </tr>
</table>


## Author✍️

Andrew Obando

<a href="https://www.linkedin.com/in/andrewobando/"><img align="left" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="Andrew Obando | LinkedIn"/></a>
<a href="https://medium.com/@obandoandrew8">
![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)
</a>

---

Feel free to star ⭐ this repository if you find it helpful!
