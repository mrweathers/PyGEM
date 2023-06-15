# Initial Conditions and Surface Type
Initial glacier area is based on the RGI and assumed to represent the year 2000.  The initial surface type is based on the glacier’s median elevation, with the higher elevation being classified as firn and the lower classified as ice (or debris-covered). The surface type evolves based on the five-year running average of the glacier bin’s annual climatic mass balance ([Huss and Hock, 2015](https://www.frontiersin.org/articles/10.3389/feart.2015.00054/full)). If the five running average is positive, then the surface is classified as firn, while if it is negative, the surface is classified as ice. The surface type is classified as snow when snow accumulates on the surface.

During the ice thickness inversion, which is done using OGGM ([Maussion et al. 2019](https://gmd.copernicus.org/articles/12/909/2019/)), the glacier is assumed to be in steady state. As a result, at the start of the simulation, there is typically a dynamical adjustment as the ice thickness is redistributed in response to the climatic mass balance forcing.