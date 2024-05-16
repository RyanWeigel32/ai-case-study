# ai-case-study document
### Homework #1
## Overview and Origin
**Name of Company**

Headspace

**When was the company incorporated?**

 2010 

**Who are the founders of the company?**

Andy Puddicombe and Rich Pierson 

**How did the idea for the company (or project) come about?**

 It came about after the two founders crossed paths in London. Richard Pierson built a successful career in marketing and advertising at a young age (27) but was beginning to feel burnt out. This led to his explorations into the practices of meditation. It was here he met Andy Puddicombe, a man before beset by personal tragedies that prompted him to travel to Asia and become a Buddhist Monk. Andy, wishing to spread the practices of meditation to laymen, decided to then leave his position as a Buddhist monk, return to London and set up a meditation clinic. The meeting and ensuing friendship between the two men, centered around meditation, proved to be the foundation out of which the idea of Headspace grew. 

**How is the company funded?**

 Headspace is funded by an agglomeration of different businesses. Investment Firms, Growth Equity Firms, Lending Firms, Incorporated Companies, and Venture Capital, to name a few. The company has raised $322.11M over 13 rounds of investments from 24 different investors with the latest round occurring on March 6th, 2024. 

---

## Business Activities 


**What specific problem is the company or project trying to solve?**

 The general problem that Headspace is attempting to address through its services is mental health difficulties that are prevalent within our present world. Although the main activity of Headspace is the offering of guided meditation courses for a myriad of different life situations and experiences, it has also entered the broader mental health market by the acquisitions of such companies as Ginger, Sayana, and Shine. 

**Who is the companies intended customer? Is there any information about the market size of this set of customers?**

 Headspace’s intended customer base is anyone seeking accessible mental health support regardless of what demographic they fall into. 
 There were 311 million health app users in 2023, and within the mental health app market, its estimated market size was set at $6.2 billion (US).  

**What solution does this company offer that their competitors do not or cannot offer?**

 The largest competitor for Headspace in the mental health and mindfulness app market is Calm, with both having 55% of the market share.  While both are well-known for offering a library of guided mediation courses, Headspace has branched out more into the general mental health field with two important acquisitions and one merger. The first acquisition was the company Sayana, a “self care app that leverages chat-based sessions with an AI persona…who encourages users to track their mood along with what influences it.” This app “personalizes user’s experiences based on their check-ins and mood trends surfacing high quality content and self-care exercises” based on a handful of different therapeutic approaches. To quote Headspace Health CEO Russel Glass, 

> “Amidst a rapidly growing landscape of mental health and wellness apps, Sayana has developed a uniquely engaging member experience backed by world-class AI and machine learning algorithms.”  

 The second acquisition was Alpine.AI, a company in the digital assistant market. Headspace Health’s plan is to leverage “Alpine’s machine learning capabilities” “to give people an interactive voice-based way to discover different meditation sessions…and to use those interactions to make better suggestions to individual users.” 

 Headspace also merged with Ginger.io to create Headspace Health.  Ginger.io, when standalone, was a “mobile app that enables users to chat with professional coaches and therapists.” Ginger.io did so by tracking through the app data pertaining to the behaviors of the user, and by building statistical patterns based on this received data through the use of machine learning and AI, the app would be able to find deviations from normal patterns of behavior and send messages to the user, as well as alert the coach or therapist to check in and intervene. 
 
 With these two acquisitions, and one merger, Headspace (now Headspace Health) has expanded its customer base beyond those who are seeking only an entry into the practice of mindfulness, and into a market for individuals searching for a more diverse array of potential solutions for mental health difficulties. By offering up different mental health practices, utilizing the power of machine learning to tailor products and courses that meet the specific need of the individual, while also retaining adjacent to these services its core business in helping individuals learn mindfulness meditation, it has the advantage of attracting individuals who are on the fence about their core business, but are looking for solutions and practices that help in addressing their very real mental health difficulties. 

---

### Which technologies are they currently using, and how are they implementing them?

* Each of these technologies are referred to in a single article. Citation is located at the end of the last paragraph of this section. * 

**Amazon Kinesis Data Stream** – “The user generates events by performing actions inside the app, and these events are forwarded to Kinesis to be processed by **Spark Structured Streaming**, another Amazon service that helps process large amounts of data. 
**Spark Structured Streaming** uses micro-batching to break up the stream of events into discrete chunks, processing incoming events in small micro-batch dataframes. 

Spark Structured Streaming processes this data and feeds into ML models developed using **Databricks** notebooks and evaluated with MLflow experiments offline. 

Once the model has been created, a Github release is created, picked up by the **Circle CI** CI/CD tools that test and build MLflow model images.

This is pushed to **Amazon’s AWS ECR**, a container registry, and then deployed onto **Amazon’s Sagemaker**, an integrated development environment that gives developers the ability to build, train, and deploy ML models at scale. 


Headspace uses Blue-Green architecture to update its ML models without interrupting its services. It does so by maintaining two parallel infrastructures. Headspace uses Amazon’s serverless compute service **Lamba** to reroute any incoming features and predictions to one of the production environments while working to update the parallel environment with new features. Once this update has been complete, the development team switches the Lambda towards this updated environment, allowing for a seamless transition between the old environment and the newly updated one.  

---

## Landscape

**What field is the company in?**

Headspace operates within the mental health and wellness field. 


**What have been the major trends and innovations over the last 5-10 years?**

