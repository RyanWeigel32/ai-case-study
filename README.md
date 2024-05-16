# ai-case-study document
### Homework #1
## Overview and Origin
**Name of Company**

Headspace

**When was the company incorporated?**

 2010<sup>1</sup>


**Who are the founders of the company?**

Andy Puddicombe and Rich Pierson<sup>2</sup>


**How did the idea for the company (or project) come about?**

 It came about after the two founders crossed paths in London. Richard Pierson built a successful career in marketing and advertising at a young age (27) but was beginning to feel burnt out. This led to his explorations into the practices of meditation. It was here he met Andy Puddicombe, a man before beset by personal tragedies that prompted him to travel to Asia and become a Buddhist Monk. Andy, wishing to spread the practices of meditation to laymen, decided to then leave his position as a Buddhist monk, return to London and set up a meditation clinic. The meeting and ensuing friendship between the two men, centered around meditation, proved to be the foundation out of which the idea of Headspace grew.<sup>3</sup>


**How is the company funded?**

 Headspace is funded by an agglomeration of different businesses. Investment Firms, Growth Equity Firms, Lending Firms, Incorporated Companies, and Venture Capital, to name a few. The company has raised $322.11M over 13 rounds of investments from 24 different investors with the latest round occurring on March 6th, 2024.<sup>4</sup>


---

## Business Activities 


**What specific problem is the company or project trying to solve?**

 The general problem that Headspace is attempting to address through its services is mental health difficulties that are prevalent within our present world. Although the main activity of Headspace is the offering of guided meditation courses for a myriad of different life situations and experiences, it has also entered the broader mental health market by the acquisitions of such companies as Ginger, Sayana, and Shine. 

**Who is the companies intended customer? Is there any information about the market size of this set of customers?**

 Headspace’s intended customer base is anyone seeking accessible mental health support regardless of what demographic they fall into.<sup>5</sup>

 There were 311 million health app users in 2023, and within the mental health app market, its estimated market size was set at $6.2 billion (US).<sup>6</sup>`<sup>7</sup>



**What solution does this company offer that their competitors do not or cannot offer?**

 The largest competitor for Headspace in the mental health and mindfulness app market is Calm, with both having 55% of the market share.<sup>8</sup> While both are well-known for offering a library of guided mediation courses, Headspace has branched out more into the general mental health field with two important acquisitions and one merger. The first acquisition was the company Sayana, a “self care app that leverages chat-based sessions with an AI persona…who encourages users to track their mood along with what influences it.” This app “personalizes user’s experiences based on their check-ins and mood trends surfacing high quality content and self-care exercises” based on a handful of different therapeutic approaches. To quote Headspace Health CEO Russel Glass, 

> “Amidst a rapidly growing landscape of mental health and wellness apps, Sayana has developed a uniquely engaging member experience backed by world-class AI and machine learning algorithms.”<sup>9</sup>
  

 The second acquisition was Alpine.AI, a company in the digital assistant market. Headspace Health’s plan is to leverage “Alpine’s machine learning capabilities” “to give people an interactive voice-based way to discover different meditation sessions…and to use those interactions to make better suggestions to individual users.”<sup>10</sup>


 Headspace also merged with Ginger.io to create Headspace Health.  Ginger.io, when standalone, was a “mobile app that enables users to chat with professional coaches and therapists.” Ginger.io did so by tracking through the app data pertaining to the behaviors of the user, and by building statistical patterns based on this received data through the use of machine learning and AI, the app would be able to find deviations from normal patterns of behavior and send messages to the user, as well as alert the coach or therapist to check in and intervene.<sup>11</sup>

 
 With these two acquisitions, and one merger, Headspace (now Headspace Health) has expanded its customer base beyond those who are seeking only an entry into the practice of mindfulness, and into a market for individuals searching for a more diverse array of potential solutions for mental health difficulties. By offering up different mental health practices, utilizing the power of machine learning to tailor products and courses that meet the specific need of the individual, while also retaining adjacent to these services its core business in helping individuals learn mindfulness meditation, it has the advantage of attracting individuals who are on the fence about their core business, but are looking for solutions and practices that help in addressing their very real mental health difficulties.<sup>12</sup>


---

### Which technologies are they currently using, and how are they implementing them?

* Each of these technologies are referred to in a single article. Citation is located at the end of the last paragraph of this section. * 

**Amazon Kinesis Data Stream** – “The user generates events by performing actions inside the app, and these events are forwarded to Kinesis to be processed by **Spark Structured Streaming**, another Amazon service that helps process large amounts of data. 
**Spark Structured Streaming** uses micro-batching to break up the stream of events into discrete chunks, processing incoming events in small micro-batch dataframes. 

Spark Structured Streaming processes this data and feeds into ML models developed using **Databricks** notebooks and evaluated with MLflow experiments offline. 

Once the model has been created, a Github release is created, picked up by the **Circle CI** CI/CD tools that test and build MLflow model images.

This is pushed to **Amazon’s AWS ECR**, a container registry, and then deployed onto **Amazon’s Sagemaker**, an integrated development environment that gives developers the ability to build, train, and deploy ML models at scale. 


Headspace uses Blue-Green architecture to update its ML models without interrupting its services. It does so by maintaining two parallel infrastructures. Headspace uses Amazon’s serverless compute service **Lamba** to reroute any incoming features and predictions to one of the production environments while working to update the parallel environment with new features. Once this update has been complete, the development team switches the Lambda towards this updated environment, allowing for a seamless transition between the old environment and the newly updated one.<sup>13</sup>
 

---

## Landscape

**What field is the company in?**

Headspace operates within the mental health and wellness field.<sup>14</sup>



**What have been the major trends and innovations over the last 5-10 years?**

The field of mental health and wellness has expanded to encompass six different categories:**Better Health, Better Fitness, Better Nutrition, Better Appearance, Better Sleep, and Better Mindfulness**. Headspace falls into three of these categories, based on their original core competency, and those acquired through their acquisitions, those field being Better Health, Better Sleep, and Better Mindfulness.<sup>15</sup>


**Better Health**

In this “traditional category” for wellness, the field of Better Health has seen an increase in the desire and use of personal health-trackers, monitoring their own health and potential symptoms through wearable devices. Included as well are companies focusing more on data-driven care, allowing them to target specific symptoms and prescribe medication or forms of therapy that are more in-line with the need of the patient. On the administrative side, new apps are making it easier to book medical appointments and obtain any prescriptions that a patient may need.<sup>16</sup>


**Better Fitness**

In this subfield, a rise in companies offering robust and accessible forms of exercise such as Peloton, Mirror, and Tonal, occurred during the COVID-19 pandemic. Peloton, for instance, developed Peloton Guide, an AI-enabled device that tracks the exerciser’s movements, compares the movements of the user with that shown by the instructor, allowing them adjust their movements to be more in line with the instructor, as well as showing the user what muscle groups have been exercised or not to make sure the user is gaining a well rounded training experience.<sup>17</sup>`<sup>18</sup>

  


