### Scraping IMDb User Rating with Selenium

Movies and TV Shows have always filled a special place in my life and I could spend a whole afternoon watching the latest blockbuster. When Netflix arrived to Spain I was completely thrilled at the idea of having more movies I could ever watch in one place. Then came HBO, Amazon Prime Video and the options just kept growing. However, at some point I started to think that all this possibilities were not that good because their quality was mostly mediocre as most companies sacrificed quality over quantity. 

With this idea on mind I decided to **analyze the quality of content available in [Netflix]([url](https://www.kaggle.com/datasets/shivamb/netflix-shows)), [Amazon Prime Video]([url](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows)) and [Disney]([url](https://www.kaggle.com/datasets/shivamb/disney-movies-and-tv-shows))+**.

For this project I used three datasets from Kaggle which had information about the participating cast, genres and duration but didn't have any field with information about the quality of the mvoie so, using **Selenium** I scraped IMDb's website to extrar the User Rating of each title. 

After enriching the original dataset with the ratings I analyzed the results and extracted the following conclusions:

- Amazon has the greatest number of titles with ratings lower than 4 in a range from 1 to 10, while Disney has the highest quality content. One reason behind this can be beacuse Amazon has many more title available than Disney, accumulating more mediocre options as a consequence. 

![alt text](https://miro.medium.com/v2/resize:fit:640/format:webp/1*O4soytg7h8LBv2bn98QDoA.png)

Also, the general evolution of title qualities is following a decreasing trennd in general: 

![image](https://user-images.githubusercontent.com/70518395/222450664-363e07b9-2020-478d-a464-f36de9996278.png)

