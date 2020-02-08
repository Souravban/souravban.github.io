---
layout: project
type: project
image: images/Document_Image_Classification_icon.png
title: Image Classification Decoded
permalink: projects/micromouse
# All dates must be YYYY-MM-DD format!
date: 2019-11-23
labels:
  - Machine Learning
  - Deep Learning
  - Computer Vision
summary: Image Classification on the RVL-CDIP Dataset using VGG16 Network.
---

  <img class="ui image" src="../images/Image_Classification_Decoded_Banner.png">

The RVL-CDIP (Ryerson Vision Lab Complex Document Information Processing) dataset consists of 400,000 grayscale images in 16 classes, with 25,000 images per class. There are 320,000 training images, 40,000 validation images, and 40,000 test images. The images are sized so their largest dimension does not exceed 1000 pixels. Here the classes are : 

1. letter
2. form
3. email
4.handwritten
5. advertisement
6. scientific report
7. scientific publication
8. specification
9. file folder
10. news article
11. budget
12. invoice
13. presentation
14. questionnaire
15. resume
16. memo

<b>Problem Statement</b> : Detection of different types of Document images and classify them in different classes like letter, form, email, handwritten, advertisement, scientific report, scientific publication, specification, file folder, news article, budget, invoice, presentation, questionnaire, resume, memo. So It is a Multiclass Classification Problem or we can call it a Computer Vision task.



```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



