# bikesharing [Link to Tableau Story](https://public.tableau.com/views/BikeSharingChallenge_16753972024660/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

**Overview of the project

There is business proposal for investors which is bike-sharing program in Des Moines. To solidfy this proposal, bike trip analysis needs to be performed. 

That is why , I created set of visualizations to :

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

** Sources 

Data Source : 
These visualizations are created by using following resources 

NYC_CitiBike_Challenge.ipynb, 201908-citibike-tripdata.csv
Data Tools : Jupyter Notebook,Tableau, cSV
Software : Jupyter Notebook & VS Code

Performed following three deliverables -

**Deliverable 1: Change Trip Duration to a Datetime Format

Used Pandas to change the "tripduration" column from an integer to a datetime datatype. After conversion "tripduration" to a datetime datatype, exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

**Final result looks as below : 

![image](https://user-images.githubusercontent.com/40743420/216501889-bbc9590b-3ff2-46b5-b369-52a987b5d6f8.png)


**Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, create visualizations that show:

How long bikes are checked out for all riders and genders.
How many trips are taken by the hour for each day of the week, for all riders and genders.
A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

In this visualization, I graphed the length of time that bikes are checked out for all riders.
Final result looks as below : 
**Trip Duration

![image](https://user-images.githubusercontent.com/40743420/216501670-8a01200a-9c1c-41ed-926f-b20278496570.png)

**Trip Duration by Gender

![image](https://user-images.githubusercontent.com/40743420/216509763-b7b489af-9863-4506-b457-c2760f32bd84.png)

Now, see the frecquency of trip length broken down by gender. Along with a comparitive analysis of the gender breakdown of Des Moines, this will help us estimate the popularity of renting bikes amongst different genders. Again, to view the data per hour more clearly, click to filter the different hours of length of bike trips.

**Weekday Popularity

![image](https://user-images.githubusercontent.com/40743420/216662848-37dc5a9e-5649-4563-a607-444f2f08a5f7.png)


Toggle between the days of the week to see how the peak hours differ, and hold your cursor over a tile to see the number of riders it represents. It appears that the most popular time to ride is rush hour, 8am and then 5-7pm. However, you can see that the weekends between 11am-8pm are also high use times, as there are over 15K rides occuring.

**Weekday Popularity by Gender

![image](https://user-images.githubusercontent.com/40743420/216665488-676a2204-6d4f-4a4b-a0b0-5fb6c35ce21e.png)

Here you can toggle between days of the week or differen gender types (male, female, and unknown) to compare bike usage. For both male and female riders, the weekdays during rush hour are the most popular times to ride, while for gender of unknown, the weekend rides are more popular. This begs the question, is there a difference in entering user data between weekdays and weekends? Is there a difference in the user types and likeliness to leave the gender as "unknown"?

![image](https://user-images.githubusercontent.com/40743420/216668145-50be1798-d2bf-4cd1-8f12-4659ac41c1df.png)

The data broken down by Weekday, User Type, and Gender shows that male subscribers are riding the most frequently. Click to filter the Weekday, User type, and Gender to drill down into the results. Looking at all the data toether, we see that Male subscribers are taking the majority of the rides, so if you want to see increased success, it would be beneifital to focus your marketing on female customers.

Deliverable 3: Create a Story and Report for the Final Presentation
