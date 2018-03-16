# dwhitena/minimal-jupyter

This is a minimal docker image for Jupyter notebooks. The "minimal" docker image from Jupyter is around 1GB, and I wanted something a little more portable. The image is based on `alpine` and only included Python and Jupyter. 

## Usage:

To start a local Jupyter server:

```
$ docker run -p 8888:8888 dwhitena/minimal-jupyter
```

Then, you open a browser and visit `localhost:8888` to use Jupyter.

