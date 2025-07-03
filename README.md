# Food Pantry Wait Time Analysis

When I first stepped into the world of food pantry operations, I was struck by the dedication of the volunteers and the need to serve those in our community. Yet, I also noticed a problem that seemed to repeat itself: long wait times for clients. This sparked my curiosity and led me to take on a project focused on analyzing food pantry visit patterns and the factors affecting wait times.

**Why THIS project?**

The motivation for this project came from my own experiences at the pantry. With around 300 people visiting over just 2.5 hours, I saw firsthand how chaotic things could get, especially when clients arrived before we even opened. This often left many waiting outside, which could be uncomfortable and frustrating. I wanted to understand these patterns better and find ways to improve the experience for everyone involved. This project is special for me because it merges data analysis with a real-world impact, aiming to enhance the pantry's efficiency and service quality.

**Key Takeaways**

  - Wait times range from 1 to 89 minutes, with an average of 45 minutes.

  - Arriving before 10:30 AM on Thursdays and Saturdays and before 5 pm on Tuesdays generally leads to longer waits compared to later arrivals.

  - At peak times there are over 100 clients (plus other guests) in waiting. The pantry parking lot holds ~20 vehicles, placing significant strain on the surrounding roads and neighborhood.

  - There is a trend of more clients arriving early on Thursdays compared to other distribution days.


**Dataset Details**

For this analysis, I used data from our pantry, comprising 17,000 rows detailing visit times and dates. This dataset provided a comprehensive view of our clients' arrival patterns, allowing me to identify trends and insights effectively.

**Analysis Process**

To tackle this project, I followed several steps:

1. Data Cleaning: I ensured that the dataset was clean and ready for analysis, eliminating any errors or missing entries.
2. Data Visualization: I created visuals, like box and whisker plots, to illustrate the wait time distributions and bar charts showing the number of arrivals per time slot. These helped clarify the trends I was observing.
3. Statistical Analysis: I calculated averages and ranges to understand how wait times varied based on arrival times.

I was surprised to find such a significant difference in wait times before and after 10:30 AM on Thursdays/Saturdays and after 5 pm on Tuesdays. It made me realize the impact of timing on client experience and how we could adjust messaging to better inform our clients.

**Visuals and Insights**

**Bar Charts:** These charts illustrate the number of people arriving per 15 minute increment (left) and before and after the official distribution start time (right). They clearly highlight the spike in arrivals just before opening, reinforcing the need for targeted communication about when to come for shorter wait times. Particularly on Thursdays when, on average, 46% (127) of all the clients served arrive prior to the distribution start time.

**Box and Whisker + Scatter Plots:** These visuals showcase the distribution of wait times as a function of arrival time and order. The wide range of wait times before the distribution starts is primarily due to the lottery system we use, which adds unpredictability. You'll notice that wait times become much more consistent and lower as time goes on after opening.

**Client Messaging Flyer:** I created a flyer in multiple languages that communicates to our clients that arriving later can significantly reduce their wait time, aiming to ease the pressure on our volunteers and improve the overall experience.

**Main Takeaways**

-	**Peak Times Need Attention:** Understanding peak arrival times allows for better planning and can help manage volunteer resources more effectively.
-	**Timing Matters:** Clients who arrive later enjoy shorter wait times, a message that can be easily communicated to improve the overall flow of visitors.
-	**Community Impact:** By sharing these insights, we hope to create a better experience for clients and volunteers alike, showing how data can lead to tangible improvements in community services.

**Conclusion and Personal Reflections**

Through this project, I learned valuable lessons about the importance of data in improving operations. The biggest challenge was translating the data insights into actionable messages for our clients. However, seeing the potential for real change has been incredibly rewarding. This experience has deepened my commitment to ensuring our pantry operates smoothly and effectively, and it has inspired me to explore further improvements in client services.
