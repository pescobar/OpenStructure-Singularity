# OpenStructure singularity container

## To build this container from scratch execute this:

```bash
sudo singularity build OpenStructure-1.7.0.img Singularity.1.7.0
```

## To list the available apps inside the container

```bash
singularity apps OpenStructure-1.7.0.img
```

## To execute one of the apps

```bash
singularity run --app lddt OpenStructure-1.7.0.img
```
