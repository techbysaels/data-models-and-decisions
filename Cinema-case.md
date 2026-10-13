# Cinema case: A rule-based process automation example

The way people go to the cinema has changed a lot since I was a kid. What used to involve arriving early, waiting in long lines, and rushing to find a good seat can now be organised from home through a website or an application. These changes provide a useful example of how rule-based automation can improve an everyday process. In this case, I will explain how connected purchasing systems, seat reservations, and loyalty programmes have improved the service for customers and helped cinemas organise their work. I will also discuss how collecting customer information supports recommendations and decisions about which movies to show in different locations.

## How has the process changed over time?

When I was a kid, my parents and I went to the cinema several times a year. I remember clearly that we needed to go early to be able to buy the tickets for the available functions. I also remember that all the customers formed a line minutes before the movie to be able to catch the better seats. Even sometimes for blockbuster movies that got a lot of spectators, the lines were formed 1 or 2 hours before the movie started because the fans wanted to see the movie in the best seats possible, and, when entering to see the movie, some of them would run and push people to reach their desired seats. The situation was chaotic and very uncomfortable, especially if you wanted to have a nice time with your family or friends.

As time passed by, the cinemas began to allow you to reserve the exact seat you wanted among the available ones. Then you went to the cinema, bought your tickets, and could go calmly to purchase your food and beverage as you already had a numbered seat. The process was still done entirely in the cinemas, but it provided order, and the customers were more relaxed, improving the service. Nowadays, the process has been developed further; the system has changed and provides a better service to the customers with a web page or an application on your phone to reserve your seats from your house and even purchase your popcorn and soda that will be given to you in the cinema. The traditional method still exists for people who are passing by and want to buy a ticket, but long lines, disorder, and stress for customers are a thing of the past.

## What are the benefits of using this type of automation instead of the traditional method?

There are several benefits to this type of automation, not only for the business but also for the customers. The service improved a lot, because before the change, customers would get stressed and sometimes couldn’t even reach a seat; now, they can know from their homes which seats are available and avoid making plans. The by-passers can still buy their tickets from the cashier, but as all the systems are connected, they will see only the available seats. The same happens for popcorn and sodas; you can buy them from your home and pick them up at the cinema or purchase them directly in the cinema. You still need to wait in line, but it is way more orderly and faster than what it used to be.

It also saved resources, because with the new system, you do not need too many people attending the cashiers, except maybe for blockbuster movies, but you still need people in charge of preparing popcorn and sodas in a fast way. Then, many cinemas reallocated their personnel to the food and beverages section and left one or max two people in the cashiers. Another benefit was creating the loyalty points system to retain customers, because when the system was only in person and the cashiers just printed the tickets at the moment, no data was available about the customers. The business was practically blind to customer data and could not provide benefits with loyalty points.

As time went on, the business began to convince customers to use a loyalty card; for that, a customer must use their personal data to purchase the card, and then, every time you went to the movies, the system saved your information such as your customer ID, number of tickets bought, food and beverages purchased, and payment method. This is a clear example of a use case where, before developing AI or tech solutions, you need to obtain enough data to train the models. The final point of this development was offers being sent to your email about movies you might be interested in, recommendations based on your favourite snacks, and a loyalty point system that gives you benefits as you upgrade your card with the number of visits.

It also improved security for the customers and the workers, because people began to use online purchases increasingly, because it was the easier and more secure way. The development of the system made the workers more secure because they had less cash to manage, so they were less exposed to possible robberies. Finally, the cinema chains could use the data of the customers and their habits when picking a movie and its characteristics to arrange the movies differently for different sectors of the city. For example, in my city, there are districts where people like to see more dubbed movies than subtitled movies; then the cinemas separate more rooms for dubbed movies and leave just two or three for subtitled movies. However, there are other sectors where the tendency is opposite, and people like to see more subtitled movies than dubbed movies; in that case, the subtitled movies get more rooms while the dubbed movies take the two or three rooms left. The same could happen with other characteristics such as 2-D or 3-D, blockbusters or documentaries, among others, leading to a more efficient way to attract customers to the cinemas.

## What are some required input questions for the process?

- What movies and movie characteristics do customers prefer in different sectors of the city or different cities in a country?

- How can the cinema collect enough customer information to provide personalized services and advertisements?

- What purchasing habits does each customer have regarding tickets, food, beverages, and payment methods?

- How frequently does the customer visit the cinema, and what loyalty category should they belong to?

- How can the cinema reduce incidents related to ticket purchasing and entering the screening rooms?

- How can more customers be encouraged to purchase tickets, food, and beverages online so employees can be reallocated from cashier activities to service and food preparation?

## How is the output structured?

- Visual interface and self-service purchasing: Customers enter the app and begin their purchase by seeing the available seats and choosing from them. Then they choose their snacks and are offered promotions according to their loyalty category and points. Finally, they receive a confirmation of purchase by email with the QR code to enter.

- Loyalty system: Customers are allocated to a loyalty category decided at the beginning of the year by counting how many times the customer has gone to the cinema in the past year. According to the category, the system enables promotions and recommendations.

- Personalized recommendations and promotions: Customers receive emails with movie recommendations, posters, offers, or additional benefits according to their previous habits and loyalty category.

- Movie allocation by location: The cinema can assign more or fewer screening rooms to dubbed, subtitled, 2-D, 3-D, blockbuster, or documentary movies according to the preferences identified in each sector of the city.

- Employee reallocation and security: Employee reallocation from ticket cashiers to food and beverage preparation to improve efficiency in the service. Reduction of the amount of cash handled by cinema employees to improve security in the cinemas.

## Can you define any rule-based tasks to clarify the process?

- Seat availability: If a seat is purchased or reserved, mark it as unavailable in all purchasing channels.

- Seat selection: If a seat is available, allow the customer to select it; if it has already been purchased, prevent another customer from selecting it.

- Loyalty registration: If a customer uses the loyalty system, associate purchases with their customer ID.

- Loyalty upgrade: If the number of visits reaches the requirement for a higher loyalty category, upgrade the customer's category and provide the corresponding benefits.

- Movie recommendation: If the customer's recorded habits indicate interest in particular movies or movie characteristics, use those preferences to generate recommendations.

- Snack recommendation: If the customer's purchase history shows recurring food or beverage preferences, use those preferences when generating personalized recommendations or benefits.

- Sector preference: If customers in a particular sector show a greater preference for specific movie characteristics (dubbed, subtitled, 2-D, 3-D, documentary, etc), allocate more rooms to movies with these characteristics.

- QR identification: If the purchase has been completed, associate it with a QR code that can be used at the cinema.

## Conclusion

This cinema example shows how automating specific tasks can improve the experience for customers and the organisation of the business. Keeping seat availability updated across all purchasing channels prevents customers from selecting the same seat, while online purchases and QR codes make buying tickets and entering the screening rooms more orderly. Employees can spend more time preparing food and beverages, and handling less cash can improve their security. The information collected through purchases and loyalty programmes also helps cinemas understand customer preferences and provide relevant benefits. For me, the main lesson is that these improvements begin with understanding the process and defining clear rules for each task. As the cinema collects more useful data, it can improve its services further and assess where more advanced tools would be worthwhile.
