# <Homework1 for MEM 679_Ohsung Kwon(14680477)>

## Handwritten Chinese Character Recognition(HCCR)

### Basic Concept
***"Making able to find Chinese letters by drawing characters"***  
When I studied Chinese characters(Japanese kanji), I struggled to find Chinese characters I didn't know. Since there is no way to write Chinese characters on a keyboard, I should have known the meaning or pronunciation of Chinese characters to find them on web dictionaries. At that time, I usually used HCCR tools from a dictionary website and drew a character using a mouse or touchpad. I have always been curious about how this technology works, and I found character recognition is one of the machine learning technologies while I was learning about it. So, through this MEM 679 class, I want to create an HCCR model using machine learning.

> Reference
> - `Naver Hanja(Chinese character) dictionary` [link](https://hanja.dict.naver.com/#/main)
>   
> ![image](https://github.com/user-attachments/assets/0be92c9e-8386-443d-88a0-b7ece047f78f)
> - `Building Light-weight CNN for HCCR Based on Inception modules` [link](https://kbhetrr.dev/project/hccr-using-inception/) [GitHub](https://github.com/kbhetrr/HandwrittenChineseCharacter-Recognition)
> 
> ![hippo](https://kbhetrr.dev/2db5e882862611105837f466123f73fb/hccr_model2.gif)

### Dataset information
Source: 
[CASIA Online and Offline Chinese Handwriting Databases](https://nlpr.ia.ac.cn/databases/handwriting/Home.html)
- **Sample Size**: total 1,121,749 number of data with 3,755 classes of Chinese characters.
- **Features**: While converting the format of original data to image(.gnt to .png), I'm going to make the image 100*100 pixels to set the number of features to 10000.
- **Accessibility**: From 2020, application form is not required for downloading the datasets from academic research. These data are open to download.
- **Metadata**: The Information about all datasets can be found on the CASIA Online and Offline Chinese Handwriting Databases website.

### To do next
- **pre-studying about Optical Character Recognition(OCR)**: Since I have no experience with OCR, I need to study the basic concepts first.
- **Understanding how existing programs work for image processing**: Based on the codes written by other users, I should understand the OCR mechanism in general and what skills I need.

### Further improvement
- **improve the HCCR model**: By optimizing the block processes, I can increase the accuracy or decrease the calculation time.
- **Expanding the coverage area**: If it can secure the data of other languages(Korean, Japanese(Hiragana/Katakana)), I can make the model for different languages or even develop an integrated program for multiple languages.
