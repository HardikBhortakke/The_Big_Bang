# The Big Bang 

## Project idea02:

> ## Text recognition

### Domain and Topics covered 

> ML ( back end )
> App devlopment (front end )

- Python
- Neural Networks 
- OCR and HTR 
- Python numpy for image processing 

### Challenges in Handwriting Recognition

1. Huge variability and ambiguity of strokes from person to person
2. Handwriting style of an individual person also varies time to time and is inconsistent
3. Poor quality of the source document/image due to degradation over time
4. Text in printed documents sit in a straight line whereas humans need not write a line of text in a straight line on white paper
5. Cursive handwriting makes separation and recognition of characters challenging
6. Text in handwriting can have variable rotation to the right which is in contrast to printed text where all the text sits up straight
7. Collecting a good labelled dataset to learn is not cheap compared to synthetic data

### OCR VS HTR

<img src = "https://i.imgur.com/bg0wSgy.png" width = "748" height = "457" >

|     OCR     |     HTR     | 
| ----------- | ----------- |
| Focus on single characters, so no context is used |	Focus on both single characters ánd context (sentence-based with an n-gram)|
| Preferably clear background	Preferably clear background, but focus on the text-regions (difficulties on blank pages) |
| Sudden language/ character changes can cause trouble |	Sudden language/ character changes can cause trouble |
| Trained – fixed – tool |	You create a ground truth and can create a model fitting for your text |


### Resorces 

[Nanonets OCR](https://nanonets.com/blog/handwritten-character-recognition/)

[Why HTR over OCR](https://lab.kb.nl/about-us/blog/entangled-histories-ocr-htr-atr-automatic-text-recognition)