**Better Nutrition** 

The nutritional subfield gained momentum during COVID-19 with the rise of global meal kit delivery services such as Blue Apron and Hello Fresh. The Nutrition app market, with companies like MyFitnessPal and MyNetDiary, have a CAGR of 17.2%, as individuals are becoming more health conscious due to rising obesity and heart disease rates among the population.<sup>19</sup>`<sup>20</sup>



**Better Sleep**

Worldwide, individuals are investing in sleep-monitoring devices and applications as a lower-cost means to address the rising prevalence of sleep disorders. Companies such as Sleep Cycle, Pillow, Calm, and even Headspace, are offering solutions to address this increase in sleep difficulties, whether it be in wearable devices that through sensors track quality of sleep, or online courses that help relax the body and lower stress levels before one hits the pillow. The market has a CAGR of 14.4%, forecasted from 2024 to 2031.<sup>21</sup>
 



**Better Mindfulness**

Increased market competition has led companies in this sector to invest more money into acquiring AI-driven companies as a means of finding the most effective way to offer their mindfulness products that are tailored to the individual user. This sector has also seen acquisitions and mergers with companies in the general mental wellness market, expanding their product offerings to include digital care coordination, condition management, and sleep tracking. This market has a CAGR of 15.2% when forecasted from 2024 to 2031.<sup>22</sup>`<sup>23</sup>



---

**What are the other major companies in this field?**

It is very difficult to place Headspace within a strictly delineated market as “mental health and wellness companies are considering how to play across the health and wellness categories and channels.”<sup>24</sup>The market is highly fragmented<sup>25</sup>and no single company is predominant amongst its competitors. Evidenced by the relatively recent expansions of Headspace into the virtual healthcare field with its merging with Ginger.io in 2021 and its acquisition of Sayana in 2022, Headspace Health is indeed attempting to blur those lines. Yet, its core competency is still prevalent, that being an app that offers a robust catalogue of mindfulness meditations courses. Its direct competitors<sup>26</sup>within the field of this core competency are: 

