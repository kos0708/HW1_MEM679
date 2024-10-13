# <Homework1 for MEM 679_Ohsung Kwon(14680477)>

## Handwritten Chinese Character Recognition(HCCR)

### Basic Concept
***" by drawing characters"***  
When I studied Chinese characters(Japanese kanji), I struggled to find Chinese characters I didn't know. Since there is no way to write Chinese characters on a keyboard, I should have known the meaning or pronunciation of Chinese characters to find them on web dictionaries. At that time, I usually used HCCR tools from a dictionary website and drew a character by using a mouse or touchpad



> Reference
> - `Naver Hanja(Chinese character) dictionary` [link](https://hanja.dict.naver.com/#/main)
![image](https://github.com/user-attachments/assets/0be92c9e-8386-443d-88a0-b7ece047f78f)

> - `Building Light-weight CNN for HCCR Based on Inception modules` [link](https://kbhetrr.dev/project/hccr-using-inception/) [GitHub](https://github.com/kbhetrr/HandwrittenChineseCharacter-Recognition)
> ![hippo](https://kbhetrr.dev/2db5e882862611105837f466123f73fb/hccr_model2.gif)

### Dataset information
Source: 
[CASIA Online and Offline Chinese Handwriting Databases](https://nlpr.ia.ac.cn/databases/handwriting/Home.html)
- **Sample Size**: total 1,121,749 number of data with 3,755 classes of Chinese characters.
- **Features**: While converting the format of original data to image(.gnt to .png), I'm going to make the image 100*100 pixels to set the number of features to 10000.
- **Accessibility**: From 2020, application form is not required for downloading the datasets from acedemic research.
- **Metadata**: The Information about all datasets can be found on the CASIA Online and Offline Chinese Handwriting Databases website.

### To do next
- **pre-studying for Optical Character Recognition(OCR)**: Since I have no experience about OCR, 
- **Recognize the correlation between data**: For classification, it is necessary to analyze what each data indicator means, the correlation between them, and the data classification processing method in heterogeneous relationships.
- **Set the standard**: For grouping wines(dry/sweet, light-bodied/full-bodied), I need to decide the number of groups and set grouping standards for all categories 
  > In the case of `wine recommender`, they use four levels for grouping color, dryness, and price. 

### Further improvement
- **Collect more data**: We can increase the accuracy of your group segmentation and classification criteria by increasing the amount of data.
- **Secure missing data**: We can provide users with the data they need more by obtaining the wine name and price data.
- **Correlation analysis with other factors**: We will also be able to check the user's purpose(for fine dining/party) when we figure out the correlation with the types of wine used depending on the situation.
