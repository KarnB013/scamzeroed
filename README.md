**Inspiration**
After seeing so many seniors in Canada being targets of scams, and the rise of the Canadian Anti-Spam Legislation, we wanted to build an app that informs the senior population of potential scams around them, including social media text and URLs that pop up in social media feeds.

**What it does?**
Users input a body of text or an URL through our frontend, and keywords are extracted from the text through our custom API call. Then, the keywords are then passed into a ML model built on top of the Naive Bayes classifier. This model scans the keywords, and takes the average score of the keywords to  detect whether this text or URL is potentially a scam or not. 

**How we built it?**
We used Anvil to build our frontend, and Python's pandas, numpy, and sklearn to build and train our ML model. 

**Challenges we ran into**
This was our first time using the Naive Bayes classifier, and so there was a lot that we needed to learn. Moreover, our team lost a member halfway through the first day, creating more for us to ramp up on. As well, with how the weekend went, our team only had just under 14 hours to create this product, creating huge time stress for us. 

**Accomplishments that we're proud of**
We are proud that our team worked through our challenges, and ended up with a functional product to demonstrate! We are also proud that we were to able to meet Rocket Innovation Studio's challenge, and build a scam app!

**What we learned?**
We learned how to use sklearn and the Naive Bayes classifier to determine scam weights to our keywords, and how to classify text and URLs as scam or not. As well, we learned how to work together as a team to overcome unexpected hurdles, and how to be friends throughout all of it!

**What's next for ScamZeroed?**
Our future plans encompass building a mobile version of our app, and expanding to take in more input variations, such as images, videos, etc to test if they are a scam or not.
