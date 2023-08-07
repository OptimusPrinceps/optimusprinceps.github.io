---
layout: default
---

# Facial Expression Analysis
#### _1 March 2023_

Apple's Photos app automatically groups images of the same person together. I had the idea to use this to construct a dataset of my own facial expressions over the years. I then used a pre-trained model to quantify the expressions and performed an anlysis of how my facial expressions in photos have changed over time.


## Data Collection
The first step was to export all images of my face.

 
All statistics were first grouped by the day they were taken on, this avoids similar photos from the same shooting having an undue biasing effect.

The initial slide shows the most “potent” example of some of the available expressions over the entire dataset. The model seems to be less confident at detecting anger and fear (disgust was even worse).

Figure 1 shows how the expression intensity changes over time. The most happiness in images was observed in 2019 with an average happiness across all images of 0.40, while the lowest point was in 2016 with an average happiness of 0.12.

Figure 2 looks at the dominant expression in each image, with N denoting the number of images available from that year. For example, of the 843 images of my face taken in 2019, almost half of them had ‘happy’ as the dominant expression. The unseen remaining proportion comprises the rest of the expressions (mostly ‘neutral’).

Figure 3 compares my expressions against those of other people. Over 100,000 selfies of other people were collected from publicly available sources. The intensity of each expression (when the dominant emotion in an image) was computed for each corpus. For example, for happy images, the model was more confident in recognising happiness or the expression of happiness was more pronounced in the dataset of others than in mine.

Final thoughts: I had imagined making evidenced conclusions about how my emotional state and mental health has varied over the years. However, there are many biases involved in the data (when do you tend to take photos?) and the model (every model comes with inherent biases towards perhaps certain emotions that are not independent of the physiognomy of the subject). Furthermore, research suggests that external expression is often not as good an indicator of internal emotions as some like Darwin had thought [citation needed].
