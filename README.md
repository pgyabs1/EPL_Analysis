# English Premier League Data Exploration

## Dataset

The data consists of information on 760 english premier league matches played during the 2019/2020 and 2020/2021 seasons. The information contained
in the dataset is explained in detail in the key (legend) below.

## Key to dataset (legend for columns):

Div = League Division
Date = Match Date (dd/mm/yy)
HomeTeam = Home Team
AwayTeam = Away Team
FTHG = Full Time Home Team Goals
FTAG = Full Time Away Team Goals
FTR = Full Time Result (H=Home Win, D=Draw, A=Away Win)
HTHG = Half Time Home Team Goals
HTAG = Half Time Away Team Goals
HTR = Half Time Result (H=Home Win, D=Draw, A=Away Win)

Match Statistics (where available)
Attendance = Crowd Attendance
Referee = Match Referee
HS = Home Team Shots
AS = Away Team Shots
HST = Home Team Shots on Target
AST = Away Team Shots on Target
HHW = Home Team Hit Woodwork
AHW = Away Team Hit Woodwork
HC = Home Team Corners
AC = Away Team Corners
HF = Home Team Fouls Committed
AF = Away Team Fouls Committed
HO = Home Team Offsides
AO = Away Team Offsides
HY = Home Team Yellow Cards
AY = Away Team Yellow Cards
HR = Home Team Red Cards
AR = Away Team Red Cards
HBP = Home Team Bookings Points (10 = yellow, 25 = red)
ABP = Away Team Bookings Points (10 = yellow, 25 = red)

## Summary of Findings

In the exploration, I first tried to assess what total number of goals was most common for matches and 
found that most games commonly featured a total of 2 or 3 goals. I also explored further and realised that
the second half of games usually featured more goals than the first halves.

I went ahead to remove betting odd statistics from my dataset because they were not going to feature in my
analysis and removing them was going to make my dataset slimmer and easier to work with. 

I then further explored if the absence of fans from stadiums had any effect on general win percentages for 
home and away teams. I did this by finding win rates for the home and away teams for games played with fans 
and those with no fans. Exploring the dataset confirmed that home advantage was actually really impacted by 
the absence of fans at the stadiums.


## Key Insights for Presentation

For the presentation, I generally focused on win percentages for the home and away teams for matches
played with fans in the stadium and those played without fans in the stadium. I was able to use a 
pie chart to show how home teams won 45% of matches played with fans at the stadium while for matches 
played with no fans at the stadiums, both home and away teams won just over 38% of them with 22% ending
in a draw. 

I was also able to expand this to individual team level. The impact of having no fans at stadium was
explored for Liverpool, Newcastle United, Sheffield United and Leeds United. These teams were selected 
because they are widely acclaimed to have the best stadium atmospheres in the EPL and are usually very hostile 
to away teams. It was observed from the dataset these teams were indeed negatively impacted with having no 
fans at the stadium. 
