# Fastball_Velocity

Project Objective

The objective of the project is to attempt to find out the numerical difference or indifference that fastball velocity has on a pitchers' success in the MLB. Why would this matter? Pro scouts and college recruiters would take more consideration into numbers and current success instead of how projectable and their potential based on velocity and spin rates (or vice versa)


Structure of the Code-Base

The code contains a data file that is a 771 x 31 matrix. The Rmarkdown file does all of the following: It creates a histgram for a visual of average fastball velocity. Mulitple models are then constucted attempting to use velocity and spin rate as predictor variables for batting average, sluggling percentage, and swing-and-miss percentage. There are plots produced for each model for visual purposes.

There is also a pdf file of the Rmarkdown to allow the veiwer to see the model summaries and plots without downloading the dataset.

How to Recreate Results

The data set comes from Statcast. The url http://baseballsavant.mlb.com/statcast_search will bring you to a site that can constuct dataframes from all the MLB stats recorded over the past 40 years. For this project I selected all four fastball types (Pitch Type), all out  results and base hit results (PA Result), Regular Season (Season Type), 2018 (Season), Pitcher (Player Type), Player Name (Group By:), and Avg. Pitch Velocity (Sort By:). This will produce a matrix with 771 rows that represent all the pitchers in the MLB that threw a fastball during the 2018 season that resulted in a base hit or an out.

Baseball Terms

ba = "batting average" - the number of hits divided by at bats

slg = "sluggling percentage" - represents the total number of bases a player records per at-bat. The formula for slugging percentage is: (1B + 2Bx2 + 3Bx3 + HRx4)/AB

velo = "velocity" - represents the maximum speed of a given pitch at any point from its release to the time it crosses home plate

spin rate - represents the rate of spin on a baseball after it is released. It is measured in revolutions per minute




