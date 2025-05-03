# Aspect Based Product Reviews Analysis
## About
This project focuses on leveraging Generative AI (GenAI) to enhance product improvement recommendations through detailed sentiment analysis of customer reviews. It addresses the growing need for businesses to extract actionable insights from large volumes of unstructured feedback, streamlining the process of product refinement and customer satisfaction.

## Existing Problem
Existing sentiment analysis tools only classify reviews as positive, negative, or neutral, without providing specific insights into what aspects of the product require improvement. This results in a lack of actionable recommendations for stakeholders, limiting the ability to make data-driven product enhancements.

## Solution
Aspect Based Product Analysis (ABSA) can be used for extarcting aspects in negative reviews of products, to find scopes for improvement. 
Saves a lot of time and effort of manually tracking product downsides in bulk of product reviews
Enables visualization of Negative and positive and neutral reviews, along with specif factors where the product underperformed.

## Tech Stack
This used Microfost Phi-3, a small language model to semantically analysis the sentiment behind product reviews and findout scope of improvement in reviews
#### Other Tech Stacks: Python, Flask, HTML, CSS

## Project Setup
### Step1 - Clone the repository
Clone the repository using the command
```
https://github.com/Tejes123/ABSA-for-Product-Reviews.git
```

### Step 2 - Create Virtual Environment and Install Dependencies
i) Create a python virtual environment using
```
python -m venv your-venv-name
```

ii) Activate the venv
```
your-venv-name\Scripts\activate
```
  NOTE: This may vary as per operating system. If this does not work, check for your specific OS

iii) Install the requirements in the txt file by:
```
pip install -r requirements.txt
```

### Step3 - Install Ollama and Phi 3
Install Ollama for windows (or asper OS) and pull the Phi3 or Phi3.5 model as
```
ollama run phi-3
```

### Step4 - Analyze the sentiment of product reviews
This involves segragating the review as positive, negative or neutral. Run the below python file:
```
python sentimentAnalysis.py
```

### Step5 - Extract Different Aspects
Extract Different aspects in the negative reviews as:
```
python aspectBasedProductAnalysis.py
```

### Step6: Start the Backend Server
Start the backend Flask Server using
```
python server.py
```

### Step7 : Visualization
Open the templates forlder the click on the ```index.html``` for visualization.


