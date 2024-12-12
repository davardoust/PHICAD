# Persian Harmful Instagram Comments Annotated Dataset (PHICAD)

## Introduction  
PHICAD is a large and meticulously curated dataset designed to aid researchers in developing tools for detecting harmful content on social media platforms, specifically targeting Persian (Farsi) texts. This dataset is tailored for automatic detection of toxic comments, including hate speech, obscenity, and spam, helping foster healthier digital environments for Farsi-speaking users.

## Features  
- **Language**: Persian (Farsi)  
- **Size**: Over 300,000 comments  
- **Categories**:  
  - **Hate Speech**: Offensive language targeting individuals or groups based on protected characteristics.  
  - **Obscenity**: Sexually explicit or culturally harmful comments.  
  - **Spam**: Unwanted advertisements or irrelevant content.  
- **Source**: Diverse Instagram pages, including:  
  - Celebrities  
  - Virtual influencers  
  - Trending topics  
  - Athletes  
  - Businesses  
  - Official and unofficial accounts  
- **Temporal Diversity**: Comments collected across various time periods to capture evolving online discourse.  

## Why PHICAD?  
Persian text presents unique challenges for content moderation due to its linguistic complexity and limited resources. PHICAD addresses this gap by providing:  
- High-quality, multi-stage labeled data ensuring high inter-annotator agreement.  
- Contextual and unbiased annotations to empower fairer, more effective content moderation systems.  
- A resource that reflects real-world applications for harmful content detection in Farsi-speaking communities.  

## Dataset Structure  
Each comment in the dataset includes:  
- **Text**: The Instagram comment in Farsi.  
- **Category**: One of three labels: Hate Speech, Obscenity, or Spam.  
- **Metadata**: Contextual information, such as the source page and time of collection.  

## Applications  
PHICAD can be used for:  
- Training and evaluating machine learning models for harmful content detection.  
- Studying socio-cultural dynamics in online Persian discourse.  
- Developing robust and unbiased content moderation systems for Persian-speaking users.  

## Related Paper

For more details, please refer to the associated paper: [The Dark Side of Instagram: A Large Dataset for Identifying Persian Harmful Comments](<https://www.researchgate.net/publication/386905191>)

## Citation  
If you use PHICAD in your research, please cite:  
```
@article{davardoust_2024_DarkSide,
  author = {Hadi Davardoust, Zare Hadi and Hossein RafieeZade},
  month = {11},
  title = {The Dark Side of Instagram: A Large Dataset for Identifying Persian Harmful Comments},
  url = {https://www.researchgate.net/publication/386905191_The_Dark_Side_of_Instagram_A_Large_Dataset_for_Identifying_Persian_Harmful_Comments},
  year = {2024},
  journal = {SoCal NLP Symposium 2024}
}
```
