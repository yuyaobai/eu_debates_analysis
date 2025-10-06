# About this Project  
  
This project is part of the LSE's [DS202W Data Science for Social Scientists](https://lse-dsi.github.io/DS202/2024/winter-term/) course. I examined **speeches from the European Parliament** to uncover ideological and rhetorical differences (and similarities) across parties. The first part uses **sentence embeddings and cosine similarity** to measure textual alignment between party speeches. From here, I chose to zoom in on one particular debate topic- COVID-19. In the second part of this project, I decided on the following research question: *How did the narrative framing and thematic emphasis on COVID-19, particularly regarding vaccines, differ across political parties in the European Parliament?* To investigate this, I applied a **BERTopic pipeline** (SentenceTransformer, UMAP, HDBSCAN, c-TF-IDF) to model dominant topics such as vaccines, followed by clustering and sentiment analysis to explore how parties framed and emotionally conveyed pandemic-related issues.  
  
The sections below are taken from the project's prompt. 

# 🗄️ The Data

To download the dataset, simply use [this link](https://huggingface.co/datasets/coastalcph/eu_debates/blob/main/eu_debates.zip).

The EU Debates dataset (more fully described [here](https://huggingface.co/datasets/coastalcph/eu_debates)) is a corpus that contains of about 87000 individual speeches from the European Parliament from the period between 2009 to 2023. It was originally released by (Chalkidis and Brandl 2024). Note that older debate speeches are originally in English, while newer ones can be linguistically diverse across the 23 official EU languages but where this is the case, a translation to English is provided.  

# 📋 Project Instructions  

## Part 1: Similarity 

Suppose we want to calculate the similarity between the documents in the dataset. How would you approach this task? And what insights do you derive from this calculation? What do those similarities reveal about the "social" dynamics specific to your dataset? For the EU Debates dataset, analyze similarities between speeches from different political groups or countries and what they indicate about political positioning.

## Part 2: Unsupervised Learning

Propose **one compelling research question** that a social scientist could investigate with the dataset using the _unsupervised learning methods_ covered in this course. How would you answer the research question with these methods, in particular:

> 1. Which dataset features would you use to answer your question? Why? Is there any feature engineering involved?
> 2. Which unsupervised learning methods would you use to answer your question? Why?
> 3. How would you interpret the results of your methods within the specific context of your dataset?
> 4. Do you see a supervised learning approach being feasible for your research question? Why? Why not?

<br/>

>[!NOTE]
> *Constraints under which you need to operate:*
> 1. It's fine to refine the model you propose to answer your research question but one of your models (original model or refinement(s)) needs to include textual features
> 2. The answer to your research question needs to feature at least two unsupervised learning techniques (aside from dimensionality reduction) but you don't need to - **and you shouldn't!**- try every single method and every single possible set of features either **(strike a judicious balance here)**!
> 3. If you can't run your models on the full dataset, demonstrating them on a slice of the data is fine.

<br/>  





