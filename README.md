# Golf Technology Impact on Drivers vs Short Game Clubs

Created by: `Roopa Patel, Steven Lee, Amit Patel, Samuel Parks, and Sean Jokhai`
Date created: `April 20th`

- - -

## Introduction
Anyone who plays the game of golf wants to hit the ball far off the tee.  Golf club manufacturers are always aggressively developing and marketing drivers that can hit the ball longer and straighter, while still within the limits set by governing bodies like the USGA (United States Golf Association) and R&A (Royal and Ancient Golf Club of St. Andrews).  Our belief is that drivers are the most “improvable” golf club through technology, irons being second, and last being the clubs used inside of 100 yards.  The clubs used for shots inside of 100 yards (let’s call these short game clubs) are typically wedges (gap wedges, sand wedges, lob wedges) and putters.  

We want to know if the constant focus on driver technology has left the short-game relatively untouched.  We’ll do this by looking at the stats of the best players in the world, the PGA Tour, across 2010-2018, and compare their performance off the tee with their short game performance.

   * `Hypothesis - Driving distance and accuracy has improved over the years, with an accompanying increase in short-game performance (<100 yards including putting)`

   * `Null Hypothesis - Driving distance and accuracy has improved over the years, while short-game performance (<100 yards including putting) has remained the same`

## What are we looking for?

### DRIVING PERFORMANCE STATS
Driving Distance - (AVG.): The average number of yards per measured drive. These drives are measured on two holes per round. Care is taken to select two holes which face in opposite directions to counteract the effect of wind. Drives are measured to the point at which they come to rest regardless of whether they are in the fairway or not. (101)

Total Driving - (TOTAL): Total Driving is computed by totaling a player’s rank in both driving distance and driving accuracy.

Total Driving - (TOTAL) = “Total Driving - (DISTANCE RANK)” + “Total Driving - (ACCURACY RANK)”

### SHORT GAME PERFORMANCE STATS
Proximity to Hole (ARG): The average distance to the hole (in feet) after hitting the ball onto the putting surface from around the green. Only those shots determined by a laser will be included. (Note: ‘Around the green’ indicates the player is within 30 yards of the edge of the green). (374)
Of interest to us:
* `Proximity to Hole (ARG) - (AVG DTP)`
    * `Proximity to Hole (ARG) - (SCRAMBLING RANK)`

Short Game Rating - (RATING): An aggregate score based on several ‘Around the Green’ statistics used to measure a player’s performance 100 yards and in (not including putting). The statistics used to compute this are: Scrambling, Proximity to the Hole from sand, PTH from Rough, PTH from fringe, PTH from less than 100 yards and Greens in Regulation from less than 100 yards. (87)

### PUTTING PERFORMANCE STATS
Putting Average - (AVG): The average number of putts per green in regulation. By using greens hit in regulation, we are able to eliminate the effects of chipping close and one-putting in the computation. (104)

Total Putting - (TOTAL): Total Putting is computed using 6 putting stats Putting from 3-5', Putting from 5-10', Putting from 10-15', Putting from 15-20', Putting from 20-25' and Three Putt Avoidance from > 25'. Each statistic is given a numerical weighting based on the frequency of putts attempted from each distance. The players rank in each of the statistics used is multiplied by the corresponding weigh factor, totalled, and divided by the number of statistics used to produce the Total Putting Value. (2428) 

## Data Summary 
- Our data source is “PGA Tour Golf 2010-2018 Data” from Kaggle.com
    * The data is described as “Every statistic recorded on the PGA Tour from the 2010 to 2018 season”
    * URL: https://www.kaggle.com/bradklassen/pga-tour-20102018-data/version/4
- There are two versions of the data file
    * One version has the data vertically, while the other has the data horizontally
    * 