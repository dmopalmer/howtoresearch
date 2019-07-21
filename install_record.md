
(base) % **conda create -y -n research -c astropy -c conda-forge python=3.7 jupyterlab ipympl nodejs widgetsnbextension ipython ipykernel matplotlib scipy numpy astropy**
```
Collecting package metadata (current_repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/palmer/anaconda/envs/research

  added / updated specs:
    - astropy
    - ipykernel
    - ipympl
    - ipython
    - jupyterlab
    - matplotlib
    - nodejs
    - numpy
    - python=3.7
    - scipy
    - widgetsnbextension


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    astropy-3.2.1              |   py37h01d97ff_0         6.9 MB  astropy
    bzip2-1.0.8                |       h01d97ff_0         148 KB  conda-forge
    ca-certificates-2019.6.16  |       hecc5488_0         145 KB  conda-forge
    certifi-2019.6.16          |           py37_1         149 KB  conda-forge
    importlib_metadata-0.18    |           py37_0          36 KB  conda-forge
    ipykernel-5.1.1            |   py37h5ca1d4c_0         156 KB  conda-forge
    ipympl-0.3.3               |             py_0         603 KB  conda-forge
    ipython-7.6.1              |   py37h5ca1d4c_0         1.1 MB  conda-forge
    ipywidgets-7.5.0           |             py_0         100 KB  conda-forge
    jedi-0.14.1                |           py37_0         697 KB  conda-forge
    json5-0.8.5                |             py_0          24 KB  conda-forge
    jupyter_client-5.3.1       |             py_0          64 KB  conda-forge
    jupyterlab-1.0.2           |           py37_0        13.6 MB  conda-forge
    jupyterlab_server-1.0.0    |             py_1          23 KB  conda-forge
    libblas-3.8.0              |      10_openblas           6 KB  conda-forge
    libcblas-3.8.0             |      10_openblas           6 KB  conda-forge
    libcxx-8.0.0               |                4         1.0 MB  conda-forge
    libcxxabi-8.0.0            |                4         138 KB  conda-forge
    liblapack-3.8.0            |      10_openblas           6 KB  conda-forge
    libopenblas-0.3.6          |       hd44dcd8_4         8.4 MB  conda-forge
    libsodium-1.0.17           |       h01d97ff_0         308 KB  conda-forge
    matplotlib-3.1.1           |           py37_0           6 KB  conda-forge
    matplotlib-base-3.1.1      |   py37h3a684a6_0         6.6 MB  conda-forge
    more-itertools-7.1.0       |             py_0          46 KB  conda-forge
    nodejs-11.14.0             |       h6de7cb9_1        15.4 MB  conda-forge
    notebook-6.0.0             |           py37_0         6.0 MB  conda-forge
    numpy-1.16.4               |   py37h6b0580a_0         4.1 MB  conda-forge
    openblas-0.3.6             |       hd44dcd8_4         9.2 MB  conda-forge
    openssl-1.1.1c             |       h01d97ff_0         1.9 MB  conda-forge
    packaging-19.0             |             py_0          23 KB  conda-forge
    pandoc-2.7.3               |                0        15.3 MB  conda-forge
    parso-0.5.1                |             py_0          65 KB  conda-forge
    pip-19.1.1                 |           py37_0         1.8 MB  conda-forge
    pluggy-0.12.0              |             py_0          18 KB  conda-forge
    prometheus_client-0.7.1    |             py_0          38 KB  conda-forge
    psutil-5.6.3               |   py37h01d97ff_0         329 KB  conda-forge
    pygments-2.4.2             |             py_0         661 KB  conda-forge
    pyparsing-2.4.1            |             py_0          57 KB  conda-forge
    pyrsistent-0.15.3          |   py37h01d97ff_0          87 KB  conda-forge
    pytest-5.0.1               |           py37_0         347 KB  conda-forge
    python-3.7.3               |       h93065d6_1        20.8 MB  conda-forge
    pyzmq-18.0.2               |   py37hee98d25_2         453 KB  conda-forge
    readline-8.0               |       hcfe32e1_0         415 KB  conda-forge
    scipy-1.3.0                |   py37hab3da7d_0        16.0 MB  conda-forge
    setuptools-41.0.1          |           py37_0         613 KB  conda-forge
    sqlite-3.29.0              |       hb7d70f7_0         2.4 MB  conda-forge
    tk-8.6.9                   |    h2573ce8_1002         3.2 MB  conda-forge
    tornado-6.0.3              |   py37h01d97ff_0         636 KB  conda-forge
    wheel-0.33.4               |           py37_0          34 KB  conda-forge
    widgetsnbextension-3.5.0   |           py37_0         1.8 MB  conda-forge
    zeromq-4.3.2               |       h6de7cb9_2         571 KB  conda-forge
    zipp-0.5.1                 |             py_0           7 KB  conda-forge
    zlib-1.2.11                |    h01d97ff_1005         101 KB  conda-forge
    ------------------------------------------------------------
                                           Total:       142.4 MB

The following NEW packages will be INSTALLED:

  appnope            conda-forge/osx-64::appnope-0.1.0-py37_1000
  astropy            astropy/osx-64::astropy-3.2.1-py37h01d97ff_0
  atomicwrites       conda-forge/noarch::atomicwrites-1.3.0-py_0
  attrs              conda-forge/noarch::attrs-19.1.0-py_0
  backcall           conda-forge/noarch::backcall-0.1.0-py_0
  bleach             conda-forge/noarch::bleach-3.1.0-py_0
  bzip2              conda-forge/osx-64::bzip2-1.0.8-h01d97ff_0
  ca-certificates    conda-forge/osx-64::ca-certificates-2019.6.16-hecc5488_0
  certifi            conda-forge/osx-64::certifi-2019.6.16-py37_1
  cycler             conda-forge/noarch::cycler-0.10.0-py_1
  decorator          conda-forge/noarch::decorator-4.4.0-py_0
  defusedxml         conda-forge/noarch::defusedxml-0.5.0-py_1
  entrypoints        conda-forge/osx-64::entrypoints-0.3-py37_1000
  freetype           conda-forge/osx-64::freetype-2.10.0-h24853df_0
  importlib_metadata conda-forge/osx-64::importlib_metadata-0.18-py37_0
  ipykernel          conda-forge/osx-64::ipykernel-5.1.1-py37h5ca1d4c_0
  ipympl             conda-forge/noarch::ipympl-0.3.3-py_0
  ipython            conda-forge/osx-64::ipython-7.6.1-py37h5ca1d4c_0
  ipython_genutils   conda-forge/noarch::ipython_genutils-0.2.0-py_1
  ipywidgets         conda-forge/noarch::ipywidgets-7.5.0-py_0
  jedi               conda-forge/osx-64::jedi-0.14.1-py37_0
  jinja2             conda-forge/noarch::jinja2-2.10.1-py_0
  json5              conda-forge/noarch::json5-0.8.5-py_0
  jsonschema         conda-forge/osx-64::jsonschema-3.0.1-py37_0
  jupyter_client     conda-forge/noarch::jupyter_client-5.3.1-py_0
  jupyter_core       conda-forge/noarch::jupyter_core-4.4.0-py_0
  jupyterlab         conda-forge/osx-64::jupyterlab-1.0.2-py37_0
  jupyterlab_server  conda-forge/noarch::jupyterlab_server-1.0.0-py_1
  kiwisolver         conda-forge/osx-64::kiwisolver-1.1.0-py37h770b8ee_0
  libblas            conda-forge/osx-64::libblas-3.8.0-10_openblas
  libcblas           conda-forge/osx-64::libcblas-3.8.0-10_openblas
  libcxx             conda-forge/osx-64::libcxx-8.0.0-4
  libcxxabi          conda-forge/osx-64::libcxxabi-8.0.0-4
  libffi             conda-forge/osx-64::libffi-3.2.1-h6de7cb9_1006
  libgfortran        conda-forge/osx-64::libgfortran-3.0.1-0
  liblapack          conda-forge/osx-64::liblapack-3.8.0-10_openblas
  libopenblas        conda-forge/osx-64::libopenblas-0.3.6-hd44dcd8_4
  libpng             conda-forge/osx-64::libpng-1.6.37-h2573ce8_0
  libsodium          conda-forge/osx-64::libsodium-1.0.17-h01d97ff_0
  markupsafe         conda-forge/osx-64::markupsafe-1.1.1-py37h1de35cc_0
  matplotlib         conda-forge/osx-64::matplotlib-3.1.1-py37_0
  matplotlib-base    conda-forge/osx-64::matplotlib-base-3.1.1-py37h3a684a6_0
  mistune            conda-forge/osx-64::mistune-0.8.4-py37h1de35cc_1000
  more-itertools     conda-forge/noarch::more-itertools-7.1.0-py_0
  nbconvert          conda-forge/noarch::nbconvert-5.5.0-py_0
  nbformat           conda-forge/noarch::nbformat-4.4.0-py_1
  ncurses            conda-forge/osx-64::ncurses-6.1-h0a44026_1002
  nodejs             conda-forge/osx-64::nodejs-11.14.0-h6de7cb9_1
  notebook           conda-forge/osx-64::notebook-6.0.0-py37_0
  numpy              conda-forge/osx-64::numpy-1.16.4-py37h6b0580a_0
  openblas           conda-forge/osx-64::openblas-0.3.6-hd44dcd8_4
  openssl            conda-forge/osx-64::openssl-1.1.1c-h01d97ff_0
  packaging          conda-forge/noarch::packaging-19.0-py_0
  pandoc             conda-forge/osx-64::pandoc-2.7.3-0
  pandocfilters      conda-forge/noarch::pandocfilters-1.4.2-py_1
  parso              conda-forge/noarch::parso-0.5.1-py_0
  pexpect            conda-forge/osx-64::pexpect-4.7.0-py37_0
  pickleshare        conda-forge/osx-64::pickleshare-0.7.5-py37_1000
  pip                conda-forge/osx-64::pip-19.1.1-py37_0
  pluggy             conda-forge/noarch::pluggy-0.12.0-py_0
  prometheus_client  conda-forge/noarch::prometheus_client-0.7.1-py_0
  prompt_toolkit     conda-forge/noarch::prompt_toolkit-2.0.9-py_0
  psutil             conda-forge/osx-64::psutil-5.6.3-py37h01d97ff_0
  ptyprocess         conda-forge/noarch::ptyprocess-0.6.0-py_1001
  py                 conda-forge/noarch::py-1.8.0-py_0
  pygments           conda-forge/noarch::pygments-2.4.2-py_0
  pyparsing          conda-forge/noarch::pyparsing-2.4.1-py_0
  pyrsistent         conda-forge/osx-64::pyrsistent-0.15.3-py37h01d97ff_0
  pytest             conda-forge/osx-64::pytest-5.0.1-py37_0
  pytest-arraydiff   astropy/noarch::pytest-arraydiff-0.3-py_0
  pytest-astropy     astropy/noarch::pytest-astropy-0.5.0-py_0
  pytest-doctestplus astropy/noarch::pytest-doctestplus-0.3.0-py_0
  pytest-openfiles   astropy/noarch::pytest-openfiles-0.3.1-py_0
  pytest-remotedata  astropy/noarch::pytest-remotedata-0.3.1-py_0
  python             conda-forge/osx-64::python-3.7.3-h93065d6_1
  python-dateutil    conda-forge/noarch::python-dateutil-2.8.0-py_0
  pyzmq              conda-forge/osx-64::pyzmq-18.0.2-py37hee98d25_2
  readline           conda-forge/osx-64::readline-8.0-hcfe32e1_0
  scipy              conda-forge/osx-64::scipy-1.3.0-py37hab3da7d_0
  send2trash         conda-forge/noarch::send2trash-1.5.0-py_0
  setuptools         conda-forge/osx-64::setuptools-41.0.1-py37_0
  six                conda-forge/osx-64::six-1.12.0-py37_1000
  sqlite             conda-forge/osx-64::sqlite-3.29.0-hb7d70f7_0
  terminado          conda-forge/osx-64::terminado-0.8.2-py37_0
  testpath           conda-forge/noarch::testpath-0.4.2-py_1001
  tk                 conda-forge/osx-64::tk-8.6.9-h2573ce8_1002
  tornado            conda-forge/osx-64::tornado-6.0.3-py37h01d97ff_0
  traitlets          conda-forge/osx-64::traitlets-4.3.2-py37_1000
  wcwidth            conda-forge/noarch::wcwidth-0.1.7-py_1
  webencodings       conda-forge/noarch::webencodings-0.5.1-py_1
  wheel              conda-forge/osx-64::wheel-0.33.4-py37_0
  widgetsnbextension conda-forge/osx-64::widgetsnbextension-3.5.0-py37_0
  xz                 conda-forge/osx-64::xz-5.2.4-h1de35cc_1001
  zeromq             conda-forge/osx-64::zeromq-4.3.2-h6de7cb9_2
  zipp               conda-forge/noarch::zipp-0.5.1-py_0
  zlib               conda-forge/osx-64::zlib-1.2.11-h01d97ff_1005



Downloading and Extracting Packages
ipykernel-5.1.1      | 156 KB    | ####################################################################################################################################################################### | 100%
packaging-19.0       | 23 KB     | ####################################################################################################################################################################### | 100%
pyrsistent-0.15.3    | 87 KB     | ####################################################################################################################################################################### | 100%
libopenblas-0.3.6    | 8.4 MB    | ####################################################################################################################################################################### | 100%
tornado-6.0.3        | 636 KB    | ####################################################################################################################################################################### | 100%
zipp-0.5.1           | 7 KB      | ####################################################################################################################################################################### | 100%
jupyterlab_server-1. | 23 KB     | ####################################################################################################################################################################### | 100%
certifi-2019.6.16    | 149 KB    | ####################################################################################################################################################################### | 100%
tk-8.6.9             | 3.2 MB    | ####################################################################################################################################################################### | 100%
nodejs-11.14.0       | 15.4 MB   | ####################################################################################################################################################################### | 100%
jupyter_client-5.3.1 | 64 KB     | ####################################################################################################################################################################### | 100%
pluggy-0.12.0        | 18 KB     | ####################################################################################################################################################################### | 100%
setuptools-41.0.1    | 613 KB    | ####################################################################################################################################################################### | 100%
libblas-3.8.0        | 6 KB      | ####################################################################################################################################################################### | 100%
libcxx-8.0.0         | 1.0 MB    | ####################################################################################################################################################################### | 100%
pytest-5.0.1         | 347 KB    | ####################################################################################################################################################################### | 100%
bzip2-1.0.8          | 148 KB    | ####################################################################################################################################################################### | 100%
jedi-0.14.1          | 697 KB    | ####################################################################################################################################################################### | 100%
zeromq-4.3.2         | 571 KB    | ####################################################################################################################################################################### | 100%
pyzmq-18.0.2         | 453 KB    | ####################################################################################################################################################################### | 100%
libcblas-3.8.0       | 6 KB      | ####################################################################################################################################################################### | 100%
parso-0.5.1          | 65 KB     | ####################################################################################################################################################################### | 100%
pygments-2.4.2       | 661 KB    | ####################################################################################################################################################################### | 100%
sqlite-3.29.0        | 2.4 MB    | ####################################################################################################################################################################### | 100%
libsodium-1.0.17     | 308 KB    | ####################################################################################################################################################################### | 100%
zlib-1.2.11          | 101 KB    | ####################################################################################################################################################################### | 100%
readline-8.0         | 415 KB    | ####################################################################################################################################################################### | 100%
python-3.7.3         | 20.8 MB   | ####################################################################################################################################################################### | 100%
prometheus_client-0. | 38 KB     | ####################################################################################################################################################################### | 100%
numpy-1.16.4         | 4.1 MB    | ####################################################################################################################################################################### | 100%
wheel-0.33.4         | 34 KB     | ####################################################################################################################################################################### | 100%
ipywidgets-7.5.0     | 100 KB    | ####################################################################################################################################################################### | 100%
matplotlib-3.1.1     | 6 KB      | ####################################################################################################################################################################### | 100%
psutil-5.6.3         | 329 KB    | ####################################################################################################################################################################### | 100%
more-itertools-7.1.0 | 46 KB     | ####################################################################################################################################################################### | 100%
pandoc-2.7.3         | 15.3 MB   | ####################################################################################################################################################################### | 100%
libcxxabi-8.0.0      | 138 KB    | ####################################################################################################################################################################### | 100%
notebook-6.0.0       | 6.0 MB    | ####################################################################################################################################################################### | 100%
importlib_metadata-0 | 36 KB     | ####################################################################################################################################################################### | 100%
ipympl-0.3.3         | 603 KB    | ####################################################################################################################################################################### | 100%
ipython-7.6.1        | 1.1 MB    | ####################################################################################################################################################################### | 100%
json5-0.8.5          | 24 KB     | ####################################################################################################################################################################### | 100%
liblapack-3.8.0      | 6 KB      | ####################################################################################################################################################################### | 100%
openblas-0.3.6       | 9.2 MB    | ####################################################################################################################################################################### | 100%
matplotlib-base-3.1. | 6.6 MB    | ####################################################################################################################################################################### | 100%
widgetsnbextension-3 | 1.8 MB    | ####################################################################################################################################################################### | 100%
openssl-1.1.1c       | 1.9 MB    | ####################################################################################################################################################################### | 100%
pip-19.1.1           | 1.8 MB    | ####################################################################################################################################################################### | 100%
astropy-3.2.1        | 6.9 MB    | ####################################################################################################################################################################### | 100%
ca-certificates-2019 | 145 KB    | ####################################################################################################################################################################### | 100%
scipy-1.3.0          | 16.0 MB   | ####################################################################################################################################################################### | 100%
jupyterlab-1.0.2     | 13.6 MB   | ####################################################################################################################################################################### | 100%
pyparsing-2.4.1      | 57 KB     | ####################################################################################################################################################################### | 100%
Preparing transaction: done
Verifying transaction: done
Executing transaction: - b'Enabling notebook extension jupyter-js-widgets/extension...\n      - Validating: \x1b[32mOK\x1b[0m\n'
done
#
# To activate this environment, use
#
#     $ conda activate research
#
# To deactivate an active environment, use
#
#     $ conda deactivate
```
(base) % **conda activate research**
(research) % **jupyter labextension install @jupyter-widgets/jupyterlab-manager**
```
Building jupyterlab assets
```
(research) % jupyter labextension install jupyter-matplotlib
```
Building jupyterlab assets
```
(research) % python -m ipykernel install --user --name research --display-name="python research"
```
Installed kernelspec research in /Users/palmer/Library/Jupyter/kernels/research
```
(research) %