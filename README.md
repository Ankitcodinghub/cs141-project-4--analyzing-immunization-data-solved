# cs141-project-4--analyzing-immunization-data-solved
**TO GET THIS SOLUTION VISIT:** [CS141 Project 4- Analyzing Immunization Data Solved](https://www.ankitcodinghub.com/product/cs141-csci-140-project-4-analyzing-immunization-data-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;121388&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS141  Project 4- Analyzing Immunization Data Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
UNICEF maintains a database which houses data sets related to health, development, and other information related to maternal and child health. For this project, we will use immunization data maintained by UNICEF, which contains information on yearly vaccinations administered to children around the world. The vaccine data you have been given is sourced from: https://data.unicef.org/topic/child-health/immunization/.

This data considers vaccines for the following infectious diseases and agents (abbreviation for vaccine shown in all caps): tuberculosis, BCG; diphteria, pertussis, and tetanus, DTP1 and DTP3; meningococcal disease, MCV1 and MCV2; hepatitis B, HEPBB and HEPB3; Haeomphilus influenza, HIB1; polio, IPV3 and POL3; pneumococcal disease, PCV3; rubella, RCV1; rotavirus, ROTAC; and Yellow Fever Virus, YFV. Data is categorized as the percentage of children vaccinated, and is provided both globally and regionally (e.g. East Asia and Pacific, Middle East and North Africa, etc.).

You will create functions to process and visualize this data, and will write a main program that performs data QC and makes use of your functions. You have been given four files:

• vaccine_data.csv is a comma-delimited text file which contains all of the data

• Project_4.py is a skeleton file where you will write your functions, import lines have been provided for you, but you must write the def lines according to the specifications below

• Project_4_Main.py is a skeleton file which will contain your main program

In order to complete this assignment you must have functional versions of the following packages installed: pandas, numpy, matplotlib, seaborn.

BE AWARE:

Keep these instructions open on your Desktop while working and refer to them often. They will tell you exactly how to complete the assignment.

Part One: Data QC

The first part of this project requires reading in the file vaccine_data.csv and reformatting some of the data. It will be helpful for you to look at the data frame after each step. Ask if you don’t know what this means.

The code you have been given to debug will do the following:

-Read the data in from the file to a pandas data frame called vaccine, consider that there are no column names in the raw data

-Name the columns: ‘Region’, ‘Vaccine’, ‘Year’, and ‘Percentage’ (the quotes indicate that these are strings, there should not be quotes in the actual text of your column names)

-Update region names to remove spaces and ampersands, for example, ‘Eastern &amp; Southern Africa’ should be changed to ‘Eastern_and_Southern_Africa’

-Change the type of the Year column to a string

-Create a new column named Description that contains the full name of the pathogen or disease that the vaccine is administered for; you MUST use the dictionary provided to accomplish this task. This column will end up as the last column in the data frame – that is fine, you do not and should not move it.

If you are doing this in a notebook, we strongly suggest putting each line of code in its own cell. That way you can look after each step to see if things worked the way they should have. If you put the code all in one block, it can be very hard to figure out where the errors are originating.

Part Two: Functions

For this section of the project you will create 2 functions to use with your processed data frame or other data frames in a similar format.

Function 1: make_subset(df, region = None, vaccine = None, year = None)

Here are a few examples. So that you can clearly see what is happening, these examples make use of a small set of data. The data frame passed in for df in all of these examples consists of the following data:

Notice that the columns are not sorted in any particular way. You should not assume the data is sorted when writing your subsetting code.

Example 1:

df is the data frame from the introduction, vaccine is [‘PCV3’, ‘RCV1’, ‘HEPB3’]; function returns a data frame with the following rows:

Example 2:

df is the data frame from the introduction, region is [‘West_and_Central_Africa’], year is [‘1981’, ‘1987’]; function returns a data frame with the following rows:

Example 3: df is the data frame from the introduction, vaccine is [‘PCV3’, ‘HEPB3’]; region is [‘West_and_Central_Africa’], year is [‘1981’, ‘1987’]; function returns an empty data frame:

NOTE: if you have written your subsetting properly, you do not check for the case where the inputs don’t match any of the rows separately – this should happen automatically without you writing any additional code.

Key points:

• You can assume that the user will pass in inputs of the correct types and formats. df will always be a Data Frame, region (if passed in), vaccine(if passed in), and/or year (if passed in) will always be lists of one or more strings

• If you are reading in from a file anywhere in this function, you are doing it wrong.

• The basis of this function is subsetting a data frame. We have discussed this. If you are looking up pandas methods to append data frames to each other, pivot the data frame, or complicated code we didn’t talk about, you are probably doing it wrong.

• It is fine to hard code in the column names, like Region for example – that might feel funny to you, but you will need to do it

• If the user passes in a combination of arguments for which there are no rows that meet all of the criteria, you should return an empty data frame.

• Remember that if the user calls the function with no arguments for vaccine, year, or region, your function should return a COPY of the data frame.

• Don’t overcomplicate this. Our reference implementation is 8 lines long (not including the def line). We expect your code to be simplified and efficient. If you are creating separate cases for each possible combination of arguments, your code is overly complicated.

• Curious how to make a copy of a data frame? Use the copy method.

Function 2: make_plot (series_object, title =”, bar = True)

Write a function called make_plot that takes one required argument: series_object, a pandas Series that contains numeric (float or integer) values. The optional argument title is a string that is a title for the plot, and the optional argument bar determines what type of plot will be drawn as explained below. The make_plot function returns a plot that visualizes the data in series_object. The index of the Series should be reflected on the x or y axis as appropriate (see below). The type of plot differs by the value of the argument bar. When bar is True, the function produces a barplot, when bar is False, it produces a line graph.

Suppose you have a pandas Series where the Region is the index and the percentage is the data:

Region

Global 13

Eastern_and_Southern_Africa 2

Latin_America_and_Caribbean 28

West_and_Central_Africa 13

Name: Percentage, dtype: int64

We get the following plot when call make_plot function with series_object as the above series and bar is True:

Notice that the barplot is horizontal. You are not responsible for changing or moving the y-axis title (Region in this case).

We get the following plot when call make_plot with series_object as the above series and bar is False and title is ‘Test Plot’:

Notice that the labels on the x-axis are rotated 90 degrees. This should always happen for the line plot regardless of what the input is.

Key points:

• series_object is a Series, not a data frame. You can assume the data in series_object is numeric.

• You can assume the inputs are of the correct types (e.g. title will be a string etc.)

• All of the code for making the different plots are is in your notes/readings verbatim. Don’t spend hours searching the internet for something else. Use the course materials.

• When bar is True, make a barplot, when bar is False, make a lineplot.

• Don’t forget to have your function return the plot!

• Plots will show up in the notebook but not on the command line and that is OK. You can make them show up on the command line but we don’t want you to do that otherwise we can’t test your code remotely. If you add in code to make them show up, please comment it out before you turn your project in.

Part Three: Putting it all together

For this part of the assignment you will add lines to the main program to use the functions you wrote in Part 2 on the re-formatted data frame you created in Part 1. The lines of code you write for Part 3 will follow (i.e. go under) the lines of code from Part 1. ASK IF YOU DO NOT UNDERSTAND THIS – YOUR CODE WILL NOT WORK PROPERLY OTHERWISE.

Use your functions. You should not repeat code from the functions in the main program. Use good style – don’t pass in default arguments, and don’t provide unnecessary arguments. Some tasks will require additional code. This is indicated in the instructions. Read carefully.

• From the data frame you made above, create a pandas Series called BCG2019_Series that has the data in the Region column as the index and the data from the Percentage column as the values. The easiest way to do this is to create a new data frame with Region as the index and then select the Percentage column.

• Create a data frame called DTP1_Years that contains the rows from the vaccine data frame that correspond to DTP1 vaccinations in the East Asia and Pacific region. This will include all available years.

• From the data frame you made above, create a pandas Series called DTP1_series that has the data in the Year column as the index and the data from the Percentage column as the values. The easiest way to do this is to create a new data frame with Year as the index and then select the Percentage column.

• Create a line plot of the data store in DTP1_series with the title: DTP1 Vaccinations by Year in East Asia and Pacific Region

SUBMISSION EXPECTATIONS

Project_4.py: Your function code goes in this file. You have been given a skeleton file that contains the appropriate import lines. You must fill in the def lines and they must match the specifications exactly (HINT: look at the title for each section). Changing default arguments, the order of arguments, the number of arguments etc. is not permitted.

Project_4_Main.py : Your correction of data QC of the .csv file in Part 1 and the additional main program in Part 3 go in this file.

POINT VALUES AND GRADING RUBRIC

Part 1: Data QC (5 pts)

Part 2: make_subset (8.5 pts), make_plot(5 pts)

Part 3: Main program (6 pts)

Writeup (0.5 pts)
