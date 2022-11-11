# bike_lot
The bicycle parking lot outside the LAB42 building. It is a one stock system; the stock is the number of available parking spaces for bicycles. The inflow of spaces is bicycles leave the parking space, and the outflow is when they arrive. 

The inflow and outflow are characterised by a mixture of continuous arrival and departure of bikes, however there is a predictable pattern in two-hour intervals. A group of tutorials or lectures are always starting from 9am and then either ending or beginning every two hours (11am, 1pm, 3pm, 5pm, 7pm). We can expect a sudden increase of inflow and outflow when a class ends. However, students stay longer to study and may arrive earlier as well. Therefore, we can expect a mix somewhere between the inventory model and the population model described by Meadows.  

On any day, we expect the inflow to match the outflow perfectly, as all students will eventually go home. The system might “leak” in a sense with abandoned bicycles, however this is expected to be insignificant. For the same semester, every day of the week should follow the same patterns (all Mondays have the same scheduling). 
 
An additional affect on the inflow/outflow rate will be how many spaces are available. If a student is cycling by and cannot immediately see many available spaces, she will simply continue to another bicycle parking lot. Even if there are still spaces available, the probability that any individual student occupies them reduces. 
