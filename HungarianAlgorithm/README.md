## HungarianAlgorithm

This implements the [Hungarian algorithm by Ivan Jurin](https://github.com/antifriz/hungarian-algorithm-n3) to solve the [Assignment problem](https://en.wikipedia.org/wiki/Assignment_problem)

This can be used to solve any sort of assignment problem between two sets of values. The component takes a 'costMatrix' represented as a dataTree.

This was created to represent data processed with T-SNE, ([using Owl, by Mateusz Zwierzycki](http://www.grasshopper3d.com/group/owl)) in 2d grid form. For an in-depth explanation of how this helps/works with T-SNE, [see here](https://blog.sourced.tech/post/lapjv/).

1. Random geometry:
![hungarian1.jpg](https://raw.githubusercontent.com/provolot/GrasshopperArsenal/master/HungarianAlgorithm/hungarian1.jpg)
2. Organized with 2D T-SNE
![hungarian2.jpg](https://raw.githubusercontent.com/provolot/GrasshopperArsenal/master/HungarianAlgorithm/hungarian2.jpg)
3. Assigned to a grid with the Hungarian algorithm
![hungarian3.jpg](https://raw.githubusercontent.com/provolot/GrasshopperArsenal/master/HungarianAlgorithm/hungarian3.jpg)
4. Placed
![hungarian4.jpg](https://raw.githubusercontent.com/provolot/GrasshopperArsenal/master/HungarianAlgorithm/hungarian4.jpg)
