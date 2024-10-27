# Simulation-of-hybrid-systems-regulated-by-newtonian-mechanics
Hybrid programs orchestrate classic computation with physical processes in order to reach 
prescribed goals. Examples of this range from small medical devices, such as pacemakers and 
insulin pumps, to autonomous vehicles and district-wide electric/water grids. Their rapid 
development in the last decades lead to a flurry of research on suitable languages, semantics, and 
tools for their design and analysis; and even though great progress has been made 
on this area, several important challenges remain largely open. One prominent case concerns the 
simulation of hybrid programs centred on the tool Lince: the latter lacks certain language 
constructs that are important for modelling important classes of hybrid programs, particularly 
those regulated by Newtonian mechanics such as autonomous vehicles. This is pressing because a 
myriad of autonomous systems are currently under development and being able to simulate them 
before deployment is useful to ensure they will behave as intended.


The goal of this project is to extend the tool Lince with new language constructs. Specifically, we  will be aiming at a palette of real-arithmetic operators: viz. division, exponentiation, and square  root. Such an extension will allow a more rigorous simulation of hybrid programs that rely on the  calculation of intersection points between trajectories. The latter occurs e.g., in autonomous  driving to determine whether two vehicles will collide under certain dynamics, and also in space  travel to determine whether a probe will intersect the orbit of a planet or moon. Technically the  addition of new language constructs will require us to extend Lince’s programming language and to  introduce a corresponding operational semantics that among other things needs to take exceptions  and exception-handling into account. The fulfillment of the goal propounded above gives rise to a  ‘next-generation’ simulator of hybrid programs, better adapted to those programs that interact  with physical processes regulated by Newtonian mechanics.


The repository of this project can be found [here](https://github.com/arcalab/lince/tree/nonLinear).
