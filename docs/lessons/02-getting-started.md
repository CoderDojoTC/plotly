# Getting Started with Plotly

This lesson will show you how to install the Plotly Python libraries.  This lesson assumes you have Python 3 already running on your computer.

## Installing Plotly Libraries

Plotly takes about 15 MB of disk.  It will usually install in about 2-minutes on a standard internet connection (10MB/sec).

### Quick Installation

If this is your first and only Python project, you don't need to worry about our libraries getting mixed up with other projects.

Just type the following in your shell:

```sh
pip install plotly
```

```
Collecting plotly
  Downloading plotly-5.8.0-py2.py3-none-any.whl (15.2 MB)
     |████████████████████████████████| 15.2 MB 10.1 MB/s 
Collecting tenacity>=6.2.0
  Downloading tenacity-8.0.1-py3-none-any.whl (24 kB)
Installing collected packages: tenacity, plotly
Successfully installed plotly-5.8.0 tenacity-8.0.1
```

Some of the examples will also depend on the popular panda library:

```sh
pip install pandas
```

## Using Conda

```sh
conda env list
```

```sh
conda create plotly python=3
```

## Results of Installation

```
## Package Plan ##

  environment location: /opt/anaconda3/envs/plotly

  added / updated specs:
    - python=3


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    ca-certificates-2022.4.26  |       hecd8cb5_0         124 KB
    openssl-1.1.1o             |       hca72f7f_0         2.2 MB
    setuptools-61.2.0          |  py310hecd8cb5_0        1020 KB
    sqlite-3.38.3              |       h707629a_0         1.2 MB
    tk-8.6.11                  |       h3fd3227_1         3.0 MB
    xz-5.2.5                   |       hca72f7f_1         244 KB
    zlib-1.2.12                |       h4dc903c_2          94 KB
    ------------------------------------------------------------
                                           Total:         7.9 MB

The following NEW packages will be INSTALLED:

  bzip2              pkgs/main/osx-64::bzip2-1.0.8-h1de35cc_0
  ca-certificates    pkgs/main/osx-64::ca-certificates-2022.4.26-hecd8cb5_0
  certifi            pkgs/main/noarch::certifi-2020.6.20-pyhd3eb1b0_3
  libcxx             pkgs/main/osx-64::libcxx-12.0.0-h2f01273_0
  libffi             pkgs/main/osx-64::libffi-3.3-hb1e8313_2
  ncurses            pkgs/main/osx-64::ncurses-6.3-hca72f7f_2
  openssl            pkgs/main/osx-64::openssl-1.1.1o-hca72f7f_0
  pip                pkgs/main/osx-64::pip-21.2.4-py310hecd8cb5_0
  python             pkgs/main/osx-64::python-3.10.4-hdfd78df_0
  readline           pkgs/main/osx-64::readline-8.1.2-hca72f7f_1
  setuptools         pkgs/main/osx-64::setuptools-61.2.0-py310hecd8cb5_0
  sqlite             pkgs/main/osx-64::sqlite-3.38.3-h707629a_0
  tk                 pkgs/main/osx-64::tk-8.6.11-h3fd3227_1
  tzdata             pkgs/main/noarch::tzdata-2022a-hda174b7_0
  wheel              pkgs/main/noarch::wheel-0.37.1-pyhd3eb1b0_0
  xz                 pkgs/main/osx-64::xz-5.2.5-hca72f7f_1
  zlib               pkgs/main/osx-64::zlib-1.2.12-h4dc903c_2


Proceed ([y]/n)? y


Downloading and Extracting Packages
setuptools-61.2.0    | 1020 KB   | ######################################################################################################### | 100% 
sqlite-3.38.3        | 1.2 MB    | ######################################################################################################### | 100% 
xz-5.2.5             | 244 KB    | ######################################################################################################### | 100% 
tk-8.6.11            | 3.0 MB    | ######################################################################################################### | 100% 
openssl-1.1.1o       | 2.2 MB    | ######################################################################################################### | 100% 
ca-certificates-2022 | 124 KB    | ######################################################################################################### | 100% 
zlib-1.2.12          | 94 KB     | ######################################################################################################### | 100% 
Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate plotly
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```

## Testing Your Installation

```sh
python3
Python 3.10.4 (main, Mar 31 2022, 03:38:35) [Clang 12.0.0 ] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import plotly

## References

[Getting Started with Plotly in Python](https://plotly.com/python/getting-started/)