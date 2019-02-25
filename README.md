# Multicell-systems.
Multicell systems are polygonal networks that are meant to characterize the structure of biological multicellular systems. Multicell systems grow from a single shape (e.g. square) to a lattice of multiple cells of the same shape. This can be done by subdividing an existing shape, or by adding a single shape with the same number of size along the edge of the system. This provides us with analogue to simple biological multicellular systems.

## Euler Paths (Intercellular Connectivity) as Indicator of Modularity.   
The conherence of a group of partitioned cells can be evaluated using an Euler completeness criterion [1]. For a group of cells to be Euler complete, a path must be able to traverse each edge only once. If the path is Euler incomplete (where the path is forced to miss an edge), that edge defines a new module in the multicell system.  

## Growth of a Multicell System.
Rather than growing in cell number through division, multicell systems grow through the recursive partitioning of a space (rectangle or oblinong sphere) using a _k_-D tree approach [2-7]. Mapping partition events to a lineage tree, a number of rules can be used to determine that relative size and asymmetry of each partition.  

## Examples of the Multicell System Developmental Process.  

<p align="center">
  <img width="700" height="350" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/hexagonal-cell-lineage.PNG">
</p>

An example of a cell lineage tree for a hexagonal multicell system. Click to enlarge.

<p align="center">
  <img width="700" height="350" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/rectangle-mixed-cell-lineage.PNG">
</p>

An example of a cell lineage tree for a retangular multicell system. Click to enlarge.

<p align="center">
  <img width="300" height="750" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/triangle-cell-lineage.png">
</p>

An example of a cell lineage tree for a triangular multicell system. Click to enlarge.

## Multicell Systems as a Species: Square Oozer.   
To illustrate how multicellular systems can behave as organisms, we can look to the pseudo-species _Quadratus exsudares_ (Square Oozer) as a thought experiment [8] to show how such systems might be shaped by their environment. Square oozer is a single-celled organism where cellular shape is modified by flows within the cell experiencing friction due to resistence to environmental forces.


<p align="center">
  <img width="450" height="450" src="https://user-images.githubusercontent.com/38323286/53359628-0bf30980-38f9-11e9-9b8f-d435788fa098.png">
</p>

Cartoon demonstrating the principle of organismal design as a minimization of flows. A: effects of Newtonian environmental parameters (e.g. gravity, resistance) on animal morphology (a Square oozer* used for illustration purposes), B: changes in shape to morphology of the Square oozer over time. C: changes in flows inside Square oozer over time from laminar to turbulent to something resembling a vasculature. Adapted from figures and text in [9].

## Limitations.    
One limitation of multicellular systems is that support networks must be formed when each cell in the community have differential access to resources from the outside. These support networks cross the edge between cells, so that this network form a route between all edge in the system. Let us suppose that our multicell systems are in equilibrium when crossings are limited to one per edge -- making two crossings on a random edge for the sake of convenience would perturb flow between compartments of the system. This mimicks gap junctions and other cell-cell communication mechanisms in biological systems. Thsi assumption allows us to adopt the idea of Euler complete paths to characterize these interaction networks.  

## References.
[1] Levin, O. (2018). [http://discrete.openmathbooks.org/dmoi2/sec_paths.html](http://discrete.openmathbooks.org/dmoi2/sec_paths.html).  In "Discrete Mathematics: an open introduction", Open Math Books.

[2]  Dmitrenok, I., Drobny, V., Johard, L., and Mazzara, M. (2016). Evaluation of spatial trees for simulation of biological tissue. arXiv, 1611.03358.

[3]  Balzer, M. and Deussen, O. (2005). Voronoi treemaps. IEEE Symposium on Information Visualization, 49–56, Washington, DC.

[4]  Oroz-Luengo, M.A., Duloquin, L., Castro, C., Savy, T., Faure, E., Lombardo, B., Bourgine, P.., Peyrieras, N., and Santos, A. (2008). [Can Voronoi diagram model cell geometries in early sea-urchin embryogenesis?](http://doi:10.1109/ISBI.2008.4541043) IEEE International Symposium on Biomedical Imaging, Paris, France.

[5]  Horn, M.S., Tobiasz, M., Shen, C. (2009). [Visualizing Biodiversity with Voronoi Treemaps](http://doi:10.1109/ISVD.2009.22). IEEE International Symposium on Visualization and Data, Copenhagen, Denmark.

[6]  Tian, S., Cui, X., and Gong, Y. (2015). [An Approach to Generate Spatial Voronoi Treemaps for Points, Lines, and Polygons](http://doi:10.1155/2015/787163). Journal of Electrical and Computer Engineering, 787163.

[7]  Nocaj, A. and Brandes, U. (2012). [Computing Voronoi Treemaps: Faster, Simpler, and Resolution-independent](http://doi:10.1111/j.1467-8659.2012.03078.x). Computer Graphics Forum, 31(3), 855–864. 

[8] Alicea, B. (2012). [A Constructal Approach to Evolution: how "physical" is descent with modification?](https://syntheticdaisies.blogspot.com/2012/05/constructal-approach-to-evolution-how.html)
Synthetic Daisies blog, May 20.

[9] Bejan, A. and Zane, P.D. (2012). Design in Nature. How the constructal law governs evolution in biology, physics, technology, and social organization. Doubleday Books, New York.
