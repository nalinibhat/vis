Visualization (Udacity project 5)


Summary
The chart compares left handed Vs Right handed baseball players who have similar Body Mass Index. For comparing I have used the Home Run as a metric. Baseball players with higher Home Runs are typically famous & amongst the highest paid players.

------------------------------------------------------------------------------------------------------------------
Initial Design (baseball_v1.html,baseball_data_v1.csv)

I selected bar chart, because I have categorized the players on the basis of their BMI & Bar charts are best suited to depict categorical data. I have selected different colors to differentiate between normal & overweight players.


Feedback 1
Initially I had represented left & right handers using color encoding. But, I got the below feedback:-
1)	The user had to switch his sight multiple times between the chart & the legend to understand if he is looking at left hander or right hander. So, the message conveyed was not very clear. Viewer initially thought I was showing performance between normal & overweight players. But, I had initially intended to show performance between left handed & right handed players. But, I can leave it to the viewer to do the comparison based on either BMI or handedness.

2) Context to the chart was missing. 
3) The chart could have been in the center, with its size adjusted.

Design changes 1:-
 I changed the chart, by showing BMI in color encoding & handedness in x axis.
I added some context before showing the chart
I added 2 charts, so that I can show comparison between average score & also HR.


Feedback 2:-
1.	Did you consider 0 values in your analysis on average vs handedness
2.	Did you eliminate the zero's from Home Runs average?
3.	Could you show the BMI as part of the tool tip
4.	It will be good if you can expand the abbrevations used in x axis
5.	In the second graph, the y axis ticks seems to be repeating. Could you try overriding them
Feedback 3:-
1.	Why are the graphics repeated below? I couldn't see any difference. They repeated graphics showed up after a short moment. Maybe a rest of an animation?
2.	The color codings are flipped on left vs. right. I think they should be the same.
3.	The categories (R,L,B) are very abstract. They could be explained more.


Design changes for feedback  2 & 3:-

I eliminated the players with 0 as average score, even while comparing HR. It could be that the players with 0 averages never got to a chance to hit or may be the data was missing. There are also slight chances that the player actually scored 0. While eliminating 0, I have ignored that rare possibility that the player actually scored 0.
Just to make sure that the viewer understands the BMI value of normal & overweight range, I included it in the context.
The abbreviations on x-axis were expanded & also the y-axis ticks were adjusted.

I made the legend color to be common  for both the charts. I could understand that the 2 charts looked almost the same & the user was not able to differentiate between them (even though one was for average HR & the other for average scores). To resolve this I placed the chart one below the other & gave some explanation to make sure viewer notices the difference.

--------------------------------------------------------------------------
Resources - list any sources you consulted to create your visualization
http://dimplejs.org/index.html

