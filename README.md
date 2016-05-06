# TreeFinder

The TreeFinder app provides an interactive experience targeted towards children to teach them how to identify and discover new species of trees. This project was created with Android Studio with a minimum supported SDK version of 16 and a targeted SDK version 23. 

This app was based off of the Tree Finder book which is a sort of "pick your own story" guide to identify trees. It asks a series of questions about the tree's characteristics and guides the reader along. We implemented this decision tree in an XML file to allow for future expansion. Currently only one branch of the decision tree is implemented, which is a small portion of the entire book's decision tree. Each of the nodes on our decision tree is an XML element in an XML file. Each element has the node's identifying question, answers and image URL's used on the Android Activity's layout as ImageButtons representing the possible answers. Future expansion of the decision tree will be done by modifying this XML file only. You will not have to modify any of the code within the Android project. In this way, we have planned for expansion to make it as easy as possible and requiring minimal technical expertise. 

## Future Work
1. Expand the Decision Tree to Encorporate all of the Trees from the Tree Finder Book.
   
Currently, only a portion of the total possible trees and questions are implemented. As can be seen here:
![tree](http://i.imgur.com/5EJZEcH.jpg)
The tree is rather large. However, it can be simply implemented using the xml file described above, following the format already in place, and using links to reference images.

2. Update the Images to Make Them Higher Quality and Original. 

Currently the images we used are low-res scans from the book. They are copywritten material and could not be used without permission from the book's copywright holder when the app is released. Also, the quality of the scans is relatively poor. Providing higher resolution, original images will greatly enhance the look and feel of the app.

3. Host the Images on a Private Server

The images we are using are currently being hosted on imgur. They are referenced in the XML file by their URL. A more robust and future-proof option would be to host them on a private server specific to the app. Provided the images on this server have unique URLs associated with them, the only thing that would need to be changed is the respective URL in the XML file.

4. Port to iOS

Using the same images and xml file, a similar system could be built as an app for iOS (by reimplementing the scaffolding in the Android App, the code that interprets the XML file, and by creating a UI that can be changed based on the xml).

## Expanding the content of the App

1. Uploading an image

Currently, as long as an image can be accessed via URL, it will work. We chose to use a site called [imgur](www.imgur.com) as our host for this semester, though as mentioned in future work, it would be ideal to host the images somewhere private or more easily controlled.

2. Adding a question node to the XML file

3. Adding a tree node to the XML file
