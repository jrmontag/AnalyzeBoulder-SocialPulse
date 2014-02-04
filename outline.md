# The Social Activity Pulse

### sketch
2013-02-05, 10 mins, general public, min('how'), max('what'|'why') 

### take-aways
1. classes of activity & why helpful 

2. social media pulse (many simultaneous observers) & sigmoid (network spread) models (maybe) 

3. what we can do with that information

---

# outline 

- context (for social data)

    - ~a decade into the [social data revolution](http://blogs.hbr.org/2009/05/the-social-data-revolution/) 

    - channel for making measurements of social and humanitarian issues (unemployment, illness, politics), cheaper and more real-time than e.g. government census 

    - how much data? (+ grapherator twitter data) -- everything from the Golden Globe awards show to the current Ukrainian riots is in that data 


- need a way to describe and classify narrow / focussed events in large data stream, eg: 
            
    - compare evolution of stories with different scales, compare user behavior across platforms, identify emerging stories & source type


## expected v. unexpected

- examples 

    - expected: winter storm (Janus: ~2014-01-21) 

    - unexpected: news story? (google + nest ~ 2014-01-13?), disaster? 

- lines through each 


## *social media pulse* 

- a little taste of the model (formulas)

- poisson counting process where probability of an observer posting/sharing is exponentially decaying in time (+formula) 

- many observers ==> sum of independent random variables is the convolution of these ==> gamma

- example with data 

- example + parameters 


## event parameters 

- half-life ~ 18:40 UTC

- time to peak ~ 5 min

- story activity volume ~ ? 

- response time ~ ?
    
## what's next 

- models (network spread, hybrid, ...)

- cross-platform

- what else?

