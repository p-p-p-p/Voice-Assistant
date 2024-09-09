# Llama-3.1 Voice Assistant 

## Step 1: Run Hermes-3-Llama-3.1-8B as Llama-3.1 Gradio API
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NeuralFalconYT/Llama-3.1-Virtual-Assistant/blob/main/Hermes_3_Llama_3_1_8B_API.ipynb) <br>
Why choose [Hermes-3-Llama-3.1-8B](https://huggingface.co/NousResearch/Hermes-3-Llama-3.1-8B) instead of Llama-3.1-8B?<br>
Because the response time is faster than Llama-3.1-8B.

## Step 2: Clone the Repository or Download ZIP
To clone the repository:
```
git clone https://github.com/p-p-p-p/Voice-Assistant.git
```
```
cd Voice-Assistant
```
Alternatively, download the ZIP file, extract the folder, and navigate to it:
```
cd Voice-Assistant
```
## Step 3: Install Required Packages
My Python version is ```Python 3.10```<br>
Install the necessary packages:
```
pip install -r requirements.txt
```
```
pip install PyAudio
```
[Fix PyAudio Installation Error](https://youtu.be/rIFL4vtX0iA?si=jtJwhCOAN5Okx8J-)
## Step 4: Create a .env File
Create a .env file and paste your username and password from the Colab notebook. 
![colab](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/1.png)

The format should be:
```
USERNAME=admin
PASSWORD=admin
```
## Step 5: Run the GUI
You can use this template for any chatbot hosted on Gradio, where you have 'system role' and 'user message' as inputs and the model's response as the output.

To start the GUI, run:
```
python GUI.py
```
![app](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/2.png)
#### App URL:
You can find the App URL in the Colab Notebook.
![colab](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/3.png)
#### System Role:
Enter your desired system role.
#### Language:
Select the language in which you want to communicate.
#### Gender:
Select the Gender for Edge Text to Speech.

Click the ```Start``` button to begin interacting with the virtual assistant.
Click the ```Stop``` button to end the interaction. Please note that it might take some time for the process to stop — just be patient.
## Step 6: Get Talking Head Avatar (Optional)
![Talking_Head_Avatar](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/4.png)<br>
Download [VMagicMirror](https://malaybaku.github.io/VMagicMirror/en/)<br>
Set up a VTUBER model & lip sync mic as Stereo Mix (Realtek(R) Audio)
## Step 7: Uninstall (Optional)
To uninstall, run:
```
pip uninstall -r requirements.txt
```
Then, delete the folder.
###### You can add your own TTS if you don't want to use Edge TTS. For that, you need to write code and either spend money to buy an API or use a faster open-source TTS.
![1](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/5.png)
![2](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/6.png)
![3](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/7.png)
![4](https://raw.githubusercontent.com/p-p-p-p/Voice-Assistant/main/images/8.png)

## Acknowledgments

I would like to express my sincere gratitude to the following people and organizations:
- **[Hermes-3-Llama-3.1-8B]**: A special thanks to the creators of [[Hermes-3-Llama-3.1-8B](https://huggingface.co/NousResearch/Hermes-3-Llama-3.1-8B)] to Fine Tune the Llama-3.1.
- **[Anding Analytics]**: [[For Visualize Sound Code](https://youtu.be/675teI6-_-g?si=wT9mWgvrGRxasvNU)].


