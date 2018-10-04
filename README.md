# conveyor-IEC61499

## Usage
1. Run editor.bat in the fbdk directory
2. Open BaggageSystemCTL in the project repository
3. Press the RUN button


## Notes
* Once you run the program, to run it again you have to restart the fbdk editor
* FCOne, FCTwo, FCThree, FCFour are the controllers for the four input branches. TwoConCtl =  "Two Conveyor Controller"
* TCOne is the controller for the horizontal branch. ThreeConCtl = "Three Conveyor Controller"

* For Central Server, a function block must be designed that acts as a server to control an intersection
* For multicast and ring token, the exisiting controller function blocks should communicate with one another to control an intersection

## Implementation Details
* Adil: Central Server, Intersection #1 (FCThree * TCOne)
* Sylvain: Ring Token, Intersection #2 (FCTwo & TCOne)
* Mark: Multicast, Intersection #3 (FCFour & TCOne)

