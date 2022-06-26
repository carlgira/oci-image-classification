# oci-custom-dataset

OCI custom dataset creation using python SDK. The idea with this notebook is to create a custom dataset, to use the datalabeling and vision service of OCI.

I'll be using the landmaks dataset v2 https://github.com/cvdfoundation/google-landmark.

## Initial Setup

1. Donwload and install OCI cli https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/cliinstall.htm

Authenticate using your OCI cli to have the config ready to start.
```
    oci session authenticate
```

2. To start the notebook create a conda enviroment using the next commands.

```
    conda create --name oci-custom-dataset-env --file environment.yaml
    conda activate oci-custom-dataset-env
```

Once the enviroment is activated start jupyter.

```
    some command
```

