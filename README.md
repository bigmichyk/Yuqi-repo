## Yuqi He
## CMPSC 442
## Markdown file for Vacuum agent



### General pipeline

1. So the vacuum cleaner starts at the very top of the room. 
2. If there is no obstacle, it will keep searching forward, until it hits 1 obstacle, which will eliminate the obstacle. 
3. If the cleaner hits the wall, we want to know if we are going left or right. Notice that we always want the agent to search one line below.
4. So if total turns is an even number, we want to turn left, if total turns is an odd number, we want the agent to turn right. 
5. After initial turn, the agent will point downwards, so we want it to only go 1 unit forward to the next line below, and start searching the line below by turning again, which is defined by 4..
6. The Vacuum will keep searching until all obstacles are removed and the final wall is hit (meaning there is no line below anymore).

### How to use it

Follow steps of https://personal.psu.edu/cld5070/courses/cmpsc442-sp23/assignments/RBES_Assignment/ to setup the correct environment. Then run the vacuum agent file.

### Issues

I did not command the agent to do a swirl type of motion. But I think the line-by-line searching is a great way to approach this. I think it potentially saves computational cost because this is an easier way.

