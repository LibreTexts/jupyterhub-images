# JupyterHub Images
This repository contains the images used in the LibreTexts-UCD JupyterHub website.
An initContainer clones this repository and mounts it as a volume to a pod
in the cluster, so the template html files can refer to the images locally.
