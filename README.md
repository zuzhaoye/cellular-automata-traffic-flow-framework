# Cellular automata traffic flow framework

A framework of cellular automata with visualization for traffic flow problems. This framework has autonoumous vehicles included. You can make any change or invent new micro rules based on this framework. A more detailed description will be added here in a later stage when I get more free time.

![example_gui.png](image/example_gui.png | width=300)

Dependencies:
- numpy
- matplotlib
- tkinker

General properties:
- Flexible. Road length and lane numbers are adjustable.
- High resolution. I set the cell size to represent 1m while the car size is 5m. So the car moves smoothier rather than one car by one car in other models.
- Recursive road. A car moves from start to end, then re-enter the starting point.

Note: I thank a paper for 2017 MCM Problem C that provides most of the details of my model. I cannot find the public repo of the author (if any). If you are the author, please feel free to let me to address your contribution (The team control number is 55278, [paper link](https://myhome.spu.edu/lauw/MCM/4725%20Case%20Studies/2017%20Problem%20C%20Co-op/Co-op02.pdf)).


