## SSD-1 R&D Showcase-


### About the project-
It is a virtual R&D Showcase that lets various labs of IIIT hold their exhibitions. Since the world was engulfed by a global pandemic barring every kind of social activity, we tried to bring the essence of the famous IIIT showcase to the living rooms. Here, a user can select from the menu of available labs hosting presently, and take a tour of that lab's exhibitions.

### Features implemented-
* Json file contains information about participating labs. Data is fetched from there.
* Room size is created dynamically according to the user selection of particular choice.
* Posters change according to user selection of particular choice.
* Json file can be edited to add or delete posters and rooms.
### Issues remaining to be fixed-
* Menu plane was planned to be as a slider initially where next and previous buttons loaded new and previous lab options. This could not be implemented as the append feature of javascript was not responding as desried to the click event. Issue remains to be solved. Hence for now, the plane is not a slider.
* Video elements were attached that worked fine statically but misbehaved again on the click event when loaded dynamically. Issue remains to be solved. Hence for now, posters in the form of videos have been removed.
* Resetting the camera position is not resetting the scene location after first time. Hence for now, user has to walk back outside to the menu plane to change his choice.
#### Dependency to run the code
* Browser should support webVR
* device should have internet connection.

#### How to navigate
* When the link is opened, user is taken to a scene which has a lab loaded by default.
* To view options of available labs, user has to click to the initial welcome image.
* It loads a menu plane containing names of various labs participating in the showcase. User has to take the navigation cursor to the image and select the desired option to visit that lab.
* User can then use their left/right/up/down keys to move left/right/forward/backward respectively.
* User can also use mouse press to rotate the scene position.

#### Illustrations for navigation-
* User has to press here to load the menu options
![Screenshot from 2020-11-22 20-00-01](https://user-images.githubusercontent.com/30933610/99906707-918a3000-2cfe-11eb-8324-df6bf051df23.png)
* User has to select a room from the menu here by clicking on it

![Screenshot from 2020-11-22 20-00-43](https://user-images.githubusercontent.com/30933610/99906763-df9f3380-2cfe-11eb-99ad-e093e4260f8d.png)
* After that that respective lab will be loaded with its posters. User can take a tour inside that room and read the posters. Example of a poster on the partition wall-

![Screenshot from 2020-11-22 20-05-35](https://user-images.githubusercontent.com/30933610/99906788-107f6880-2cff-11eb-9d98-725c38d15a45.png)

#### Presented by-
* Nayanika
* Adrija Chakraborty 
* Neha Agarwal 
* Mohsin Husain
