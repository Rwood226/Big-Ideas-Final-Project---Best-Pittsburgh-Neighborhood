Crime is a necessary statistic when evaluating the best neighborhood. To do this, I used arrest data.  

The first code block takes the spreadsheet and organizes it by neighborhood. It then reports how many crimes occured in each neighborhood during 2024, 2025, and October 31, 2026. It also reports a percentage trend between 2024 and 2025, as well as a total trend from 2024 and 2026. Finally, a Total column reports the total crime in each neighborhood.  


The second code block aims to quantify these numbers into a simple Safety Score. The formula used is given below:  
  
100 - Δ%  
---------  =  Safety Score  
  Total  
  
  
An example of this could be Point Breeze with 199 total arrests, and a 4.7% increase from 2024 to 2025.   

100 - 4.7 = 95.3   
95.3 / 199 = 0.478894    

Thus Point Breeze has a Safety Score of 0.478894, placing it at number 23 on the list.    
    
    
To clarify, this is just arrests, and while a neighborhood of 4 people with 0 crime is great, it isn't the best, which is why other data is necessary. This can only be one piece to a greater puzzle.    

I classified the top neighborhoods as those with a safety score greater than 0.45 to leave room for population errors
St. Clair	            10.000000    
Ridgemont	            6.250000   
New Homestead	        4.166667    
Windgap	              2.261429     
Oakwood	              2.205882     
Swisshelm             2.000000      
Esplen	              1.581522      
Friendship	          1.578000       
Westwood	            1.308257      
Polish Hill           1.054955   
Upper Lawrenceville	 	1.030000   
Bon Air               0.996947   
Fairywood             0.974843   
Hays	                0.915094   
Upper Hill          	0.802105   
Stanton Heights      	0.697541   
Squirrel Hill North	  0.648241   
Arlington Heights	    0.634559   
Allegheny West	      0.614388   
Duquesne Heights	  	0.573810   
Banksville	          0.563675   
Lincoln Place         0.509249   
Point Breeze          0.478894   
Perry North	          0.459365     
