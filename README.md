# Predicting the Trajectory of a Paper Airplane through Mathematical Modelling
### A Physics and Mathematical approach to analysing the trajectory and flight phases of paper airplanes at different initial launch (pitch) angles

Paper Airplanes are a  cheap and convenient modelling tool for the design of MAV (Micro Air Vehicles) as they both have low Reynolds numbers. Investigating the properties of paper planes can help us to better design MAVs.

We investigated the effect of the launch angle on the **2D trajectory** of the paper Airplane.

A multivariate spline polynomial regression model was used to predict the trajectories, and Physics insights were obtained from there. 

### Data Collection
A Suzanne Model paper airplane was folded with copy paper and a launching device with constant elastic force was used to launch the paper airplane at varying initial launch (pitch) angles from 0 to 40 degrees with intervals of 2 degrees, controlling the starting height at 1.00m

A high speed camera was used to record the trajectory from a perpendicular angle and the 2D trajectory was digitally tracked on a Tracker software, with the x and y coordinates at each time interval of 0.01s.

Each angle had a total of 5 flights conducted and tracked, resulting in a total of 105 trajectories.

