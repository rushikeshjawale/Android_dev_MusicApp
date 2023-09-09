# Android_dev_MusicApp

Music Application Using Java
Project Description:
In this project I have created the music application by using Android Studio and java as my main language.
This is simple learning project created to showcase my skills in java.

I Select the Empty activity and select Java as my base language to work with. At the start of the project, 
we get 2 files to work with i.e. "MainActivity.java" and "activity main.xml ". Below are the steps to create this application.

Steps:
1) First, every application needs permission to read all the music files available in the external storage of the Android device.
   So I created the permission in the file "AndroidManifet.xml"  located in the file name "manifests" to read the external storage of the device
   Then, in the Second step I changed the "Constraint layout" to "Relative layout" as I wanted to use the ID of the UI components to align them accordingly.
   If I used a Constraint layout then I had to use the constraints to align all my components.

2) Then, I add the "TextView" in which I "wrap_content" the width and height of the text as it will wrap the content in screen and create a virtual box whose size will be set according to the number of text.
   I also set the text color to black, and set the text to "SONGS".
   I also set the text size to 20dp and the text style to bold and I gave padding to the text to 10dp and set the text horizontally to centre.
   Below this created "TextView" we will see all the songs available for external storage.

3) To display all songs available in device storage I created the "RecyclerView" as it makes it easy to efficiently display large sets of data.
   It will recycle the individual music files and display them on the Android screen according to our command.
   I set the id to the Text view of the songs and then I set the recycler view below the song text Id.
   Here I “MatchParent” the width and “WrapContent” the height of the list of the songs.

4) I created another "TextView" as "NO SONGS FOUND" if their are no songs present in external folder.
   I wrap_content the height and weidth of the text. I set that text at center and set ID

Authors
@Rishikesh Jawale
🔗 Connect with me
linkedin


