**Inspiration**
After seeing so many seniors in Canada being targets of scams, and the rise of the Canadian Anti-Spam Legislation, we wanted to build an app that informs the senior population of potential scams around them, especially those texts and URLs that pop up in social media feeds.

**What it does?**
Users input a body of text (with or without an URL) through our frontend, and keywords and any URLs are extracted from the text. Then, the keywords are then passed into a ML model built on top of the Naive Bayes classifier. This model scans the keywords, and takes the average score of the keywords to detect whether the input text is potentially a scam or not.

**How we built it?**
We used Anvil to build our frontend, and Python's pandas, numpy, and sklearn to build and train our ML model. Additionally, rake-ntlk was used to extract the keywords from the input text, with regular expressions used to extract the URLs.

**Challenges we ran into**
This was our first time tackling an issue related to NLP and detecting potential scams from text, and so there was a lot that we needed to learn. Moreover, our team lost a member halfway through the first day, creating more for us to ramp up on. As well, with how the weekend went, our team only had just under 14 hours to create this product, creating huge time stress for us.

**Accomplishments that we're proud of**
We are proud that our team worked through our challenges, and ended up with a functional product to demonstrate! We are also proud that we were to able to meet Rocket Innovation Studio's challenge, and build a unique approach with a scam detection web app which could be repurposed into an API for use with any and all social media!

**What we learned?**
We learned how to use rake-ntlk and sklearn to determine scam weights to our keywords, and how to classify text and URLs as scam or not. As well, we learned how to work together as a team to overcome unexpected hurdles, and how to be friends throughout all of it!

**What's next for ScamZeroed?**
Our future plans include creating a more robust ML model to better detect the scams, as due to time constraints we were limted to detect based solely on individual keywords rather than the whole context. Additionally, we plan. Additionally, we plan on modifying our web app into a Rest API, which would allow social media apps to utilize it to detect and flag potential scam posts.

**Demo**
https://drive.google.com/file/d/1TrMXZsiYJKmKhulC92uFbQ3RU4_Ic5c0/view?usp=sharing
https://youtu.be/DnZAK1xdmDU
