- very high speeds
- low altitudes (500-1200km) [[kasliwal_2023.pdf#page=5&selection=35,35,36,22|kasliwal_2023, page 5]]

information extracted form [[kasliwal_2023.pdf#page=5&selection=0,1,4,9|kasliwal_2023, page 5]]
### Pros

reduce total loss

### Cons

it is difficult for the satellite to communicate with the ground station because of its high speed, which introduces a shorter window of conducting the experiment 

higher speed => shorter window 

##### What equivalent channel does IR see?
##### Is the channel stationary? What assumptions are made?

non-stationary because of the satellite motion and atphmospheric turbulence [[wang_2023.pdf#page=3&selection=136,0,143,61|wang_2023, page 3]]

##### What QBER/SNR range must the reconciliation engine support?

avg QBER 1.1% [[liao_2017.pdf#page=9&selection=1,16,2,15|liao_2017, page 9]]
QBER between between 1%-#% under different weather conditions [[liao_2017.pdf#page=9&selection=29,20,29,68|liao_2017, page 9]]

! check figure 3c from [[liao_2017.pdf]]

##### How fast does the channel drift?
satellite orbital velocity = 7.6 km/s [[liao_2017.pdf#page=5&selection=19,59,19,84|liao_2017, page 5]]

273s?? and also Fig 3a [[liao_2017.pdf#page=8&selection=19,64,21,6|liao_2017, page 8]] but I will have to check this again 

##### What RTT is available?

bandwidth 1Mbps uplink and 4Mbps downlink [[liao_2017.pdf#page=8&selection=2,46,4,46|liao_2017, page 8]]

##### How many reconciliation rounds are feasible?

low interactivity is required here because of the speed of the satellite, one-way protocols are suitable here (interpretation)

##### What block-size budget is available?
sifted key 1.6 * 10^6 bits [[liao_2017.pdf#page=8&selection=21,19,21,33|liao_2017, page 8]]

rate: > ~12 kbit/s at 645 km to ~1 kbit/s at 1200 km

[[liao_2017.pdf#page=8&selection=22,14,22,58|liao_2017, page 8]]

secure final key ~ 300939 bits [[liao_2017.pdf#page=9&selection=10,13,10,20|liao_2017, page 9]]







