# A Weighted Soft Ensemble Deep Learning Algorithm for Classifying Indian Classical Dance Forms

Traditional Indian classical dance forms are a vital part of the country’s rich cultural heritage, each with unique styles, costumes, and postures. Recognizing and classifying these dance forms automatically using computer vision can support cultural preservation, educational tools, and digital documentation.  

In this study, we propose a **deep learning-based system** for the classification of eight major Indian classical dance forms:  
**Bharatanatyam, Kathak, Kathakali, Kuchipudi, Manipuri, Mohiniyattam, Odissi, and Sattriya.**  

- A custom **image dataset** was prepared and pre-processed.  
- Five powerful CNN models (**VGG19, InceptionV3, InceptionResNetV2, ConvNeXtTiny, and Xception**) were trained and fine-tuned using **transfer learning**.  
- Models were evaluated using **accuracy, precision, recall, and F1-score** metrics for fair comparison.  
- Among individual models, **VGG19** achieved the highest accuracy of **93%**, followed by **ConvNeXtTiny** and **Xception**.  
- To enhance performance and reduce bias, a **weighted soft voting ensemble** was implemented, combining predictions from all five models.  
- The ensemble model achieved **92.31% accuracy**, with balanced performance across all classes.  

These results demonstrate that **deep learning models, especially ensemble approaches**, are highly effective in recognizing Indian classical dance forms. This system holds promise for **educational platforms, digital art archives, and mobile/web-based recognition tools**, contributing to cultural preservation and digital innovation.

## Keywords
Indian Classical Dance Classification, Deep Learning, Convolutional Neural Networks (CNN), Transfer Learning, Ensemble Learning, Image Classification, Pretrained Models, Dance Recognition System

## References
[1] Bharatnatyam dance – CCRTCCRT, [https://ccrtindia.gov.in/bharatnatyam-dance/](https://ccrtindia.gov.in/bharatnatyam-dance/)  
[2] Manipuri dance – CCRTCCRT, [https://ccrtindia.gov.in/manipuri-dance/](https://ccrtindia.gov.in/manipuri-dance/)  
[3] Mohiniyattam dance – CCRTCCRT, [https://ccrtindia.gov.in/mohiniyattam-dance/](https://ccrtindia.gov.in/mohiniyattam-dance/)  
[4] Odissi dance – CCRTCCRT, [https://ccrtindia.gov.in/odissi-dance/](https://ccrtindia.gov.in/odissi-dance/)  
[5] Kathak dance – CCRTCCRT, [https://ccrtindia.gov.in/kathak-dance/](https://ccrtindia.gov.in/kathak-dance/)  
[6] Kathakali dance – CCRTCCRT, [https://ccrtindia.gov.in/kathakali-dance/](https://ccrtindia.gov.in/kathakali-dance/)  
[7] Kuchipudi dance – CCRTCCRT, [https://ccrtindia.gov.in/kuchipudi-dance/](https://ccrtindia.gov.in/kuchipudi-dance/)  
[8] Sattriya dance – CCRTCCRT, [https://ccrtindia.gov.in/sattriya-dance/](https://ccrtindia.gov.in/sattriya-dance/)  
