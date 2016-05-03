# TreeFinder

The TreeFinder app provides an interactive experience targeted towards children to teach them how to identify and discover new species of trees. This project was created with Android Studio with a minimum supported SDK version of 16 and a targeted SDK version 23. 

This app was based off of the Tree Finder book which is a sort of "pick your own story" guide to identify trees. It asks a series of questions about the tree's characteristics and guides the reader along. We implemented this decision tree in an XML file to allow for future expansion. Currently only one branch of the decision tree is implemented, which is a small portion of the entire book's decision tree. Each of the nodes on our decision tree is an XML element in an XML file. Each element has the node's identifying question, answers and image URL's used on the Android Activity's layout as ImageButtons representing the possible answers. Future expansion of the decision tree will be done by modifying this XML file only. You will not have to modify any of the code within the Android project. In this way, we have planned for expansion to make it as easy as possible and requiring minimal technical expertise. 

## Future Work
1. Expand the Decision Tree to Encorporate all of the Trees from the Tree Finder Book.
   
<Put more detail here>

2. Update the Images to Make Them Higher Quality and Original. 

Currently the images we used are low-res scans from the book. They are copywritten material and could not be used without permission from the book's copywright holder when the app is released. Also, the quality of the scans is relatively poor. Providing higher resolution, original images will greatly enhance the look and feel of the app.

3. Host the Images on a Private Server

The images we are using are currently being hosted on imgur. They are referenced in the XML file by their URL. A more robust and future-proof option would be to host them on a private server specific to the app. Provided the images on this server have unique URLs associated with them, the only thing that would need to be changed is the respective URL in the XML file.
