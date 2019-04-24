fastreg
============
implementation of a fast non-rigid registration method via accelerated optimisation on the manifold of diffeomorphisms.


dependencies
-----------
* boost
* itk
* nvidia gpu with cuda >=8.0.44
* opencv

building
-----------
```
source setup.sh -a
```

usage
-----------
images must be of type `float32` and labels of type `int16`

```
./build/bin/app ./params.ini <path_to_target> <path_to_target_labels> <path_to_source> <path_to_source_labels> <output_path>
```


