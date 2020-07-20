# Kickstarter-Challenge 

### This project is aimed to compare how different each campaign fared in relation to their launch dates and funding goals after Louise's play Fever came close to its fundraising goal in a short amount of time.  

## Analysis and Challenges

From the provided Kickstarter dataset, I extracted datasets linked to campaign's success or failure in relation to its campaign dates and goals. I also used line graphs to better visualize the data relations. There weren't any challaneges encountered since I have a large and reliable dataset. Possible challange will be if such dataset was not available or the set is too small to draw reliable conclusion. Lastly, for the percentage columns, I compare the Number Successful, Failed, and Canceled to Total Project sums which yields a percentage.  

### Analysis of Outcomes Based on Launch Dates 

In this analysis, I extracted outcomes based on launch dates from the Kickstarter dataset, and filtered it to theatre as prompted. 

### Analysis of Outcomes Based on Goals 

Here, I created a table listing goal values down the rows and number and percentage successful, failed, cancel, and total number of projects across on the columns. I used COUNTIFS() formula to populate the first three column: Number Successful, Number Failed, and Number Canceled. Then, I used SUM() to tally up total number of project in each range as specified in the rows. 

## Results

The theatre outcomes based on launched dates indicates that campaigns that were launched in April has the highest success rate. The following spring and summer months also tend to fare better than those launched in early fall. Overall, the chart indicates that theatre campagins fare well on Kickstarter as most of them are successful and very few are canceled. 

The outcomes based on goals has an inverse relationship between the successful and failed campaigns. The line chart indicates that between 60-80% of of the campaigns ranged from less than $1000 to $4999, and $35000-$44999 are successful. Whereas the higher set of ranged goals of $45000-$49999 and greater has the smallest rate of success and the highest rate of failure. This relationship would be less noticeable if projects as a bar chart. 

I really can't think of any limitation of this dataset as since it's a large and dependable set. 

Both outcomes can also use bar graphs to visualize the data since there are only three criteria used for comparison: successful, failed, and cancel. The bar graph will provide an clear comparison of the critieria, although I would still prefer the line graph espcially for outcomes based on goals as the reader can at once see the inversed relationship between percentage successful and percentage failed. 
