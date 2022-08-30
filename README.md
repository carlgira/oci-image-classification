<img src="img/emea-wedo.png" alt="WEDO" width="400"/>

# OCI Image Classification 

OCI custom dataset creation using python SDK. The idea with this notebook is to create a custom dataset, to use the datalabeling and vision service of OCI.

A wrote a blog explaining how to use this repository https://medium.com/@carlgira/ai-vision-model-on-oci-for-image-classification-90387524d69d


I'll be using the landmaks dataset v2 https://github.com/cvdfoundation/google-landmark.

## Initial Setup

1. Follow the instructions to configure oci cli and to create API keys to authenticate against OCI that are in this blog https://medium.com/@carlgira/install-oci-cli-and-configure-a-default-profile-802cc61abd4f

2. To start the notebook create a conda enviroment using the next commands.

```
    conda env create --name oci-custom-dataset-env --file environment.yml
    conda activate oci-custom-dataset-env
```

3. Once the enviroment is activated start jupyter.

```
    jupyter-notebook
```