The field of mental health and wellness has expanded to encompass six different categories:**Better Health, Better Fitness, Better Nutrition, Better Appearance, Better Sleep, and Better Mindfulness**. Headspace falls into three of these categories, based on their original core competency, and those acquired through their acquisitions, those field being Better Health, Better Sleep, and Better Mindfulness.  

**Better Health**

In this “traditional category” for wellness, the field of Better Health has seen an increase in the desire and use of personal health-trackers, monitoring their own health and potential symptoms through wearable devices. Included as well are companies focusing more on data-driven care, allowing them to target specific symptoms and prescribe medication or forms of therapy that are more in-line with the need of the patient. On the administrative side, new apps are making it easier to book medical appointments and obtain any prescriptions that a patient may need. 

**Better Fitness**

In this subfield, a rise in companies offering robust and accessible forms of exercise such as Peloton, Mirror, and Tonal, occurred during the COVID-19 pandemic. Peloton, for instance, developed Peloton Guide, an AI-enabled device that tracks the exerciser’s movements, compares the movements of the user with that shown by the instructor, allowing them adjust their movements to be more in line with the instructor, as well as showing the user what muscle groups have been exercised or not to make sure the user is gaining a well rounded training experience.   


**Better Nutrition** 

The nutritional subfield gained momentum during COVID-19 with the rise of global meal kit delivery services such as Blue Apron and Hello Fresh. The Nutrition app market, with companies like MyFitnessPal and MyNetDiary, have a CAGR of 17.2%, as individuals are becoming more health conscious due to rising obesity and heart disease rates among the population.   

**Better Sleep**

Worldwide, individuals are investing in sleep-monitoring devices and applications as a lower-cost means to address the rising prevalence of sleep disorders. Companies such as Sleep Cycle, Pillow, Calm, and even Headspace, are offering solutions to address this increase in sleep difficulties, whether it be in wearable devices that through sensors track quality of sleep, or online courses that help relax the body and lower stress levels before one hits the pillow. The market has a CAGR of 14.4%, forecasted from 2024 to 2031.  



**Better Mindfulness**

Increased market competition has led companies in this sector to invest more money into acquiring AI-driven companies as a means of finding the most effective way to offer their mindfulness products that are tailored to the individual user. This sector has also seen acquisitions and mergers with companies in the general mental wellness market, expanding their product offerings to include digital care coordination, condition management, and sleep tracking. This market has a CAGR of 15.2% when forecasted from 2024 to 2031.   

---

**What are the other major companies in this field?**

It is very difficult to place Headspace within a strictly delineated market as “mental health and wellness companies are considering how to play across the health and wellness categories and channels.”  The market is highly fragmented  and no single company is predominant amongst its competitors. Evidenced by the relatively recent expansions of Headspace into the virtual healthcare field with its merging with Ginger.io in 2021 and its acquisition of Sayana in 2022, Headspace Health is indeed attempting to blur those lines. Yet, its core competency is still prevalent, that being an app that offers a robust catalogue of mindfulness meditations courses. Its direct competitors  within the field of this core competency are: 

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

Headspace generated in 2023 $195 million in revenue, trailing behind Calm which pulled in $300 million in the same year. Pokémon Sleep generated the third most, with $60 million. 

 **Market Share:**

In 2023, Headspace held 21% of the overall Wellness App market, trailing behind Calm which held 34%. Fabulous held the third most, with 10% of the market. 

**Downloads:**

In 2023, Headspace was downloaded 5.4 million times. 
In comparison, Calm was downloaded 10.02 million times in 2023, close to double the amount of Headspace.  

---

## Recommendations 


**What products or services would you suggest they offer?**

One area within wellness that has grown considerably over the last few decades is the practice of Yoga. Headspace offers within its catalogue yoga practices that complement and deepen the practice of mindfulness by the addition of specific physical movements and observations of the breathe. Yet, the difficulty in the practice of yoga, especially as a beginner, is being able not only to do the movements as they are intended, but to be able to breathe in a certain style throughout the practice. By offering something similar to the Peloton Guide, which uses computer vision to track movement , and incorporating the usage of third party wearable devices such as an Apple Watch that track biometrics, real-time data pertaining to the movement of the individual can be collected and shown in a side by side with the instructional video, allowing the individual to make adjustments during their practice seamlessly. The wearable sensor may also collect biofeedback data that alerts the practitioner when their breathe is out of sync, allowing them to bring themselves consciously back to the rhythm of their breathe, which is a key component in both the practice of yoga and mindfulness meditation. 

**Why do you think that offering this product or service would benefit the company?**

The market for wearable devices and apps that track biometric data has grown considerably over the last decade. Companies within the mental health and wellness sector, regardless of their origin, have begun to incorporate this technology into their business. Headspace is already attempting to do so with its merger with Ginger.io and its acquisition of Sayana, both mentioned more in detail in one of the above sections. In the fitness sector, companies such as Peloton have taken advantage of the growing desire from individuals to improve their fitness with the help of expert instructors, without having to spend a significant amount of money to hire one privately. With the recent merger and acquisition trends of Headspace, the company is looking to broaden their product offerings, and in light of the growing research showing the correlation between physical exercise and robust mental health, it would not be too much of a jump to expand their product offerings to include both more fitness oriented classes, as well as the ability to integrate technologies that the consumer is already using (wearable devices) or are becoming more available and less expensive (computer vision-capable video cameras a la Peloton Guide.) By incorporating the recent technological trends occurring within the fitness industry, specifically the at-home segment of that market, Headspace expands their pool of potential customers, and exposes them to the other products they currently offer, without having to expend a substantial amount of resources moving into markets that share no relationship with their core business. 