-	**Calm**
-	**Fabulous**
-	**Sleep Cycle** 
-	**Pokémon Sleep** 
-	**Meditopia**


**What are some of the core metrics that companies in this field use to measure success?**

-	**Revenue**
-	**Market Share**
-	**Downloads (*2023*)**


**Revenue:**

Headspace generated in 2023 $195 million in revenue, trailing behind Calm which pulled in $300 million in the same year. Pokémon Sleep generated the third most, with $60 million.<sup>27</sup>


 **Market Share:**

In 2023, Headspace held 21% of the overall Wellness App market, trailing behind Calm which held 34%. Fabulous held the third most, with 10% of the market.<sup>28</sup>


**Downloads:**

In 2023, Headspace was downloaded 5.4 million times.<sup>29</sup>

In comparison, Calm was downloaded 10.02 million times in 2023, close to double the amount of Headspace.<sup>30</sup>


---

## Recommendations 


**What products or services would you suggest they offer?**

One area within wellness that has grown considerably over the last few decades is the practice of Yoga. Headspace offers within its catalogue yoga practices that complement and deepen the practice of mindfulness by the addition of specific physical movements and observations of the breathe. Yet, the difficulty in the practice of yoga, especially as a beginner, is being able not only to do the movements as they are intended, but to be able to breathe in a certain style throughout the practice. By offering something similar to the Peloton Guide, which uses computer vision to track movement<sup>31</sup>, and incorporating the usage of third party wearable devices such as an Apple Watch that track biometrics, real-time data pertaining to the movement of the individual can be collected and shown in a side by side with the instructional video, allowing the individual to make adjustments during their practice seamlessly. The wearable sensor may also collect biofeedback data that alerts the practitioner when their breathe is out of sync, allowing them to bring themselves consciously back to the rhythm of their breathe, which is a key component in both the practice of yoga and mindfulness meditation. 

**Why do you think that offering this product or service would benefit the company?**

The market for wearable devices and apps that track biometric data has grown considerably over the last decade. Companies within the mental health and wellness sector, regardless of their origin, have begun to incorporate this technology into their business. Headspace is already attempting to do so with its merger with Ginger.io and its acquisition of Sayana, both mentioned more in detail in one of the above sections. In the fitness sector, companies such as Peloton have taken advantage of the growing desire from individuals to improve their fitness with the help of expert instructors, without having to spend a significant amount of money to hire one privately. With the recent merger and acquisition trends of Headspace, the company is looking to broaden their product offerings, and in light of the growing research showing the correlation between physical exercise and robust mental health, it would not be too much of a jump to expand their product offerings to include both more fitness oriented classes, as well as the ability to integrate technologies that the consumer is already using *(wearable devices)* or are becoming more available and less expensive *(computer vision-capable video cameras a la Peloton Guide.)* By incorporating the recent technological trends occurring within the fitness industry, specifically the at-home segment of that market, Headspace expands their pool of potential customers, and exposes them to the other products they currently offer, without having to expend a substantial amount of resources moving into markets that share no relationship with their core business. 

---

**What technologies would this additional product or service utilize?**
- **Heart Rate Sensors**
- **Transformers**
- **LSTM Networks**
- **Computer Vision and CNNs**

**Why are these technologies appropriate for your solution?**

**Heart Rate Sensors** – The use of a sensor that utilizes Photoplethysmography by emitting a light against the skin to track blood flow changes that determine a user’s pulse. This is available on many wearable sensor products and can be integrated into the Headspace software to determine whether a signal should be sent to the user to deepen their inhale and exhale while breathing.<sup>32</sup>
  

**Machine Learning and AI Technologies**

**Transformers** – Transformers have been used to make recognition predictions based on gait patterns with success. The integration of transformers into computer vision would potentially increase the accuracy of detecting a user’s movements and providing too a more accurate live comparison with the technique of the online expert when engaging in physical exercise.<sup>33</sup>


**LSTM Networks** – The ability to retain information for long periods is important when it comes to making accurate predictions. For Headspace, they would want their machine learning algorithms to accurately predict the movements of an individual so that that individual both in real time and after the session can see themselves how well they are doing or did in comparison to their instructor. The accumulation of biometric data pertaining to the individual user, built up over time, would help the algorithm, by supplying additive layers of information that could be cross-referenced for movement patterns that are peculiar to that individual. Even if the user is new, a databank of movement pattern information, whether from outside data sources or accumulated from within, would allow for a general level of accuracy even in the beginning, but over time, the accumulation of movement data within the app, and retained via a LSTM network, would lead to even greater accuracy of movement predictions.<sup>34</sup>
 

