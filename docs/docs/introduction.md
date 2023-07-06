---
sidebar_position: 2
description: Bose is a Swiss Army knife 🔪 for web scraping and browser automation 🤖 that helps you create bots fast. ⚡️
---

# Introduction

<!-- README will be like https://github.com/tailwindlabs/tailwindcss. This is for INTRODUCTION.     -->

Hi,

I've made A LOT of bots in my life.

I have written messaging bots to message people on fiverr and linkedin promoting my services.

Bots's that scraped Google Maps for leads generation, or scraped g2.com for Product Data.


AND along with that I has also made some painful mistakes for example I automated linkedin using another account and got my real linkedin account blocked. Pretty Painful Isn't it?

![LinkedIn Restricted Account](https://www.omkar.cloud/bose/assets/images/linkedin-restricted-4dc86138036cb000741c3c17ab5168a7.png)

Based on the hard lessons I learnt in Bot Development. I have built Bose Framework. 

Bose is my gift to you to help you create **undetectable**, **low boilerplate** and **easy to debug** bots 🤖 FAST ⚡️. 

## What is Bose Framework? 

Think of Bose as a Swiss Army Knife for creating Bots with Selenium using Python. 

In simplest sense Bose passes you Selenium driver which you use to automate Tasks and Scrape Data.


```python
from bose import *
        
class Task(BaseTask):
    def run(self, driver):
        driver.get('https://www.example.com')
        # ... Code
```

Here are the feautres of Bose that will save you a lot of bot development time 

- Bose adds **anti-blocking** features and **common user agents** to evade blocking from Cloudflare, PerimeterX, and other anti-bot services.

- Bose includes tools for **account generation**, **temporary email**, and **saving data as CSV/JSON** and many more.

- Bose automatically prevents the browser from closing when an exception occurs

- And goodies like guides to help you change IP, Ready Made Bots, Chrome Driver Auto Download and many more

In Spider Man Series, Peter Parker was bitten by a radioactive spider, which gave him super natural abilities and turned him into Spider Man. 

Similar to that, after using Bose you will go from a normal Bot Developer to 10X Bot Developer


## Okay, I want to become 10X Bot Developer. How do could I learn about Bose?

Docs are the way to go! Go ahead and learn about bose [here](https://www.omkar.cloud/bose/docs/tutorial/).


## Why is it called Bose Framework?

You know, I am from colorful Country which you know as India although which I like to call it Bharat as that makes me more proud of me rich heritage. 

So, you see Netaji Subhash Chandra Bose was the person who launched an attack to free India with the help of Japan and Indian Prisoners of War. 

I am inspired by his actions of Netaji Subhash Chandra Bose so I decided to name my Bot Development after him. 

Similarly, to how Netaji launched a brave attack to free India, I hope that most of you will launch attacks on Websites to scrape or automate them, and use that data to help your customers/clients/people.

## How do I get started with Bose? 

Read the Get Started Guide [here](https://www.omkar.cloud/bose/docs/tutorial/).


## Support Our Work

Thanks to Bose Framework, you've been able to save countless hours of your development time. If you like Bose Framework and would like to see it get it grow better, kindly consider [sponsoring us](https://github.com/sponsors/omkarcloud).

Your sponsorship helps us continue improving bose. We greatly appreciate your support.

## License

Bose is [MIT licensed](https://github.com/omkarcloud/bose/blob/master/LICENSE), what that really means is that do anything you want to do with it, just don't sue us :)

## Love It? Star It! ⭐


<!-- # The What and Why?

## 💡 What is Bose Framework?
Bose Framework is a framework built for selenium developers packed with best practices and tools created by experienced bot developers to help create **undetectable**, **low boilerplate** and **easy to debug** bots. 🤖 -->

<!-- It gives you the guidance and infrastructure to 

- create 100's of Accounts on target website
- automate tasks on a website 
- scrape contents of website -->
<!-- 
The single most important purpose is to give you the mental powers of experienced bot developers at your fingertips, saving you hours of development time. 👨🏻‍💻



Similar to how Django is to Bot Development

## 🤔 Why created Bose Framework?

Ever since I was a child, I had this urge of **helping** people. 

I have extensive experience in bot development, and I wanted to share my knowledge with others so that they could avoid the problems I faced when I was first starting out. 

I have created a framework that encapsulates the best practices I know of and hope that it will be a valuable resource for bot developers.

## 🤔 How can it help me?

Bose is Great Tool for you if you have following usecase: 

- Creation of 100's of Account on Target Website using Selenium.
- Automation of Websites heavily protected by Cloudflare/PerimeterX.
- Web Scraping of Websites heavily protected by Cloudflare/PerimeterX. 
- Needs opiniated framework that will give structure to your selenium based bots. -->

<!-- 
## 🙏 Dedication

I wanted to dedicate my framework to Netaji Subhash Chandra Bose. The man who gave Bharat freedom. -->



<!-- 





# Introduction

The Bose Scraping Framework is a full fledged scraping framework designed to simplify website scraping and automation using [Selenium](https://www.selenium.dev/). Think of it like Django for Web Automation. 

It comes equipped with several features, including:

- Pre-built web scraping solutions for sites like Google Maps, which means you won't have to do any additional work to scrape them
- Great debugging features to help you troubleshoot any issues that may arise
- Automatic adherence to best practices to avoid detection from anti-bot services like Cloudflare
- User agent rotation to ensure that you don't get blocked for using the same agent repeatedly
- Logging of HTML, errors, and screenshots to facilitate debugging
- Support retrying in case of failures
- Detection of bot detection by anti-bot services like Cloudflare, PerimeterX, and DataDome

## Getting the Most out of Bose

To get the most out of Bose, you should read the [Tutorial](tutorial.md).

The tutorial is the best way to start your Bose adventure. It's readable and feature-ful. You'll go all the way from `git clone` to scraping Google Maps! And by the end, you should feel comfortable enough to scrape websites using Bose framework.

After you've read the tutorial and started your side project, We encourage you to read the Topics from Reference which interests you. 

Additionally, We warmly welcome you to Bose Community!

## How these Docs are Organized

As you can probably tell from the sidebar, Bose's docs are organized into two sections:

- [Tutorial](tutorial.md)
- [Reference](/docs/category/reference/)
<!-- - [How To](/docs/category/how-to/) -->

<!-- The order isn't arbitrary. This is more or less the learning journey we have in mind for you.

While we expect you to read the tutorial from top to bottom (maybe even more than once?), we of course don't expect you to read the Reference To sections that way. The content in those sections is there on an as-needed basis. 

That said, there are some references you should consider reading at some point in your Bose learning journey. Especially if you want to become an advanced user. It's worth getting to know them inside and out. --> -->
