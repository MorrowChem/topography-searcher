# Simple landscape generation

The key use of TopSearch is in mapping the topography of surfaces. Here, we provide a simple example of using this functionality on the two-dimensional Schwefel function. Throughout this example we use the techniques developed in the energy landscape framework. First, we perform global optimisation using basin-hopping to locate all the local minima of the surface. From these local minima we perform transition state searches between selected pairs of minima. These transition states provide important information about the intermediate structure of the space between local minima. We then encode the topography by the minima and transition states, and visualise this information directly on the surface, and with network and disconnectivity graph representations.