# DESCRIPTION: #
When April scatters charms of primrose gold 
Among the copper leaves in thickets old, 
And singing skylarks from the meadows rise, 
To twinkle like black stars in sunny skies; 

When I can hear the small woodpecker ring 
Time on a tree for all the birds that sing; 
And hear the pleasant cuckoo, loud and long -- 
The simple bird that thinks two notes a song; 

When I can hear the woodland brook, that could 
Not drown a babe, with all his threatening mood; 
Upon these banks the violets make their home, 
And let a few small strawberry blossoms come: 

When I go forth on such a pleasant day, 
One breath outdoors takes all my cares away; 
It goes like heavy smoke, when flames take hold 
Of wood that\'s green and fill a grate with gold.

William Henry Davies
------------

All you get are the following 2 sequences of numbers.  Determine the
sequence of numbers which comes next, and that will be the key.

           Sequence 1:  123112233111222333
           Sequence 2:  111213212223313233
           
# WALKTHROUGH: #
This is a classic challenge designed to make you think way too much. The solve is easy once you realize what's going on. The sequence is created by describing the numbers in the previous sequence. Example: to get sequence 2, you say what is in the first sequence. Sequence 1 starts with one '1', so the beginning of sequence 2 is 11. Next is a 2, so you add one '2' to sequence 2, which is now 1112. It continues like this...

Sequence 1:  **1**23112233111222333  
Sequence 2:  **11**  - one 1  
Sequence 1:  1**2**3112233111222333  
Sequence 2:  11**12**  - one 2  
Sequence 1:  12**3**112233111222333  
Sequence 2:  1112**13**  - one 3  
Sequence 1:  123**11**2233111222333  
Sequence 2:  111213**21**  - two 1s  
Sequence 1:  12311**22**33111222333  
Sequence 2:  11121321**22**  - two 2s  
Sequence 1:  1231122**33**111222333  
Sequence 2:  1112132122**23**  - two 3s  
Sequence 1:  123112233**111**222333  
Sequence 2:  111213212223**31**  - three 1s  
Sequence 1:  123112233111**222**333  
Sequence 2:  11121321222331**32**  - three 2s  
Sequence 1:  123112233111222**333**  
Sequence 2:  1112132122233132**33**  - three 3s  
  
Sequence 3 is derived the same way from Sequence 2.
  
Sequence 3 is: 311211131211322311131223
