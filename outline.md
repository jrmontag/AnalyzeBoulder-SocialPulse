# The Social Activity Pulse

### sketch
2013-02-05, 10 mins, general public, min('how'), max('what'|'why') 

### take-aways
1. classes of activity & why helpful 

2. social media pulse (many simultaneous observers) & sigmoid (network spread) models (maybe) 

3. what we can do with that information

---

# outline *(WIP)*

- ~a decade into the [social data revolution](http://blogs.hbr.org/2009/05/the-social-data-revolution/) = mucho data

- new channel for making measurements of social and humanitarian issues (unemployment, illness, politics), cheaper and more real-time than e.g. government census 

- how much data? (+ grapherator twitter data) -- everything from the Golden Globe awards show to the current Ukrainian riots is in that data 

- many reasons why you might want to be able to describe and classify events in that data stream, eg: 
            
    - compare evolution of stories with different scales  

    - compare user behavior across platforms  
    
    - identify emerging stories & source type



## event classes

### expected (+data) 

- golden globes ( 2014-01-12 ) / SAG ( 2014-01-18 ) 

- winter storm janus ( 2014-01-21 ) 

### unexpected (+data) 

- *social media pulse* (many simultaneous observations / multiple sources): CA quake ( 2014-01-15, fontana/LA ) 
    
- *network spread* (single- or few-source): bin Laden strike (before traditional media), syrian dissidents *(newer example* 
    
- [ *hybrid* : AP hack ( 2013-04-24 ) ]



## unexpected event models

### social media pulse

counting user activities in time: Poisson process (stochastic, positive integers) 

time between pairs of observatations has an exponential probability distribution 

gamma distribution from sum of all uncorrelated users (?)    

parameters: t_0 (start of pulse), alpha (shape), beta (rate), 

model building/fitting in Python (scipy)



#### pulse characteristics  

- time-to-peak

- story half-life

- total story activity volume


### network spread 

story breaks on twitter (single-source or few-sources), shared widely, growth rate increases quickly

message reaches network saturation, stops being shared

logisitic/sigmoid function



# to do

- cross-social-platform comparison of models

- (non-parametric) trend detection



