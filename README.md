Mirrored from MATLAB Central [**Wavefront OBJ toolbox**](http://www.mathworks.com/matlabcentral/fileexchange/27982-wavefront-obj-toolbox) - [*Version 2b*](http://www.mathworks.com/matlabcentral/fileexchange/27982-wavefront-obj-toolbox?download=true).

-------------------------------------------------------
## Original Description

Read and Write Wavefront OBJ geometry and MTL files.

A Wavefront Geometry Object file is supported by many 3D programs, it looks like: 

``````matlab
    v 0.000000 2.000000 0.000000 
    v 0.000000 0.000000 0.000000 
    v 2.000000 0.000000 0.000000 
    v 2.000000 2.000000 0.000000 
    % Vertices Coordinates 4 
    f 1 2 3 4 
    % Faces 1
```

The function read_wobj allow Wavefront object files including material MTL files to be read into a Matlab structure. 
The function write_wobj exports a Matlab structure to an OBJ file.

It doesn't matter if the object file contains splines or polygon based geometry, it reads and writes almost all .obj files.

See "help read_wobj" and "help write_wobj"

Comments and bug reports are welcome

## Acknowledgements	
*This file* inspired **[Ray Casting For Deformable Triangular 3D Meshes](http://www.mathworks.com/matlabcentral/fileexchange/41504)**.

## MATLAB release
MATLAB 7.10 (R2010a)