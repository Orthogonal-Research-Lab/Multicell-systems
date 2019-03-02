# Multicell systems: a compositional approach to multicellularity and embryogenesis  

While development is a generative process, much can also be learned from the geometry and overall form of an multicellular biological structures. One such instantiation is the multicell systems, which allows for a better understand how geometry and composition contribute to life-like generative processes. It is further demonstrate how category theory can be used to create a multicell system that increases in complexity. The development of a multicell system can also be analyzed using a lineage tree. We can also understand multicell systems at being part of species inhabiting various environmental niches using a thought experimental tool. To summarize, the limitations of such as approach are considered as well as a consideration of how multicell systems might be used in future research.

## Introduction to Multicell Systems  
Multicell systems are polygonal networks that are meant to characterize the structure and overall form [1] of developing multicellular systems. Multicell systems grow from a single shape (e.g. square) to a lattice of multiple cells of the same shape. This can be done by subdividing an existing shape, or by relocating a shape of _n_ sides to any edge within the system. This provides us with analogue to simple biological multicellular systems that can be the basis for developmental and evolutionary analyses. For example, triangular-shaped cells can be found amongst diatoms, while rectangular cells can be found in plants. As a biologically-plausible and generative multicelular system, we seek to learn about the interrelated processes of functional emergence and cellular differentiation.

### Multicell Systems as Compositional Abstractions  
Multicell systems are also mathematical objects. Multicell systems can be built using the principles of compositionality [2,3] to allow for developmental causality. Composition also provides us with an abstraction that allows for complex states to be built from a set of classes and morphisms. In multicell systems, our initial condition is defined by the following objects: edges, cell interiors, and nodes, and paths across an edge. Morphisms serve the functional role of joining objects into a common class, and are defined as cell divisions, rearrangements, and modularity events. Suppose the initial condition is a triangular-shaped cell. This "cell" contains all of our category's objects (three edges, one cell interior, three nodes, and one path across each edge). As the multicell gains complexity by means of cell division, relocation, and modularity events, these morphisms allow us to fully describe the origin and generation of all system components over time. 

### Euler Paths (Intercellular Connectivity) as Indicator of Modularity  
The conherence of a group of partitioned cells can be evaluated using an Euler completeness criterion [4]. For a group of cells to be Euler complete, a path must be able to traverse each edge only once. If the path is Euler incomplete (where the path is forced to miss an edge), that edge defines a new module in the multicell system. The rationale for using Euler paths as an indicator of modularity is based on homeostatic regularity of intercellular signaling. All cell-cell junctions must have the same number of communication pathways to be considered part of the same functional unit (in this case, a single intercellular module). When this principle is violated, the site of the next division event defines the boundary between functional units.  

### Growth of a Multicell System  
As embryos grow in cell number through division, multicell systems grow through the recursive partitioning of a space (two- or three-dimensional) using a _k_-D tree approach [5-10]. Mapping partition events to a lineage tree, a number of rules can be used to determine that relative size and asymmetry of each partition. Each round of division introduces the oppportunity to add cells to the system and transform the multicell phenotype.  In the following section, several examples are provided of how multicell systems can be configured and analyzed.

## Examples of the Multicell System Developmental Process  
This iterative process of _k_-D decomposition and functional evaluation results in a lineage tree that provies information regarding the plausibility of each new pheontype. Two variables that significantly affects the shape of this tree and the functional evolution of developing multicell systems are the shape of individual cells and symmetry of division events. We evaluated there variables for three cell shapes: hexagon, rectangle, and triangle. For the hexagonal and triangle conditions, the cell size is kept constant with a periodic alignment. For the rectangular condition, asymmetrical cell divisions (one cell per round of division instead of two) result in cells  of varying size.

We find that hexogonal motifs tend to preserve a single module, even as the multicell system grows in size. In the case of triangle motifs, Euler completeness can be preserved in two ways: by introducing a shape mutation (hexagon) to the system, or by shifting components around to rescue the phenotype by relocating structures that result from modularity in the previous developmental step. Using a rectangulat motif provides us with a result in between the hexogonal and tringular result. That is, symmetrical divisions tend to preserve a single module for increasingly larger numbers of cells, while asymmetrical divisions result in the creation of multiple modules simultaneously. Morevoer, the strategies used to rescue Euler completeness for triangular motifs do not neccessarily work with rectangular systems.  

<p align="center">
  <img width="481" height="360" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/hexagonal-cell-lineage.png">
</p>

__Figure 1.__ An example of a cell lineage tree for a hexagonal multicell system. Click to enlarge.

<p align="center">
  <img width="478" height="359" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/rectangle-mixed-cell-lineage.png">
</p>

__Figure 2.__ An example of a cell lineage tree for a retangular multicell system. Derived modules are shaded in cross-hatch. Click to enlarge.

<p align="center">
  <img width="379" height="385" src="https://github.com/Orthogonal-Research-Lab/Multicell-systems/blob/master/Sketches-and-Lineages/triangular-cell-lineage.png">
