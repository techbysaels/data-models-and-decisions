# Amazon Go Case

Amazon Go focuses on a specific shopping problem, to reduce the time customers spend checking out. Amazon developed an automated approach which raised questions about how much data and investment are needed to remove that step reliably, and whether the same service outcome could be achieved more simply.

## Background

Amazon Go stores were designed to let customers enter, select their products, and leave without a traditional checkout. The case describes seven years and $300 million spent implementing the concept, initially with a limited assortment of products used to collect data. That amount of investment in time and money puts the practical difficulty of building the system into perspective and if it could be reached in a easier way.

## What is the rationale for what they are trying to do?

Amazon is trying to remove the traditional checkout step and create a faster grab-and-go experience. By doing this, they seek to provide customers with a better service. Basically, the experience consists of going into the store, grabbing what you need, and then leaving the store without interacting with a cashier or waiting in line. The challenge with this system is to maintain an accurate digital representation of the activities of the shoppers in real time to transform it into a correct digital transaction.

The same objective had Monoprix, a known French retailer that challenged Amazon by claiming that they had offered an on-the-go service for more than a decade. Even when the solutions are technically different, this raises an important question: how much technology is really necessary to deliver the outcome the customers want?

## What are the AI elements, and what are they supposed to do?

The core of the solution is computer vision through complex neural networks and sensor fusion to obtain the behaviour of the client. In general, the question the system is trying to solve is who took what using a variety of AI models. Object recognition was used to distinguish the products even when they are from the same brand and look very similar. Pose estimation was applied to answer the question of what a person near a shelf is doing with their arms, while their activity was being analysed to know if they have picked up or returned a product to update the virtual cart. Finally, customer location tracking was done by cameras and AI to determine not only where a customer is, but also how to differentiate them from other customers in crowded situations.

## What data is needed, and how is it acquired?

The solution needed visual, location, activity, product, and customer-entry data. To obtain visual information, custom camera hardware that captures RGB video and distance information was used. The computer vision system powered by AI segments images, identifies customers, separating them from workers, and uses information from multiple cameras to build an accurate location map. It also uses the images to analyse the pose and activities near the shelves and to recognize the items in them. The customer-entry data comes from a robust system that combines the entry input from the scanner at the door of the shop with the location information provided by the cameras, knowing when a customer is entering and leaving the store, even in situations where a family is shopping using the same account. Finally, product information was obtained from limited data that needed to be augmented to address different situations like strange positions or angles. The solution also used mock-up stores to generate and check the examples under controlled conditions.

The limited product assortment helped constrain the initial problem. Introducing more products or different store conditions would require further examples and validation. The years and investment described in the case show why training data should be treated as a major project cost. Installing sensors does not immediately produce the labelled, representative data needed to train a dependable system.

## What is the interface with humans and expert operators?

For shoppers, the human interface is simple, because everything is done by downloading the Go app. With the app and their registration, they only need to shop normally and leave the place while the AI does all the work in the background to provide the final receipts of the transactions. The app also provides the options to question or correct a charge if the transaction is wrong. For the workers and supervisors, the system checks their behaviour to separate them from the customers; for example, the workers will mostly put products on the shelves, not take products from them. In the information reviewed, there isn’t a direct interface for supervision stated; however, we can deduce that their role is more efficient because the cameras are already checking the behaviour of the customers and workers, probably raising alarms for suspicious activities or problems that require more attention and analysis from a human point of view.

## Conclusion

The design should be judged by the quality and cost of the shopping process, not only by the complexity of the solution. A retailer considering a similar system would need to include training-data collection and human review in that assessment. Amazon's investment shows what this approach can demand while another retailer may achieve a worthwhile reduction in waiting time with a simpler process.

## Sources
- [Introducing Amazon Go and the World’s Most Advanced Shopping Technology (YouTube, 2016)](https://www.youtube.com/watch?v=NrmMk1Myrxc)
- [How the Amazon Go Store’s AI Works (Gross, 2019)](https://medium.com/data-science/how-the-amazon-go-store-works-a-deep-dive-3fde9d9939e9)
- [Video: French grocer parodies Amazon Go, claiming checkout-free shopping is nothing new (GeekWire, 2017)](https://www.geekwire.com/2017/video-french-grocer-parodies-amazon-go-claiming-checkout-free-shopping-nothing-new/)
- [Monoprix tacle Amazon (YouTube, 2016)](https://www.youtube.com/watch?v=CNoa-9TBH30)
