# The-Vision
Brickhack 6 project that helps blind people listen to the description of the objects in front of them.

Inspiration -The fact that this project might help so many people in the world. There are so many cool technologies available out there but there are not as many cheap products available that would help people with disabilities. So we thought why not create a product at minimum cost and make it available to the people in need. 

What it does -When you run the code, your webcam will start and on pressing key 'c', you will be able to listen to the description of the objects that you show to the camera. 

How we built it -We used Google Could API to read an image and detect the objects in that image. Then we wrote code to take live video and used image detector on this video to get the description of the objects in the video. Then we used Google Could API to convert text to speech and converted a text file in mp3 file and then read the mp3 file to the user. 

Challenges we ran into -Linking up credentials file with the code.

Accomplishments that we're proud of -We are proud of our project because we are going to help a lot of people in the world.

What we learned -We learned a lot about Google Cloud APIs. Also it was a good opportunity to realize that there can be so many cool things that can be done with these APIs.

What's next for The-Vision -We are expecting to attach the live camera to the gloves and have a headphone to listen to the descriptions(output). Also, we are planning on creating a chrome extension that helps blind people listen to the websites including pictures, videos, etc. We are going to try to make this product as cheaper as possible so that most people can make use of it.

Built With -Python, Google Cloud APIs (Text to speech, Image detector)
