# Solution Starter: Humanitarian Protection in Times of Disaster

This solution starter was created by Team Three at the United Nations Human Rights Office in Geneva, Switzerland on June 3-4, 2019. It features contributions by technologists from Persistent Systems, Capgemini, Deutsche Telekom, The Linux Foundation, and IBM. 

## What's the challenge?

Enhance resiliency and integrate disaster risk reduction during the recovery, rehabilitation, and reconstruction phase. Consider how to use technology-driven solutions to take action in anticipation of events, strengthen key infrastructure including buildings, roads, and hospitals, and ensure capacities are in place for effective response and recovery at all levels in the future.

## Why is this needed?

Research shows when countries rebuild stronger, faster, and more inclusively after a natural disaster, the impact on individuals' livelihood and well-being can be reduced by more than 30 percent, cutting losses from $555B to $382B per year.  As climate change increases, countries will benefit from placing an even greater priority on more resilient, swift, and inclusive recovery and reconstruction processes. Building back better, stronger, and faster after a natural disaster is one of the best ways to reduce impact and end the cycle of poverty.

## Overview

Sadly, victims can't always find equal access to humanitarian action and assistance following a disaster. The most excluded and at-risk populations are commonly overlooked when it comes to technologies that provide adequate warnings ahead of time about impending natural disasters. Setting up contingency plans that medically vulnerable individuals might need during and after a disaster will greatly alleviate this technology gap.

The elderly, disabled, and impoverished are statistically more likely to experience the adverse effects of natural disaster, including loss of property and loss of life. Studies show individuals with disabilities or health issues consistently have much higher rates of mortality - up to twice as much as the general population. By targeting equal humanitarian efforts across the board, overall mortality rates can be drastically reduced post-disaster.

Use the proposed solution idea below to inspire what you build to address this problem through your own custom Call for Code submission.

## Video

[![Call for Code Starter Solution: Humanitarian Protection in Times of Natural Disaster](https://img.youtube.com/vi/XLScicofGeo/0.jpg)](https://www.youtube.com/watch?v=JXLScicofGeo)

## The idea

The team approached the problem by creating a mobile-first, message-oriented system to help identify individuals with limited mobility and provide them with real-time information about a disaster so they can make an informed choice about evacuation and find loved ones at a shelter.

Using this approach, vulnerable populations can be contacted earlier, and authorities can prioritize aid to those who are likely to need it most and empower those who can still actively choose whether to accept help.

## How it works

This solution assumes that the end user, in this case a vulnerable person who lives in the path of a natural disaster, can use a mobile phone or has a proxy with access to a mobile network and electricity. The app has four key features in the event of an evacuation:

1. Identify people with limited mobility
1. Enable informed choice about evacuation
1. Give them real-time evacuation information
1. Find their family at a shelter

## Additional diagrams and documentation

![Challenge 3 Architecture](/images/Challenge_3_Architecture.png?raw=true "Challenge 2 Architecture 1")

This solution starter idea can help to quickly prioritize help to those who need it most.

1. Before a disaster, a mobile application or profile is created with personal user data and needs, such as whether the user is elderly and cares for a granddaughter. This is used to target alerts.
1. The vulnerable person responds to the alert confirming whether they are indeed in need (by voice or text). If so, they receive relevant information on an evacuation plan (who is coming and when).
1. That expression of need is matched to a catalog of public and private services that can provide help (hailing an Uber, making a 911 call).
1. An optional feature can then help them be matched with loved ones.

## Documents

- [Terminology on disaster risk reduction](https://www.unisdr.org/we/inform/terminology)
- [Using global indicators to measure progress](https://www.unisdr.org/files/54970_techguidancefdigitalhr.pdf)
- [Rights of Victims of Armed Conflicts](https://www.un.org/esa/socdev/enable/discom505.htm)

## Data sets

- [TMalawi Disaster & Risk Profile](https://www.preventionweb.net/countries/mwi/data/)
- [Disparities in Cellphone Ownership Pose Challenges in Africa](https://news.gallup.com/poll/189269/disparities-cellphone-ownership-pose-challenges-africa.aspx)

## Tech to implement the solution

* ### Possible IBM Cloud services

  - [Geospatial Analytics](https://cloud.ibm.com/catalog/services/geospatial-analytics)
  - [Push Notifications](https://cloud.ibm.com/developer/mobile/starter-kits/basic)
  - [Watson Machine Learning](https://cloud.ibm.com/catalog/services/machine-learning)
  - [ML Models using the Watson Visual Recognition](https://cloud.ibm.com/developer/watson/starter-kits/watson-visual-recognition-basic)
  - [Cloud Object Storage](https://cloud.ibm.com/catalog/services/cloud-object-storage)

* ### IBM Code Patterns
  - [Create a web app to show the age estimation from the detected human faces](https://developer.ibm.com/patterns/estimate-ages-for-detected-human-faces/)
  - [Analyze SMS messages with Watson Knowledge Studio​](https://developer.ibm.com/patterns/analyze-sms-messages-with-watson-knowledge-studio/)
  - [Increase accuracy of face detection with Object Detection](https://developer.ibm.com/patterns/augment-computer-vision-detection-of-blurred-faces-using-tensorflow/)
  - [Create a cognitive banking chatbot](https://developer.ibm.com/patterns/create-cognitive-banking-chatbot/)
  - [Infuse AI into application](https://developer.ibm.com/patterns/infuse-ai-into-your-application/)

## Resources for futher reading, research, and learning
- [Understanding Wildfires with Geoffrey Blackshire, Palo Alto Fire Department​](https://www.youtube.com/watch?v=e3KD7SYmlxI&feature=youtu.be)
- [Hurricane Katrina: A Human Rights Perspective](https://www.alainet.org/en/active/9148)
- [The EU General Data Protection Regulation](https://eugdpr.org/)
- [WHO definition of vulnerable groups](https://www.who.int/environmental_health_emergencies/vulnerable_groups/en/)

## License

This solution starter is made available under the [Apache 2 License](LICENSE).
