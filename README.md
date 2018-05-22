# ECE143-Individual-Project
## Results Discussion
#### Modules
In this project, a couple modules I used are matplotlib, random, and numpy. Numpy is a really powerful module in this case because it helps create the tracking map and check if any overlapping happens. For example, numpy.any() returns true if the condition inside of the parentheses is met, false otherwise. It becomes extrodinarily convenient to check if there is any 1s inside of the target region when 1 is defined as the region is occupied
#### Question 1: Given an overall desired coverage footprint and a sequence of n communications towers, what is the resulting resolved coverage?
  Example: footprint of 10 by 10, run execution 5 times
  
  Try 1:
  
  <img width="277" alt="screen shot 2018-05-21 at 10 35 35 pm" src="https://user-images.githubusercontent.com/35671831/40344234-bf38118a-5d48-11e8-95e0-d91609eb38ef.png">
  
  Try 2:
  
  <img width="280" alt="screen shot 2018-05-21 at 10 35 58 pm" src="https://user-images.githubusercontent.com/35671831/40344257-d17452c8-5d48-11e8-8cf2-d813c8658055.png">
  
  Try 3:
  
  <img width="280" alt="screen shot 2018-05-21 at 10 35 48 pm" src="https://user-images.githubusercontent.com/35671831/40344264-dc16277e-5d48-11e8-9e07-10c60a21bec5.png">
  
#### Question 2: What is the total area of coverage relative to the desired total coverage area of the original footprint? That is, are there any gaps in coverage?
  Example: footprint of 10 by 10, run execution 5 times
  
  Try 1: In this example, the covered area is 54, so the coverage is 54/100 = 54%
  
  <img width="462" alt="screen shot 2018-05-21 at 11 02 14 pm" src="https://user-images.githubusercontent.com/35671831/40344819-65ea419a-5d4b-11e8-93da-99aa9d6fc394.png">
  
  Try 2: In this example, the covered area is 29, so the coverage is 29/100 = 29%
  
  <img width="511" alt="screen shot 2018-05-21 at 11 02 36 pm" src="https://user-images.githubusercontent.com/35671831/40344820-6702d088-5d4b-11e8-98c8-629f39b4c8cb.png">
  
  Try 3: In this example, the covered area is 33, so the coverage is 33/100 = 33%
  
  <img width="492" alt="screen shot 2018-05-21 at 11 02 44 pm" src="https://user-images.githubusercontent.com/35671831/40344821-6848bc28-5d4b-11e8-889a-7767bad3859c.png">

#### Question 3: On average, how many communications towers are required before full coverage is obtained?
  To answer this question, the calculation is implemented on a footprint of 10 by 10
  
  The execuation is ran 50 times.

  The number of towers put down for each execuation is documented as follows:
  [22,24,35,25,26,34,20,17,19,22,30,32,23,30,20,24,26,29,30,25,19,32,26,15,16,37,24,33,20,37,24,29,16,26,16,30,23,32,20,26,31,20,39,28,29,15,24,33,27,26]
  
  On average: 25
