# Planned revisions to reproduction of ....

Author: Colman Bashore

## Analysis

I will attempt to consolidate the code used to make maps into a function that can 
be used multiple times.The tm package is used to make several maps throughout the
procedure with relatively similar inputs. Therefore, my goal is to make a function
that can be called anytime a map plot needs to be created.

## Results

Outputs should be the same maps as before, but just derived through a more efficient 
method. For at least one map, I can run the original code and then run my new 
code right after and I will be able to see if it produces the same map.

## Discussion

I am not sure how many parameters my function will need to take, but it will be
effective if it can produce the exact same maps but just by calling one function
instead of writing the same code chunk many times.