</p>

__Figure 3.__ An example of a cell lineage tree for a triangular multicell system. Derived modules are shaded in cross-hatch. Click to enlarge.

The hexogonal and rectangular motifs reveal a phenomenon called fractal reproduction. Fractal reproduction resembles cloning in biological development, and are usually produced during rounds of cell proliferation. 

### Multicell Systems as a Species: Square Oozer  
To illustrate how multicellular systems can behave as organisms, we can look to the pseudo-species _Quadratus exsudares_ (Square Oozer) as a thought experiment [11] to show how such systems might be shaped by their environment. Square oozer is a single-celled organism where cellular shape is modified by flows within the cell experiencing friction due to resistence to environmental forces. During behavior, the phenotype moves along the path or least resistance for both internal and extenal flows, resulting in a highly fluid phenotype that changes its overall shape and spatial orientation over time (Figure 4). Over thousands of generations, Square Oozer will tend to resemble pixellated versions of "lifelike" structures: animal vasculature, the root systems of plants, and branching axons of nervous systems. 

<p align="center">
  <img width="450" height="480" src="https://user-images.githubusercontent.com/38323286/53359628-0bf30980-38f9-11e9-9b8f-d435788fa098.png">
</p>

__Figure 4.__ Cartoon demonstrating the principle of organismal design as a minimization of flows. A: effects of Newtonian environmental parameters (e.g. gravity, resistance) on animal morphology (a Square oozer* used for illustration purposes), B: changes in shape to morphology of the Square oozer over time. C: changes in flows inside Square oozer over time from laminar to turbulent to something resembling a vasculature. Adapted from figures and text in [12].

## Limitations  
One limitation of multicellular systems is that support networks must be formed when each cell in the community have differential access to resources from the outside. These support networks cross the edge between cells, so that this network form a route between all edge in the system. Let us suppose that our multicell systems are in equilibrium when crossings are limited to one per edge -- making two crossings on a random edge for the sake of convenience would perturb flow between compartments of the system. This mimicks gap junctions and other cell-cell communication mechanisms in biological systems. Thsi assumption allows us to adopt the idea of Euler complete paths to characterize these interaction networks.  

## References  
[1] Thompson, D. (1942). On Growth and Form, Cambridge University Press, Cambridge, UK.

[2] Spivak, D.I. (2014). [Category theory for the sciences](https://github.com/mmai/Category-Theory-for-the-Sciences). MIT Press, Cambridge, MA.

[3] Fong, B. and Spivak, D.I. (2018). [Seven Sketches in Compositionality: an invitation to applied category theory](https://arxiv.org/abs/1803.05316). arXiv, 1803:05316.

[4] Levin, O. (2018). [http://discrete.openmathbooks.org/dmoi2/sec_paths.html](http://discrete.openmathbooks.org/dmoi2/sec_paths.html).  In "Discrete Mathematics: an open introduction", Open Math Books.

[5]  Dmitrenok, I., Drobny, V., Johard, L., and Mazzara, M. (2016). Evaluation of spatial trees for simulation of biological tissue. arXiv, 1611.03358.

[6]  Balzer, M. and Deussen, O. (2005). Voronoi treemaps. IEEE Symposium on Information Visualization, 49–56, Washington, DC.

[7]  Oroz-Luengo, M.A., Duloquin, L., Castro, C., Savy, T., Faure, E., Lombardo, B., Bourgine, P.., Peyrieras, N., and Santos, A. (2008). [Can Voronoi diagram model cell geometries in early sea-urchin embryogenesis?](http://doi:10.1109/ISBI.2008.4541043) IEEE International Symposium on Biomedical Imaging, Paris, France.

[8]  Horn, M.S., Tobiasz, M., Shen, C. (2009). [Visualizing Biodiversity with Voronoi Treemaps](http://doi:10.1109/ISVD.2009.22). IEEE International Symposium on Visualization and Data, Copenhagen, Denmark.

[9]  Tian, S., Cui, X., and Gong, Y. (2015). [An Approach to Generate Spatial Voronoi Treemaps for Points, Lines, and Polygons](http://doi:10.1155/2015/787163). Journal of Electrical and Computer Engineering, 787163.

[10]  Nocaj, A. and Brandes, U. (2012). [Computing Voronoi Treemaps: Faster, Simpler, and Resolution-independent](http://doi:10.1111/j.1467-8659.2012.03078.x). Computer Graphics Forum, 31(3), 855–864. 

[11] Alicea, B. (2012). [A Constructal Approach to Evolution: how "physical" is descent with modification?](https://syntheticdaisies.blogspot.com/2012/05/constructal-approach-to-evolution-how.html)
Synthetic Daisies blog, May 20.

[12] Bejan, A. and Zane, P.D. (2012). Design in Nature. How the constructal law governs evolution in biology, physics, technology, and social organization. Doubleday Books, New York.  
