# CS361
For CS361

This is my final release for my Video Game Library app. It has 4 Microservices. Microservice A is a random game image generator provided by my teammate. Microservice B is a login authenticator. Microservice C is a video game recommendation generator that randomly selects 3 games from the database. The games chosen are updated based on a cache that can be changed. Currently it is set to every 5 seconds for testing purposes. Microservice D is a YouTube trailer generator for the game detail page. It uses the YouTube API to search YouTube using the game title and adds the trailer to the end, and uses the first result to add a trailer onto the game detail page.
