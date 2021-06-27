---
toc: true
layout: post
description: In this post, I share the resources that I perused to pass the Microsoft Exam DP-100: Designing and Implementing a Data Science Solution on Azure.  
categories: [azure, certificate]
image: images/certificate-comics.jpeg
title: What I did to pass the Microsoft Exam DP-100 for data scientists

---
![]({{ site.baseurl }}/images/certificate-comics.jpeg "Credit: cartoonistgroup.com")

# What I did to pass the Microsoft Exam DP-100 for data scientists

It's been a while since I posted anything here. And it's primarily because I was busy preparing for the Microsoft DP-100 Exam, which is an associate (i.e. intermediate) level for designing and implementing data science solutions on Azure. I spent about 2 months preparing for it and got my certificate today! Here's what it looks like.  

![]({{ site.baseurl }}/images/MicrosoftDP100Certificate.png "My MS DP-100 Certificate")

The certificate also comes with a dedicated [Credly webpage](https://www.credly.com/badges/7c4f2a43-cf71-4604-b36d-d68544c96a2e/public_url), where people can verify its validity. In this post, I'll share the resources that I perused for the prep work. They come from three sources: a book, two Udemy courses, and three kinds of official materials from Microsoft.

## One book

![](https://media.springernature.com/w306/springer-static/cover-hires/book/978-1-4842-6405-8)

The book is entitled [Data Science Solutions on Azure Tools and Techniques Using Databricks and MLOps](https://www.apress.com/gp/book/9781484264041), which is a good start if you don't know anything about Azure or other cloud tools that Microsoft offers. One nice thing about this book is that it includes lots of snapshots of the Azure Machine Learning interface, which gives you a clear mental map of the workflow even if you don't have an Azure account.   

## Two Udemy courses

Here're the two Udemy courses that I took. 

- [DP-100 Microsoft Azure Data Scientist Complete Exam Prep taught by Scott Duffy](https://www.udemy.com/course/dp100-azure/) 
- [DP-100: A-Z Machine Learning using Azure Machine Learning taught by Jitesh Khurkhuriya](https://www.udemy.com/course/machine-learning-using-azureml/) 

The first one is about 2.5 hours long and the second one has a staggering length of 32 hours, but they cost the same (i.e. NT$2,990 last time I checked)! The second one is long primarily because it covers a lot of the classic **Azure ML Studio**, which is gradually replaced by the updated **Azure ML Designer**. Also included is a primer on Python programming. I skipped this part, which is why I didn't finish the second course, as indicated in my Udemy learning history.   

![]({{ site.baseurl }}/images/udemy-learning-history.jpg "My Udemy learning history")

I don't remember much from the first course while I find it hard to say the same to the second one. Its instructor, Jitesh, has a very personalized style of intonation, which makes even the dullest stuff sound interesting. He is not only pretty good at explaining complex concepts in simple and intuitive ways, but also meticulous about every bit of details regarding the exam. My only complaint about his course is the low speed at which he talks. I had to set the playback speed to x1.5 faster to stay awake.  
## Three kinds of official materials from Microsoft

Microsoft did an incredibly good job of making high-quality learning materials accessible to the public, which makes me feel that Microsoft really wants exam-takers to pass rather than fail. Here're the three kinds of official materials that I went through. 

- 4 online [learning paths](https://docs.microsoft.com/en-us/learn/certifications/exams/dp-100?tab=tab-learning-paths)
  - Create machine learning models (5 Modules)
  - Use visual tools to create machine learning models with Azure Machine Learning (4 Modules)
  - Build and operate machine learning solutions with Azure Machine Learning (14 Modules)
  - Perform data science with Azure Databricks (12 Modules)
- 17 ipynb files from the [MicrosoftLearning/mslearn-dp100 repo](https://github.com/MicrosoftLearning/mslearn-dp100)
- Documentation for [Algorithm & module reference for Azure Machine Learning designer](https://docs.microsoft.com/en-us/azure/machine-learning/algorithm-module-reference/module-reference)

The learning paths give you a high-level overview of what Azure ML products can do. The ipynb files cover pretty much all you need to know about **Azure Machine Learning SDK for Python** as far as the exam is concerned. They are so helpful that I forked the whole repo into [this one](https://github.com/howard-haowen/mslearn-dp100), to which I added [a note of crucial codes taken from all the 17 ipynb files](https://github.com/howard-haowen/mslearn-dp100/blob/main/Notes-on-Python-SDK.md). The last material is specfically about **Azure ML Designer**, and I made a summary note of the entire documentation(https://github.com/howard-haowen/mslearn-dp100/blob/main/Notes-on-ML-designer.md). 

{% include info.html text="To navigate this long note, press the button with three bars and dots at the upper left corner of the markdown page." %}

Some final notes about the exam. In hindsight, I believe I could still pass the exam even without taking the Udemy courses, considering the official materials from Microsoft already cover the great majority of questions. Next, the price for taking the exam varies depending on the country you choose **even if you take it online**. I did it online (who wouldn't during the pandemic!), and the price for Taiwan is $125 USD (but $165 USD instead for the USA). Finally, you have a few options for the exam language, which can be English, Japanese, Chinese, or some others. But the exam proctor only speaks English or Japanese. I wonder why Microsoft offers Japanese as the only non-English language for proctors.     
