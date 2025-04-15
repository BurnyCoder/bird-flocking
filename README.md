# Bird flocking

Browser-based simulation demonstrating emergent flocking behavior, referred to as "boids", with group of agents (birds) following a set of simple rules, resulting in complex, life-like flock movement patterns, using HTML, CSS (with Tailwind CSS for styling), and JavaScript for the logic and rendering on an HTML Canvas.

![image](https://github.com/user-attachments/assets/e2df018f-ff8d-4b7e-9acf-4b5c29701986)

1.  **Separation:** Steer to avoid crowding local flockmates. Birds calculate a repulsive force away from neighbors that are within the `avoidanceRadius`. The closer a neighbor, the stronger the repulsive force.
2.  **Alignment:** Steer towards the average heading (velocity) of local flockmates. Birds try to match the direction of their neighbors.
3.  **Cohesion:** Steer to move toward the average position (center of mass) of local flockmates. Birds try to stay close to the group.
