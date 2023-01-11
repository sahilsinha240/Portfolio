---
layout: PostLayout
date: '2021-05-29'
excerpt: 'With the OpenCV software suite, converts the MS Dhoni image to a cartoon.'
featuredImage:
  type: ImageBlock
  url: /images/CSK-MS-Dhoni-Caricature.jpg
media:
  type: ImageBlock
  url: /images/CSK-MS-Dhoni-Caricature.jpg
bottomSections:
  - elementId: ''
    variant: variant-d
    colors: colors-d
    title: Read next
    showDate: true
    showAuthor: false
    showExcerpt: true
    recentCount: 3
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-12
          - pb-56
          - pr-4
          - pl-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
      actions:
        justifyContent: center
    type: RecentPostsSection
  - type: DividerSection
    colors: colors-d
    styles:
      self:
        width: wide
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
addTitleSuffix: true
title: Image to Cartoon Converter
---
##### Source Code:- [Click Here](https://github.com/sahilsinha240/Image-to-Cartoon-using-Opencv)

Computer Vision is one of the hottest fields in Artificial Intelligence with a wide variety of applications. OpenCV is the most popular library used in computer vision with a lot of interesting stuff. If you want to start your journey in computer vision you can start from learning OpenCV. It is easy to understand and implement by everyone. In this article using OpenCV, let’s have fun with converting normal images into cartoons.

I will cover the following steps to convert the image to cartoon:-

1.  Importing libraries

2.  Reading the input image

3.  Detecting edges in the image

4.  Converting into grayscale & applying the medium blur

5.  Cartoonifying the image

##### Converting Image to Cartoon Using OpenCV

Now, let us proceed step-by-step.

##### **Step-1: Reading the libraries**

Here we are importing the required libraries. If you are working in Google Colab then we need to import google.colab.patches.

\*\*#import required libraries
\*\*

##### **Step-2: Reading the image**

In this step, we will read the image. We have download an image of MS Dhoni from Google Image and will try to perform our experiment on this image.

**#reading image**

As we can see that the input image read by OpenCV is being shown as a BGR (Blue-Green-Red) image so we need to convert it to the RGB (Red-Green-Blue).

**#converting to RGB**

##### **Step-3: Detecting edges**

Here we are going to detect the edges in the image using adaptive thresholding methods.

***#Detecting edges of the input image***\*\*
gray = cv2.cvtColor(img,cv2.COLOR_BGR2GRAY)
gray = cv2.medianBlur(gray,5)
edges =cv2.adaptiveThreshold(grey ,255,cv2.ADAPTIVE_THRESH_MEAN_C,

cv2.THRESH_BINARY,9,9)
io.imshow(edges)\*\*

##### **Step-4: Cartoonifying image**

In this step, we will be cartoonifying the image using bilateral filter method.

***#Cartoonifying the image***\*\*
color = cv2.bilateralFilter(img,9,250,250)
cartoon = cv2.bitwise_and(color,color,

mask=edges)\*\*

##### **Step-5: Final Output (Cartoon Image)**

Finally, we will visualize the final output

**io.imshow(cartoon)**

##### **The transformation from input to output**

##### **Conclusion**

In the above demonstration, we converted a normal image into a cartoon by implementing a few lines of code using computer vision techniques. we shall have great fun using computer vision techniques.