**Computer Vision and CNNs** – The use of convolutional neural networks that filter inputs (images) captured by a video camera would be necessary if the individual doing the exercises is to see how accurate their physical movements are against that of the instructor.<sup>35</sup>


---

## References


<sup>1</sup> Mindfulness and Meditation for the Masses. (2024, January 17). Retrieved from Startupsavant.com: - Headspace — Mindfulness and Meditation for the Masses (startupsavant.com)

  
<sup>2</sup> Mindfulness and Meditation for the Masses. (2024, January 17). Retrieved from Startupsavant.com: - Headspace — Mindfulness and Meditation for the Masses (startupsavant.com)

  
<sup>3</sup> Mindfulness and Meditation for the Masses. (2024, January 17). Retrieved from Startupsavant.com: - Headspace — Mindfulness and Meditation for the Masses (startupsavant.com)

  
<sup>4</sup> Insights, C. (2024). Headspace. New York: CBInsights.com.

  
<sup>5</sup> Headspace. (n.d.). About Headspace. Retrieved from Headspace.com: https://www.headspace.com/about-us


  
<sup>6</sup> Wylie, L. (2024, March 26). Health APP Revenue and Usage Statistics(2024). Retrieved from Business of Apps: https://www.businessofapps.com/data/health-app-market/

  
<sup>7</sup>Grandview Research. (2024). Mental Health App Apps Market Size, Share & Trends Analysis Report By Platform Type (Android, iOS), By Application Type (Depression & Anxiety Management, Stress Management), By Region, And Segment Forecasts, 2024 - 2030. . San Francisco: Grandview Research.

  
<sup>8</sup>Wylie, L. (2024, March 26). Wellness App Revenue and Usage Statistics (2024). Retrieved from Business of Apps: https://www.businessofapps.com/data/wellness-app-market/

  
<sup>9</sup>Business Wire. (2022, January 12). Headspace Health Announces Acquisition of AI-Driven Mental health and Wellness Company, Sayana. Retrieved from Business Wire: https://www.businesswire.com/news/home/20220112005244/en/Headspace-Health-Announces-Acquisition-of-AI-Driven-Mental-Health-and-Wellness-


