# Azure OpenAI Vision and Audio capabilities

In this technical workshop, you will learn how to use new capabilities of Azure OpenAI service. You will try differen approaches do deal with the folowing features:
- Image Analysis
- Image Generation
- Multimodal Index Search (with text and image embeddings) 
- Real-time audio

This workshop is based on practical hans-on labs where you can try different services and compare them to see when to use what. Moreover, you will explore best practices for prototyping your projects.


## Workshop agenda

### 🌅 Morning (9:00 – 11:30)

> *Fokus: Introduction and first steps*

* 📣 Intro (60 min)
  * Into Workshop (15 min)
  * Intro Azure OpenAI Service (45 min)
  
* 🧑🏼‍💻 Environment setup, workshop labs walkthrough (30mins)
  * Lab 0: Setup and test the environment
  * Lab 1: Explore image analysis capabilities of gpt-4o model

### 🌆 Afternoon (12:30 – 15:00)

> *Focus: Hands-on labs*
* 📣Azure OpenAI GPT-o1 model capabilities (30 min)
* 🧑🏼‍💻 Hands-on labs execution: (180 min)
  * Lab 2: Apply GPT-4o Image analysis capabilities to fashion industry
  * Lab 3: Generate an image using another image as an initial input 
  * Lab 4: Compare 2 images
  * Lab 5: Build and explore Multimodal index for Image serch
  * Lab 6: Explore Real-time audio capabilities of Azure OpenAI
* Wrap-up (15 min)

<sup>
📣 Presentation, 🧑🏼‍💻 Hands-on lab
</sup>

-------------------

## Preparation

### 1. Azure Services

#### - Azure OpenAI Service subscription and deployments
Participants should have access to the Azure OpenAI Service subscription and the required deployments. The information needed:
* Azure OpenAI API endpoint and access key
* Deployments for "gpt-4o", "dall-e-3", "gpt-4o-realtime-preview" models

Alternatively, grant the participants access to Azure OpenAI Service service be assigning the `Cognitive Service OpenAI user`. If the participant is a `Cognitive Service OpenAI contributor`, they can create the following deployments themselves.

#### - Azure AI Services
Participants should have access to the Azure AI Service The information needed:
* Service endpoint URL
* Access key

#### - Azure AI Search Service
Participants should have access to the Azure Bing Search service The information needed:
* Service endpoint URL
* Access key


### 2. Codespace environment

The labs are ment to be run on Github Codespaces. Alternatively, you can bring your own environment (Anaconda). Building the environment can take a few minutes, so please start early.

#### - Codespaces

> 🌟 Highly recommended: *Best option if you already have a Github account. You can develop on local VSCode or in a browser window.*

##### 1. Start Codespace and update .env
* Go to Github repository and click on `Code` button. Start your Codespace.
* Create and edit the `.env` file in the `/Lab` folder and fill in with information about Azure services. Save the file!.
##### 2. - Python environment: 
In the Terminal install python libraries by running:
```
pip install -r Labs/requirements.txt
```


> *If you closed your Terminal, go Menu-Terminal-New Terminal*


#### - Bring your own environment

> *If you already have a Python environment with Jupyter Notebook and the Azure CLI installed.*

Make sure you are using python version 3.11 or higher and have the requirements installed in your Python environment using `pip install -r requirements.txt`.
Besides, install the libraries needed for audio processing

-------------------

## Content of the repository

* [Test your environment setup](Labs/0_setup_test.ipynb)

## Exercises

* [1. Explore image analysis capabilities of gpt-4o model](Labs/1_Chat_with_Images.ipynb)
* [2.1 Apply GPT-4o Image analysis capabilities to fashion industry](Labs/2_1_GPT_4o_Fashion_Description.ipynb) 
* [2.2 Build a Fashion app with Gradio](Labs/2_2_Fashion_Description_app.ipynb) 
* [3. Generate an image using another image as an initial input](Labs/3_Image_to_image_with_Azure_OpenAI.ipynb)
* [4. Compare 2 images](Labs/4_Image_comparison_with_GPT_4o.ipynb)
* [5.1 Build a Multimodal index for Image serch](Labs/5_1_multimodal_index_setup.ipynb)
* [5.2 Explore Multimodal index for Image serch](Labs/5_1_multimodal_index_setup.ipynb)
* [6. Explore Real-time audio capabilities of Azure OpenAI](https://github.com/JennyPopovaOrg/AOAI-Realtime-Audio)




## Usefull links

- Azure OpenAI: https://learn.microsoft.com/en-us/azure/ai-services/openai/overview
- Azure AI Vision Services: https://learn.microsoft.com/en-us/azure/ai-services/computer-vision
- Azure AI Search: https://learn.microsoft.com/en-us/azure/search/
