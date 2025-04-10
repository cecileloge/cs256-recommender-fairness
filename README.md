## Algorithmic Fairness in Recommender Systems
CS256 Project | Spring 2024 


**Cecile Loge ep. Baccari** | ceciloge@stanford.edu 

---

**Motivation**: Recommender systems can be found everywhere today, shaping our everyday experience whenever we’re consuming content, ordering food, buying groceries online, or even just reading the news. Let’s imagine we’re in the process of building a recommender system to make content suggestions to users on social media. When thinking about fairness, it becomes clear there are several perspectives to consider: the users asking for tailored suggestions, the content creators hoping for some limelight, and society at large, navigating the repercussions of algorithmic recommendations.

A shared fairness concern across all three is the emergence of filter bubbles (Pariser, 2012; Areeb et al., 2023) , a side-effect that takes place when recommender systems are almost "too good", making recommendations so tailored that users become inadvertently confined to a narrow set of opinions/themes and isolated from alternative ideas. From the user’s perspective, this is akin to manipulation. 

From the small content creator’s perspective, this is an obstacle preventing them access to a whole range of potential fans. From society’s perspective, the potential consequences are far-reaching, influencing collective opinions, social behavior and political decisions.

---

**Approach**: A recommender system can be thought of as a two-step model that first (step 1) will predict a user’s ratings on different items of content they haven’t consumed yet, then (step 2) will surface a ranked list of top k items of content to recommend to that user (based on the predicted ratings). Read more about our proposal for more fairness in recommender systems in the report - including new metric definitions and a post-processing algorithm.
