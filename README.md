# PhotoFinder AI

Final project for the Building AI course

## Summary

this AI project helps you discover the best places to take photos near your current location. 

Whether you want to capture a selfie, a group photo, or beautiful landscapes, the AI will show you where to go on a map. It also checks if the sun's position is favorable for good lighting and suggests the ideal times to take your photos.

## Background

The problem I want to solve is this: many people love taking photos when they're out and about, especially when they're sightseeing or exploring new places. But often, they struggle to find the best spots to take those perfect pictures. They might end up taking photos that don't turn out as well as they'd hoped, and by the time they realize it, they're already far from that location.

My personal motivation for this project is because I enjoy taking photos with my phone when I'm out and about. I've often wished for a tool that could suggest good photo spots, but I couldn't find anything like that, so I decided to create it myself.

I think that this topic is important because a lot of people take pictures and i'm sure i am not the only one who is searching a tool like this

## How is it used?

For example: I'm in a town I know nothing about, and the urge to take photos comes over me, so I take my phone out in a place I like, but it's not enough for me, so I look on the internet, but there aren't many examples there either.

Solution: PhotoFinder AI, thanks to this AI I enter my location and the style of photo I want to take (selfies, landscapes etc...) and the AI gives me suggestions.
The database of this AI will be dynamics, the localisation of good spot will be upload from users that gone there , if they think it's a good spot they can upload it. To check if it's really a good spot or not the ai will check the photo with another ai if the pictures are good or not, there is a risk that some user upload some photo that are not made for taking good pictures and to delete this from the AI database the users can check the pictures taken in this spot and make a feedback, if there is enough feedback the ai will delete it.

## Data sources and AI methods
For this ai to work i will have to use a bunch of AI methods because i have a lot of things to check and calculate.
* Firstly to utilize the data from the databse in AI and the data from the upload of users:
  
| Methods                                  | Description                                                                                                                                     |
| -----------                              | -----------                                                                                                                                     |
| Data Collection and Preprocessing        | Collect and store data from various sources, including databases and user uploads.                                                              |
| Data Storage                             | Utilize a robust and scalable database system to store and manage the data efficiently. Options include SQL databases (e.g., MySQL, PostgreSQL) |
| User Authentication and Security         | Implement user authentication and authorization mechanisms to ensure data security and privacy.                                                 |
| Supervised Learning                      |  If you have labeled data, you can train models for tasks like classification, regression, or recommendation.                                   |
| Computer Vision                          | Use computer vision models for image and video analysis.                                                                                        |
| User Feedback and Iteration              | Gather user feedback to improve the system continually. For deleting a pictures for example ect...                                              |

* Secondly to detect the sun position and tell the user if it's a good time to take a picture:

| Methods                                           | Description                                                                                                                                     |
| -----------                                       | -----------                                                                                                                                     |
| Astronomical Calculations for Sun Position        | Use astronomical algorithms and formulas to calculate the sun's position in the sky for a given location (latitude and longitude) and time (including date and time of day).        |
| Integration with Geographic Data                  | <li>Incorporate geographic data into your system to determine the precise latitude and longitude of the location where the pictures are being taken.</li><li>Combine the calculated                                                          sun position with the location data to obtain the sun's position relative to the photographer's position.</li>                                                                      |
| Real-time Monitoring and Feedback:                | <li>Continuously monitor the sun's position based on real-time astronomical calculations and the camera's view.</li><li>Provide feedback to the user, indicating whether the sun is in                                                       the frame and its current position.</li>                                                                                                                                            |

## Challenges

* This project has the potential to be a huge success, but its success hinges on user engagement and feedback for the database. Without active user participation and the upload of valuable spots, we'll end up with a database filled with identical or uninteresting locations, which is not the outcome we desire. Therefore, the limitation we face primarily lies in the number of users actively contributing to the platform.

* Additionally, there's another challenge we need to address – the human factor. It's essential to recognize that sometimes, a truly exceptional spot is one that remains untouched or undiscovered by the masses. These hidden gems thrive because they're not yet widely known or frequented by large crowds. The allure of such places lies in their exclusivity and pristine condition.

* However, if too many people start flocking to these hidden spots, we risk compromising their charm and cleanliness. It's essential to strike a delicate balance between promoting these unique locations and preserving their natural beauty. My objective is not only to identify these hidden gems but also to ensure their long-term sustainability, so that they remain exceptional places for generations to come.

## What next?

The next logical step in the evolution of this AI could indeed be its integration directly into the photos application of smartphones. However, for this vision to become a reality, our AI needs to achieve significant success in its current form. It's only when we demonstrate its potential and garner widespread recognition that phone companies may become interested in incorporating it into their systems.

To develop an AI as sophisticated as this, assembling a highly skilled team of AI developers is paramount. The field of AI is ever-evolving and requires a deep understanding of machine learning, computer vision, and data analysis. A dedicated team with expertise in these areas will be essential to take this technology to the next level.

Looking ahead, it's possible that in the future, we may not even need user feedback to grow and enhance the AI's database. As technology advances, the AI could potentially autonomously identify hidden spots using tools like Google Street View, making it more self-reliant in discovering and sharing these unique locations with users. This next step would not only reduce the reliance on user feedback but also increase the efficiency and accuracy of the AI in uncovering hidden gems.

In conclusion, the potential for this AI is vast, and its integration into smartphone photo applications represents an exciting possibility for the future. However, it all hinges on achieving current success, assembling the right team, and harnessing emerging technologies to make it even more autonomous and user-friendly.


## Acknowledgments

* The Elements of AI team inspired me to come up with an idea for a project. Thanks to them, I have come up with a project idea that I love, and if my skills are good enough, I think I will develop it.