<sup>10</sup>Sarah Perez, I. L. (2018, September 4). Meditation App Headspace bets on voice and AI with Alpine.AI acquisition. Retrieved from Tech Crunch: https://techcrunch.com/2018/09/04/meditation-app-headspace-bets-on-voice-and-a-i-with-alpine-ai-acquisition/


  
<sup>11</sup>(Alumni), D. (2018, April 9). Ginger.io: An app that monitors your mental health. Retrieved from Harvard Digital Innovation and Transformation - MBA Student Perspectives: https://d3.harvard.edu/platform-digit/submission/ginger-io-an-app-that-monitors-your-mental-health/

  
<sup>12</sup>Stephanie Li, V. L. (2018). Calm: Calm Before the Storm. Retrieved from Ivey Business Review: https://www.iveybusinessreview.ca/magazine/articles/calm-before-storm

  
<sup>13</sup>Yu Chen, K. N. (2021, August 16). Real-Time Machine Learning at Headspace. Retrieved from Medium: https://headspace.medium.com/infrastructure-design-for-real-time-machine-learning-inference-e140793d6741

  
<sup>14</sup>Grandview Research. (2024). Mental Health Apps Market Size, Share & Trends Analysis Report By Platform Type (Android, iOS), By Application Type (Depression & Anxiety Management, Stress Management), By Region, And Segment Forecasts, 2024 - 2030. San Francisco: Grandview Research. Retrieved from Grandview Research: 0

  
<sup>15</sup>Shaun Callaghan, M. L. (2021, April 8). Feeling good: The future of the $1.5 trillion wellness market. Retrieved from McKinsey: https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/feeling-good-the-future-of-the-1-5-trillion-wellness-market

  
<sup>16</sup>Shaun Callaghan, M. L. (2021, April 8). Feeling good: The future of the $1.5 trillion wellness market. Retrieved from McKinsey: https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/feeling-good-the-future-of-the-1-5-trillion-wellness-market

  
<sup>17</sup>Shaun Callaghan, M. L. (2021, April 8). Feeling good: The future of the $1.5 trillion wellness market. Retrieved from McKinsey: https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/feeling-good-the-future-of-the-1-5-trillion-wellness-market

  
<sup>18</sup>Peloton. (2021, November 9). Peloton Introduces Peloton Guide, First Connected Strength Product. Retrieved from Peloton: https://www.onepeloton.com/press/articles/peloton-guide-strength

  
<sup>19</sup>Grandview Research. (2024). Diet And Nutrition Apps Market Size, Share & Trends Analysis Report By Platform (Android, iOS), By Service, By Deployment (Smartphones, Tablets), By Region, And Segment Forecasts, 2024 - 2030. San Francisco: Grandview Research.

  
<sup>20</sup>Research, G. (2024). Meal Kit Delivery Services Market Size, Share & Trends Analysis Report By Offering (Heat & Eat, Cook & Eat), By Service (Single, Multiple), By Platform (Online, Offline), Meal Type (Vegan, Vegetarian), By Region, And Segment Forecasts, 2023 - 2030. San Francisco: Grandview Research.

  
<sup>21</sup>Coherent Market Insights. (2024). Diet And Nutrition Apps Market Size, Share & Trends Analysis Report By Platform (Android, iOS), By Service, By Deployment (Smartphones, Tablets), By Region, And Segment Forecasts, 2024 - 2030. Burlingame: Coherent Market Insights.

  
<sup>22</sup>Olsen, E. (2022, October 18). Calm accounces clinical mental health offering. Retrieved from mobi health news : https://www.mobihealthnews.com/news/calm-announces-clinical-mental-health-offering

  
<sup>23</sup>Grandview Research. (2024). Mental Health Apps Market Size, Share & Trends Analysis Report By Platform Type (Android, iOS), By Application Type (Depression & Anxiety Management, Stress Management), By Region, And Segment Forecasts, 2024 - 2030. San Francisco: Grandview Research. Retrieved from Grandview Research: 0

  
<sup>24</sup>Shaun Callaghan, M. L. (2021, April 8). Feeling good: The future of the $1.5 trillion wellness market. Retrieved from McKinsey: https://www.mckinsey.com/industries/consumer-packaged-goods/our-insights/feeling-good-the-future-of-the-1-5-trillion-wellness-market

  
<sup>25</sup>Mordor Intelligence. (2024). Mental Health Apps Market Size & Share Analysis - Growth Trends & Forecasts (2024 - 2029) Source: https://www.mordorintelligence.com/industry-reports/mental-health-apps. Hyderabad: Mordor Intelligence.

  
<sup>26</sup>Wylie, L. (2024, March 26). Wellness App Revenue and Usage Statistics (2024). Retrieved from Business of Apps: https://www.businessofapps.com/data/wellness-app-market/

  
<sup>27</sup>Wylie, L. (2024, March 26). Wellness App Revenue and Usage Statistics (2024). Retrieved from Business of Apps: https://www.businessofapps.com/data/wellness-app-market/

  
<sup>28</sup>Wylie, L. (2024, March 26). Wellness App Revenue and Usage Statistics (2024). Retrieved from Business of Apps: https://www.businessofapps.com/data/wellness-app-market/

  
<sup>29</sup>Ceci, L. (2024). Downloads of Headspace mobile app worldwide from 1st quarter of 2018 to 4th quarter 2023. New York: Statista.

  
<sup>30</sup>Ceci, L. (2024). Downloads of Calm mobile app worldwide from 1st quarter of 2018 to 4th quarter 2023. New York: Statista.

  
<sup>31</sup>Ransbotham, S. (2022, March 22). AI in Your Living Room: Peloton’s Sanjay Nichani. Retrieved from MIT Sloan Management Review: https://sloanreview.mit.edu/audio/ai-in-your-living-room-pelotons-sanjay-nichani/

  
<sup>32</sup>Mughees, N. (2020, July 02). Types of wearable sensors. Retrieved from Electronics 360: Types of wearable sensors | Electronics360 (globalspec.com)

  
<sup>33</sup>Delgado-Santos, P., Guest, R. T., Deravi, F., & Vera-Rodriguez, R. (2022, June 03). Exploring Transformers for Behavioural Biometrics: A Case Study in Gait Recognition. arXivLabs, pp. 1-12.

  
<sup>34</sup>Salturk, S., & Kahraman, N. (2024, April 15). Deep learning-powered multimodal biometric authentication: integrating dynamic signatures and facial data for enhanced online security. Neural Computing and Applications, pp. 1-12.

  
<sup>35</sup>Nvidia. (n.d.). Computer Vision - What is it and Why does it Matter? Retrieved from Nvidia: Computer vision – What Is It and Why Does It Matter? (nvidia.com)




