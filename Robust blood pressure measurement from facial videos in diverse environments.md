## Abstract
#### Motivation 
```txt
Like we can measure the blood pressure with our traditional spyghmomanometer so why do we want to derive some new technology for the same thing?
Reasons -:
1) It causes foreign touch and discomfort
2) It is not practical to use remotely / or cant be used for periodic monitoring
```
#### New term - : Photoplethysmography(PPG)
```txt
- Photo - light
- Plethysmos - Expansion or increase
- Graphy - measurement
- Technique which uses light to measure the change in volume of blood in specific area. 
 ```
#### New term -: Pulse Transit Time (PTT)
```txt
Pulse Transit Time (PTT) is the duration it takes for a pulse pressure wave to travel between two defined points along the arterial system
```
#### New Term -: Pulse Wave Velocity (PWV)
```txt
Pulse Wave Velocity (PWV) is a measure of the speed at which the pressure wave travels along the arteries as the heart beats.
```
#### First method proposed
```txt
Utilization of two cameras to measure PTT and have focused on
internal environments
This method failed as External environments introduce variables such as changing lighting conditions, movement artifacts, and other environmental factors that can affect the accuracy of blood pressure measurements.
```
#### Solution
Use PWV and PTT calculated from the video
PTT -: Phase diff between 2 ROIs(Region of interests)
PWV -: $\frac{\text{Actual distance between ROIs}}{PTT}$

- We extract pulse waves from ROIs
- Then these two pulse waves is used to find Actual distance between ROI and PTT
- Then we find PWV from ROI and PTT
- Then PWV and PTT is used to find BP
