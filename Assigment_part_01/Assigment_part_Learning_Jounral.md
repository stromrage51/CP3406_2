# Assigment 01
Name: Matthew Ballarino

# Learning activities: 

## Process:
    I first created the XML files I needed such as main_activity.xml and layout for the recipe and settings. I used the main_activity as the home page as I thought it would look better and created a second empty activity called View_Recipes that displays the recipe. I then created the necessary class's need for the main activity to access the buttons to activate other activities. I then created the data class Data_Recipe to store the data and created the adapter class for displaying recipes in the recycle view. Then I created the load recipe function in the View_Recipes to load the recipe data into an array and remanding the adapter the data has been changed. Then array is read into the recycle view displaying the recipes. 

    For the settings page at first, I used a textbox for the text font but changed to a spinner as it was easier to use to change the text size, used a toast to show that change in the font has occurred. I encountered a problem at this time the change was not carried out on other pages except settings_page. I created the background colour spinner next to see if the problem was still there it was. So, I created the function apply settings after I looked up online for so long to fix the settings problem this function was used to apply the changes made in the settings then used the onResume function to call the activity and reapply the changes made in settings. 

## Problems: 
    Originally I planned to create a recipe app that allows you to create your recipes I ran into a problem; I couldn't get data stored in the database that was created by the user into viewing activity Every time I tried it crashed I don't know what the problem was. So instead, I created a new list that has predetermined information as run out of time. I just couldn't get the ROOM library working for me correctly so creation_activity was made pointless.  
## Videos I used: 
    For the data class: 
        https://www.youtube.com/watch?v=oFli6rYejUQ

    For the recipe app inspired by: 
        https://www.youtube.com/watch?v=6-891CSz6v0 

    Understanding room: 
        https://developer.android.com/training/data-storage/room#kotlin 

    For auto sizing the text: 
        https://www.youtube.com/watch?v=9LTFmn_4Okk 

    For changing the colour of the background: 
        https://www.youtube.com/watch?v=DpyJZ-f6xVg 



## Conclusion: 
    I am happy this app is made and has learned a lot from this app, I am disappointed that the app doesn't work the way I intended to as couldn't allow the ability for users to create custom recipes as run out of time trying to work it out the database. 

# Estimated Hours
    I dedicate around about 8 hours and 30 minutes a day from the beginning of June to the end of June except for working on projects that include practicals.

# Content Insight: 
    -	Data Class and Adapters:
        o	Gained valuable insights into the connection between data classes and adapters.

    -	Settings Recall: 	
            o	Learned to apply settings changes across activities, which will be useful in future projects.

    -	Database with ROOM: 
        o	Explored database management using the ROOM library.


    -	General Knowledge: 
        o	Acquired comprehensive information on various Android development aspects.


# Career/Employability/Learning Insights:
    I am planning to go back on this app as I still want to make the database work knowing would be important to have when looking to get employed as help me to be more distinguished over other employees. This experience has provided a strong foundation in Android development, and overcoming the database challenge will further enhance my skills and employability.
