AI ASSIGNMENT 3.
Kyle Mokua - 189801
Ryan Ngugi –192561
Einstein Ogamba -192078 

Question 1: PEAS Framework
Performance Measure :	Reach Kisumu safely and on time, minimize total travel distance (km) and fuel consumption, obey Kenyan traffic rules and speed limits, and deliver cargo without collisions or damage.
Environment :	Kenya's Highway Network (Nairobi, Central Highlands, Rift Valley, and Lake Victoria Basin roads), other road users (cars, matatus, buses, trucks, pedestrians), road signs/intersections, and weather conditions (rain, fog, hills).
Actuators :	Steering wheel/mechanism (turn left/right), accelerator/throttle, brakes, gear transmission, indicators, headlights, wipers, and horn.
Sensors :	GPS (Google Maps location tracking), cameras (lanes, signs, traffic lights),  radar (obstacle distance/speed), ultrasonic proximity sensors, and speedometer/odometer.

Pt 2 Definitions of agent environments
Partially Observable (vs. Fully Observable): The trailer cannot obtain complete information about its surroundings at every moment. Cameras and other sensors may miss objects, experience interference, or fail to detect hazards hidden behind other vehicles

Stochastic (vs. Deterministic): The outcome of an action is not always predictable because of changing road conditions, sensor uncertainty, and the unpredictable behaviour of other road users.

Sequential (vs. Episodic): Each decision affects later decisions and the state of the trailer. The agent must consider the consequences of its actions over time.

Dynamic (vs. Static): The environment can change while the agent is making decisions. Vehicles move, pedestrians cross roads, and weather or road conditions may change.

Multi-agent (vs. Single agent): The trailer operates around other road users, including drivers, pedestrians, cyclists, and potentially other autonomous vehicles. Their actions affect the trailer's decisions.



Question 2: Directed Graph, Search Tree & Abstraction (Circular Nodes)
Directed Graph:



Search Tree:

Question 3: 
Route A
Path sequence: Nairobi -> Naivasha -> Nakuru -> Eldoret -> Kitale -> Kakamega -> Kisumu
Step cost sum: 89.5 + 71 + 156 + 71 + 110 + 50 = 547.5 km

Route B
Path sequence: Nairobi -> Naivasha -> Nakuru -> Kericho -> Sondu -> Kisumu
Step cost sum: 89.5 + 71 + 45 + 52.6 = 365.1 km

Route C
Path sequence: Nairobi -> Narok -> Bomet -> Kericho -> Sondu -> Kisumu
Step cost sum: 141.5 + 81.5 + 74.25 + 45 + 52.6  = 394.85 km

Route D
Path sequence: Nairobi -> Narok -> Bomet -> Kericho -> Kisii -> Sondu -> Kisumu
Step cost sum: 141.5 + 81.5 + 74.25 + 87.2 + 61.3 + 52.6 = 498.35 km

Route E
Path sequence: Nairobi -> Thika -> Nyeri -> Nyahururu -> Nakuru -> Kericho -> Sondu -> Kisumu
Step cost sum: 44 + 110 + 104 + 64 + 107 + 45 +  52.6 = 526.6 km

Route F
Path sequence: Nairobi -> Thika -> Nyeri -> Nyahururu -> Nakuru -> Kericho -> Kisii -> Sondu -> Kisumu
Step cost sum:  44 + 110 + 104 + 64 + 107 + 87.2 + 61.3 + 52.6 = 630.1 km


Optimal Path Conclusion: The optimal path the trailer can take is Route B (Nairobi -> Naivasha -> Nakuru -> Kericho -> Sondu -> Kisumu), which has the lowest total path cost of approximately 365.1 km.

