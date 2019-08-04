# CPSC5310-Machine_Learning
* User review analysis is becoming a popular area of research. It generally focuses on identifying opinion polarity. App stores like Google Play allow users to submit feedback for downloaded apps in the form of star ratings and text comments. Thousands of user’s feedbacks are given every day on these apps. With this huge amount of apps, the users have a wide selection range to buy or install. 

* User reviews serve as a valuable source of information for evaluating a mobile app, for both new users and developers. But after few months of a new app is launched in the market, there could be over ten thousand textual comments from users. It is very challenging for a potential user to read all of the comments one by one. User reviews may contain helpful advice, innovative ideas about features as well as insulting comments. A textual review generally holds a mixed sentiment. So it is very difficult to filter out the positive and negative feedback or retrieve the feedback for specific features. This can be made easier with sentiment analysis more specifically user review analysis. 

* Moreover, App’s reviews and other user’s reviews are two different things. App’s reviews are normally short. On the other hand, app reviews contain many app specific words like **freezes**, **crashes**, **crashed**, **ads**, **popup**, **candy crush** etc. While testing the reviews against the other review classifiers *“i love this app”* was resulting into **negative** sentiment and *“this app freezes”* was returning **positive**. This makes this analysis even more challenging. I focused on 2 possible sentiment classifications of user reviews: positive and negative. I got the state-of-the-art sentiment classification accuracy of 96.7% combining various classification techniques with voting.
