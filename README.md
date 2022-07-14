# rtfluid
rtfluid code from http://www.ss.iij4u.or.jp/~amada/fluid/ (check wayback machine)

So I remember being pretty impressed with this fluid simulation and wanting to check things out in more depth later.

Seems to be a SPH simulation and is rendered with Marching Cubes, marching cubes is cool, but kind of limits the SPH simulation in that it must be located within the voxel area of the marching cube rendering. But marching cubes is a pretty straight forward algorithm, maybe as CPU's progress this can become more practical with optimization.

You might want to check out the following for alternate rendering methods:

https://developer.download.nvidia.com/presentations/2010/gdc/Direct3D_Effects.pdf

https://matthias-research.github.io/pages/publications/screenSpaceMeshes.pdf

