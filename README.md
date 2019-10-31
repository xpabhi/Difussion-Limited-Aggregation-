# Difussion-Limited-Aggregation-
DLA using Brownian movement (Random 2D flow) &amp; Stickiness  Identification, Implementation and verification.



Problem statement

DLA and Brownian movement: 
"start with a white image except for a single black pixel in the center. New points are introduced at the borders and randomly (approximation of Brownian motion) walk until they are close enough to stick to an existing black pixel. A typical example of this is shown below in figure 1. If a point, during its random walk, approaches an edge of the image there are two strategies. The point either bounces off the edge or the image is toroidally bound (a point moving off the left edge enters on the right, a point moving off the right edge enters on the left, similarly for top and bottom). In general new points can be seeded anywhere in the image area, not just around the border without any significant visual difference."

Task:

a.	Program in python to simulate DLA
b.	Build an Algorithm and program it to estimate Stickiness
c.	Introduce the Stickiness found in point “b” to the program created in point “a” and see if it works well. Check if the algorithm supports  with the data gathered from in DLA simulations. Here the calculated K and Expected K is compared for model accuracy.
Assume:  M =  matrix size, N = number of particles, K = Stickiness
