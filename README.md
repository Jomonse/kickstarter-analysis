# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarte data to uncover trends

First we have a database with 4113 titles of different recreational content such as film & video, plays, musicals and so on. We have a brew description of wath is about each one and the coutrys where there were watch. They have and identificator and important information for an investor like goal, pledged, if it was a success or a failed, if they had backerys before and the time they were released or were playing. Also they have an important column that tell us the percentage of return based on the invest and the profit.

Some analysis were made with this information:
1. Outcomes Based on Launch Date
  Basically the analysis were about if the time of the year was significally on the launchig date to the outcome, the answer were yes and the best month to launch      something is on May.
    ![Outcomes BAsed on Launch Date](https://user-images.githubusercontent.com/21062253/135364373-4f843dc4-52ba-496e-837d-94f4c8ad8745.png)
    
2. Then the analysis were focus on the type of content and see wich one is more successful than the others
  First the focus were on the category, the result was that teather is more successful than the other categories
  ![Parent Category Outcomes](https://user-images.githubusercontent.com/21062253/135364916-fa262cb5-4d7f-4adb-93d8-d819fe42ca9f.png)
  
  Then the focus were on the subcategory, were the result was that plays are more successful than the others
  ![Subcategory Statistics](https://user-images.githubusercontent.com/21062253/135365090-0f55fe2b-2a59-4686-b6b4-db6a87aa9bba.png)
  
In conclusion we can say based on the results that if you want to launch something, you should lauch a teather play.

So the information is clear, plays is the best option to take, but how much do we can spect to earn in an especific country such as US, well using descriptive statistics is possible to see the data behaviour on what's the goal and the pledge
![imagen](https://user-images.githubusercontent.com/21062253/135365571-5d0a82a0-2aa3-4fb9-8ce1-90c6c1aca9a3.png)

The result was that in a successful scenario the results beetween what is espect vs what is the real result don't vary significantly, obviously when it is failed they does, but in general you earn what you spect.

Finally it is important to know how to invest, for this analysis the focus were on Great Britain because on of our invest wanted to launch a musical in this country, so the decision was to made a boxplot to see what was the smartest investment.

![GB boxplot](https://user-images.githubusercontent.com/21062253/135366176-7b5f7352-c6e3-4e48-995e-18b7701dd079.png)

Here we can see that the smartest invest should be under £2000.

More or less this is the information you could see on this Excel but you can downloaded and make you're on analysis, have fun!

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Kickstarting with Excel

## Overview of Project
In this project 2 analysis were made, one was to see the putcomes based on launch date and the second one was to see the outcomes based on goals. The taken information was the same data used before with the 4113 titles of the diferent types of content.

### Purpose
The main purpose of the analysis was to see the behaviour of the outcomes of the theater and the plays, the first one based on the month that it was launched and the second one was based on outcomes obtained respect the goal that was settled.

## Analysis and Challenges
For the both analysis was neccessary to read carefully the instructions of what was expected, for the first one was really helpful to see the following image:

![hint deliverable 1](https://user-images.githubusercontent.com/21062253/135382020-2191f555-bf61-478b-9eb9-1b8578699296.png)
                                                   _Image 1: Hint Pivot Table_
                                                  
Because it could be a little confused to know what data colected in the pivot table and where to drag it, but the image clear your doubts and help you to be sure what you're doing and if the result is the expected.

The second analysis were a little bit more difficult, more because I have excel in spanish and the function name was different of what I believe, also at first I was using the function bad and I did'n understand what I was doing wrong, but the following video clear my doubts and then I was able to do it right:
           
              https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842?ui=en-us&rs=en-us&ad=us
                                                  
### Analysis of Outcomes Based on Launch Date
In this analysis a pivot table was made to see the outcomes respect to the month that a theater was launched, then a line chart was made reflecting the following results:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/21062253/135376218-48c78add-cad4-4fbf-a100-809a1c935e7f.png)
                                                    _Image 2: Outcomes Based on Launch Date_

1. May is the best month to launch a theather
2. If a theather is launched in october it is probably that it would not be canceled, also is the third month with more successful theaters. The second one is febraury
3. It could be said that there is the same probability of failure or success if a theater is launched in december

### Analysis of Outcomes Based on Goals
In this analysis the following table was created:

![imagen](https://user-images.githubusercontent.com/21062253/135377253-ef00954c-4a86-4736-baa0-de041fab8843.png)
                                                  _Table 1: Outcomes Based on Goals data_

For the creation of the table a function called countifs() was neccessary, where it filters for the plays the information based on the goals established in the first column of the table and the outcomes (successful, canceled, and failed). Also for the information needed in the table for the analysis, the percentage of every outcome was calculated. Finnaly as in the first analysis a line chart was created with the information of the table:

![Outcomes Based on Goal](https://user-images.githubusercontent.com/21062253/135377741-1e6e44d2-cd1e-4758-8852-600da2099d4d.png)
                                                _Image 3: Outcomes Based on Launch Date_
                                                
 The chart tell us that:
 1. There aren't plays canceled
 2. If the goal is between 45000 and 49999 inclusive, there are 0% probabilities of success and 100% of probabilities to failed
 3. If the goal is less than 15000 there are more probabilities to success than fail.
 4. The lower the goal the better.

### Challenges and Difficulties Encountered

It was difficult to use different types of filter the information: by functions, pivot tables, boxplots, etc. But I think it would be more difficult in the future to know wich one use without having specific instruction, nevermind is usefull to know different ways so in the future we can fullfill the expectations of our clients.

## Results

 **What are two conclusions you can draw about the Outcomes based on Launch Date?**
 
  1. That is better to launch a theater on may 
  2. If you don't launched it in may it is better on october, becuase even it is the third month with successful outcomes it doesn't have canceled ones.

**What can you conclude about the Outcomes based on Goals?**

  You should reach a lower goal if you want a successful play.

**What are some limitations of this dataset?**

  That the results of each type of content depends on the consumer, and this one could be afected by many things such as what is on trend, what is happening on the     world, largest age group of the population, etc. One example is our reallity now that we're leaving a pandemic, because people started to use more streaming           platforms to see movies and series, because they couldn't go to a movie teather or to another recreation place.

**What are some other possible tables and/or graphs that we could create?**

  We can made analysis based on another types of parent categories, analysis based on the countrys or the years, etc. For example this analysis of what parent           categorie is more successful in the world:
  
  ![World's successful parent categories](https://user-images.githubusercontent.com/21062253/135382305-d80173e8-6aa0-4551-9f9d-55a780312c77.png)
                                                            _Image 4: World's successful parent categories_

Were the result was that teather is the more succesfful parent categorie around the world!

