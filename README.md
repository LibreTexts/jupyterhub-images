# JupyterHub Images
This repository contains the images used in the LibreTexts-UCD JupyterHub website.
An initContainer clones this repository and mounts it as a volume to a pod
in the cluster, so the template html files can refer to the images locally.

Please visit the [documentation](https://github.com/LibreTexts/metalc/blob/master/docs/Bare-Metal/baremetal.md#editing-custom-html-pages)
for more information.

*This repository has been integrated into [JupyterHub Templates](https://github.com/LibreTexts/jupyterhub-templates).
 None of the content here is pulled onto the cluster or displayed online.*
