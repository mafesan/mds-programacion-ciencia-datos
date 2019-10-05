# Programación orientada a ciencia de datos

## Python

### Intro a Jupyter Notebooks

Con **Anaconda** instalado, ejecutar:

```bash
$ conda activate
$ jupyter notebook
```

## Crear proyecto Anaconda con PyCharm

Una vez creado, desde la terminal:

```bash
$ conda create -n entorno1 python=3.7
$ conda activate entorno1
```

## Troubleshooting

### Desactivar `base` por defecto

```bash
$ conda config --set auto_activate_base false
```

### Instalar **Anaconda** con otra shell

Con **zsh**, abrá que editar el fichero `~/.zshrc` y pegar las líneas generadas por el instalador en `~/.bashrc` o similar.
