# POCLOUD-download-selected-variables
Download selected variables using OPeNDAP

Data subscriber is required for run the POCLOUD download for selected variables.

The subscriber scripts are available in the [pypi python repository](https://github.com/podaac/data-subscriber), it can be installed via pip:

```sh
pip install podaac-data-subscriber
```

Now you could run the subsetter through Command line interfaces:

```sh
$> python pocloud_download_variables.py -v=lat,lon,analysed_sst,mask -c MUR-JPL-L4-GLOB-v4.1 -d myData -sd 2023-06-28T00:46:02Z -ed 2023-07-01T00:46:02Z
```
