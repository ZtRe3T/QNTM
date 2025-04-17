(base) PS C:\Users\test> conda list | Select-String -NotMatch "python|conda|#" | ForEach-Object { $_.ToString().Split(" ")[0] } | Where-Object { $_ -ne "" } | % { conda remove -y $_ }

PackagesNotFoundError: The following packages are missing from the target environment:
  - absl-py


Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-assistant


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-assistant-server


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-core


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-core-server


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-panels


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-panels-server


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-share-notebook


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-share-notebook-server


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aext-shared


The following packages will be REMOVED:

  aext-assistant-4.0.15-py312haa95532_jl4_0
  aext-assistant-server-4.0.15-py312haa95532_0
  aext-core-4.0.15-py312haa95532_jl4_0
  aext-core-server-4.0.15-py312haa95532_1
  aext-panels-4.0.15-py312haa95532_0
  aext-panels-server-4.0.15-py312haa95532_0
  aext-share-notebook-4.0.15-py312haa95532_0
  aext-share-notebook-server-4.0.15-py312haa95532_0
  aext-shared-4.0.15-py312haa95532_0
  anaconda-toolbox-4.0.15-py312haa95532_0


Preparing transaction: done
Verifying transaction: failed

RemoveError: 'setuptools' is a dependency of conda and cannot be removed from
conda's operating environment.

Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aiobotocore


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    _anaconda_depends-2023.03  |          py310_0          67 KB
    aext-assistant-4.1.0       |py310haa95532_jl4_0         3.5 MB
    aext-assistant-server-4.1.0|  py310haa95532_0          20 KB
    aext-core-4.1.0            |py310haa95532_jl4_0         227 KB
    aext-core-server-4.1.0     |  py310haa95532_0          12 KB
    aext-panels-4.1.0          |  py310haa95532_0         1.7 MB
    aext-panels-server-4.1.0   |  py310haa95532_0          81 KB
    aext-project-filebrowser-server-4.1.0|  py310haa95532_0         246 KB
    aext-share-notebook-4.1.0  |  py310haa95532_0         542 KB
    aext-share-notebook-server-4.1.0|  py310haa95532_0           9 KB
    aext-shared-4.1.0          |  py310haa95532_0          35 KB
    aiohappyeyeballs-2.4.4     |  py310haa95532_0          24 KB
    aiohttp-3.11.10            |  py310h827c3e9_0         785 KB
    alabaster-0.7.16           |  py310haa95532_0          19 KB
    alembic-1.13.3             |  py310haa95532_0         367 KB
    altair-5.5.0               |  py310haa95532_0         774 KB
    anaconda-anon-usage-0.7.0  |py310hfc23b7f_101          30 KB
    anaconda-auth-0.8.4        |  py310haa95532_0         131 KB
    anaconda-catalogs-0.2.0    |  py310haa95532_0          14 KB
    anaconda-cli-base-0.5.2    |  py310haa95532_0          54 KB
    anaconda-client-1.13.0     |  py310haa95532_1         812 KB
    anaconda-cloud-auth-0.8.4  |  py310haa95532_0          29 KB
    anaconda-navigator-2.6.5   |  py310haa95532_0         5.0 MB
    anaconda-project-0.11.1    |  py310haa95532_0         517 KB
    anaconda-toolbox-4.1.0     |  py310haa95532_0         2.2 MB
    annotated-types-0.6.0      |  py310haa95532_0          23 KB
    anyio-4.6.2                |  py310haa95532_0         203 KB
    argon2-cffi-bindings-21.2.0|  py310h827c3e9_1          41 KB
    arrow-1.3.0                |  py310haa95532_0         161 KB
    astroid-3.3.8              |  py310haa95532_0         552 KB
    astropy-6.1.3              |  py310h827c3e9_0        11.8 MB
    astropy-iers-data-0.2025.1.13.0.34.51|  py310haa95532_0         1.7 MB
    async-lru-2.0.4            |  py310haa95532_0          19 KB
    async-timeout-5.0.1        |  py310haa95532_0          14 KB
    asyncssh-2.17.0            |  py310haa95532_0         667 KB
    attrs-24.3.0               |  py310haa95532_0         154 KB
    babel-2.16.0               |  py310haa95532_0         6.8 MB
    bcrypt-3.2.0               |  py310h827c3e9_2          46 KB
    beautifulsoup4-4.12.3      |  py310haa95532_0         217 KB
    black-24.10.0              |  py310haa95532_0         338 KB
    blinker-1.9.0              |  py310haa95532_0          21 KB
    bokeh-3.6.2                |  py310haa95532_0         5.5 MB
    boltons-24.1.0             |  py310haa95532_0         420 KB
    bottleneck-1.4.2           |  py310hc99e966_0         130 KB
    brotli-python-1.0.9        |  py310h5da7b33_9         346 KB
    cachetools-5.5.1           |  py310haa95532_0          30 KB
    certifi-2025.1.31          |  py310haa95532_0         163 KB
    cffi-1.17.1                |  py310h827c3e9_1         254 KB
    chardet-4.0.0              |py310haa95532_1003         220 KB
    click-8.1.8                |  py310haa95532_0         279 KB
    cloudpickle-3.0.0          |  py310haa95532_0          35 KB
    colorama-0.4.6             |  py310haa95532_0          32 KB
    colorcet-3.1.0             |  py310haa95532_0         567 KB
    comm-0.2.1                 |  py310haa95532_0          15 KB
    conda-25.3.1               |  py310haa95532_0         916 KB
    conda-build-25.3.2         |  py310haa95532_0         593 KB
    conda-content-trust-0.2.0  |  py310haa95532_1          82 KB
    conda-index-0.5.0          |  py310haa95532_0         217 KB
    conda-libmamba-solver-25.3.0|     pyhd3eb1b0_0          39 KB
    conda-pack-0.7.1           |  py310haa95532_0          73 KB
    conda-package-handling-2.4.0|  py310haa95532_0         297 KB
    conda-package-streaming-0.11.0|  py310haa95532_0          31 KB
    conda-repo-cli-1.0.165     |  py310haa95532_0         190 KB
    conda-token-0.6.0          |     pyhd3eb1b0_0          11 KB
    constantly-23.10.4         |  py310haa95532_0          28 KB
    contourpy-1.3.1            |  py310h214f63a_0         217 KB
    cookiecutter-2.6.0         |  py310haa95532_0         145 KB
    cpp-expected-1.1.0         |       h214f63a_0         131 KB
    cryptography-44.0.1        |  py310hbd6ee87_0         1.4 MB
    cssselect-1.2.0            |  py310haa95532_0          38 KB
    cytoolz-1.0.1              |  py310h827c3e9_0         328 KB
    daal4py-2023.1.1           |  py310hf497b98_0         9.7 MB
    dal-2023.1.1               |   h59b6b97_48682        26.5 MB
    dask-2025.2.0              |  py310haa95532_0           7 KB
    dask-core-2025.2.0         |  py310haa95532_0         2.5 MB
    dask-expr-2.0.0            |  py310haa95532_0           9 KB
    datasets-3.3.2             |  py310haa95532_0         680 KB
    datashader-0.18.0          |  py310haa95532_0        17.0 MB
    debugpy-1.8.11             |  py310h5da7b33_0         3.2 MB
    deprecated-1.2.13          |  py310haa95532_0          16 KB
    dill-0.3.8                 |  py310haa95532_0         204 KB
    distributed-2025.2.0       |  py310haa95532_0         1.4 MB
    distro-1.9.0               |  py310haa95532_0          57 KB
    docstring-to-markdown-0.11 |  py310haa95532_0          32 KB
    docutils-0.21.2            |  py310haa95532_0         846 KB
    et_xmlfile-1.1.0           |  py310haa95532_0          10 KB
    exceptiongroup-1.2.0       |  py310haa95532_0          31 KB
    filelock-3.17.0            |  py310haa95532_0          33 KB
    flake8-7.1.1               |  py310haa95532_0         122 KB
    flask-3.1.0                |  py310haa95532_0         212 KB
    fonttools-4.55.3           |  py310h827c3e9_0         2.1 MB
    frozendict-2.4.2           |  py310h2bbff1b_0          53 KB
    frozenlist-1.5.0           |  py310h827c3e9_0          61 KB
    fsspec-2024.12.0           |  py310haa95532_0         296 KB
    gensim-4.3.3               |  py310hc64d2fc_0        42.1 MB
    giflib-5.2.2               |       h7edc060_0         105 KB
    gitpython-3.1.43           |  py310haa95532_0         286 KB
    gmp-6.3.0                  |       h537511b_0         330 KB
    gmpy2-2.2.1                |  py310h827c3e9_0         205 KB
    greenlet-3.1.1             |  py310h5da7b33_0         212 KB
    h11-0.14.0                 |  py310haa95532_0          91 KB
    h5py-3.12.1                |  py310h535c9fb_1         1.1 MB
    hdf5-1.14.5                |       ha36df97_2         2.1 MB
    holoviews-1.20.2           |  py310haa95532_0         5.2 MB
    httpcore-1.0.2             |  py310haa95532_0          87 KB
    httpx-0.27.0               |  py310haa95532_0         197 KB
    huggingface_hub-0.29.2     |  py310haa95532_0         566 KB
    hvplot-0.11.2              |  py310haa95532_0         278 KB
    idna-3.7                   |  py310haa95532_0         132 KB
    imagecodecs-2024.9.22      |  py310hacb3832_0        10.1 MB
    imageio-2.37.0             |  py310haa95532_0         512 KB
    imagesize-1.4.1            |  py310haa95532_0          14 KB
    imbalanced-learn-0.13.0    |  py310haa95532_0         298 KB
    importlib-metadata-8.5.0   |  py310haa95532_0          46 KB
    importlib_metadata-8.5.0   |       hd3eb1b0_0           9 KB
    inflection-0.5.1           |  py310haa95532_0          11 KB
    intake-2.0.7               |  py310haa95532_0         225 KB
    ipykernel-6.29.5           |  py310haa95532_1         208 KB
    ipython-8.30.0             |  py310haa95532_0         1.2 MB
    ipywidgets-7.8.5           |  py310haa95532_0         180 KB
    isort-6.0.1                |  py310haa95532_0         300 KB
    itemloaders-1.3.2          |  py310haa95532_0          30 KB
    itsdangerous-2.2.0         |  py310haa95532_0          32 KB
    jedi-0.19.2                |  py310haa95532_0         1.1 MB
    jellyfish-1.1.3            |  py310h8ecf97c_0         232 KB
    jinja2-3.1.6               |  py310haa95532_0         279 KB
    jmespath-1.0.1             |  py310haa95532_0          40 KB
    joblib-1.4.2               |  py310haa95532_0         402 KB
    jsonpatch-1.33             |  py310haa95532_1          57 KB
    jsonschema-4.23.0          |  py310haa95532_0         180 KB
    jsonschema-specifications-2023.7.1|  py310haa95532_0          16 KB
    jupyter-1.1.1              |  py310haa95532_0           9 KB
    jupyter-lsp-2.2.0          |  py310haa95532_0          87 KB
    jupyter_client-8.6.3       |  py310haa95532_0         214 KB
    jupyter_console-6.6.3      |  py310haa95532_0          64 KB
    jupyter_core-5.7.2         |  py310haa95532_0         110 KB
    jupyter_events-0.12.0      |  py310haa95532_0          63 KB
    jupyter_server-2.15.0      |  py310haa95532_0         527 KB
    jupyter_server_terminals-0.5.3|  py310haa95532_0          26 KB
    jupyterlab-4.3.4           |  py310haa95532_0         5.5 MB
    jupyterlab-variableinspector-3.2.4|  py310haa95532_0         123 KB
    jupyterlab_server-2.27.3   |  py310haa95532_0          88 KB
    keyring-24.3.1             |  py310haa95532_0          84 KB
    kiwisolver-1.4.8           |  py310h5da7b33_0          63 KB
    lazy-object-proxy-1.10.0   |  py310h827c3e9_1          45 KB
    lazy_loader-0.4            |  py310haa95532_0          21 KB
    libaec-1.1.3               |       hcdb6601_0          59 KB
    libarchive-3.7.7           |       h9243413_0         1.8 MB
    libavif-1.1.1              |       h827c3e9_0         1.9 MB
    libmamba-2.0.5             |       hcd6fe79_1         4.7 MB
    libmambapy-2.0.5           |  py310h214f63a_1         459 KB
    libsolv-0.7.30             |       hf2fb9eb_1         473 KB
    libxml2-2.13.7             |       h866ff63_0         2.9 MB
    linkify-it-py-2.0.0        |  py310haa95532_0          35 KB
    llvmlite-0.44.0            |  py310h8b1c7eb_1        19.6 MB
    locket-1.0.0               |  py310haa95532_0          13 KB
    lxml-5.3.0                 |  py310h395c83e_1         1.1 MB
    lz4-4.3.2                  |  py310h827c3e9_1          90 KB
    mako-1.2.3                 |  py310haa95532_0         143 KB
    markdown-3.4.1             |  py310haa95532_0         149 KB
    markdown-it-py-2.2.0       |  py310haa95532_1         130 KB
    markupsafe-3.0.2           |  py310h827c3e9_0          36 KB
    matplotlib-3.10.0          |  py310haa95532_0           8 KB
    matplotlib-base-3.10.0     |  py310he19b0ae_0         9.5 MB
    matplotlib-inline-0.1.6    |  py310haa95532_0          17 KB
    mdit-py-plugins-0.3.0      |  py310haa95532_0          52 KB
    mdurl-0.1.0                |  py310haa95532_0          19 KB
    menuinst-2.2.0             |  py310h5da7b33_1         200 KB
    mistune-3.1.2              |  py310haa95532_0         120 KB
    mkl-service-2.4.0          |  py310h827c3e9_2          66 KB
    mkl_fft-1.3.11             |  py310h827c3e9_0         168 KB
    mkl_random-1.2.8           |  py310hc64d2fc_0         257 KB
    more-itertools-10.3.0      |  py310haa95532_0         124 KB
    mpc-1.3.1                  |       h827c3e9_0          85 KB
    mpfr-4.2.1                 |       h56c3642_0         266 KB
    mpmath-1.3.0               |  py310haa95532_0         834 KB
    msgpack-python-1.0.3       |  py310h59b6b97_0          76 KB
    multidict-6.1.0            |  py310h827c3e9_0          60 KB
    multipledispatch-0.6.0     |  py310haa95532_0          23 KB
    multiprocess-0.70.15       |  py310haa95532_0         248 KB
    mypy-1.14.1                |  py310h827c3e9_0         8.4 MB
    mypy_extensions-1.0.0      |  py310haa95532_0          12 KB
    narwhals-1.31.0            |  py310haa95532_1         453 KB
    navigator-updater-0.5.1    |  py310haa95532_0         2.3 MB
    nb_conda_kernels-2.5.2     |  py310haa95532_1          40 KB
    nbclient-0.10.2            |  py310haa95532_0          67 KB
    nbconvert-7.16.6           |  py310haa95532_0           9 KB
    nbconvert-core-7.16.6      |  py310haa95532_0         509 KB
    nbconvert-pandoc-7.16.6    |  py310haa95532_0           9 KB
    nbformat-5.10.4            |  py310haa95532_0         167 KB
    nest-asyncio-1.6.0         |  py310haa95532_0          15 KB
    networkx-3.4.2             |  py310haa95532_0         2.5 MB
    nlohmann_json-3.11.2       |       h6c2663c_0         126 KB
    nltk-3.9.1                 |  py310haa95532_0         2.3 MB
    notebook-7.3.2             |  py310haa95532_0        10.3 MB
    notebook-shim-0.2.4        |  py310haa95532_0          24 KB
    numba-0.61.0               |  py310h5da7b33_1         4.5 MB
    numexpr-2.10.1             |  py310h4cd664f_0         176 KB
    numpy-1.26.4               |  py310h055cbcc_0          11 KB
    numpy-base-1.26.4          |  py310h65a83cf_0         8.6 MB
    numpydoc-1.7.0             |  py310haa95532_0         175 KB
    openpyxl-3.1.5             |  py310h827c3e9_1         567 KB
    overrides-7.4.0            |  py310haa95532_0          30 KB
    packaging-24.2             |  py310haa95532_0         175 KB
    pandas-2.2.3               |  py310h5da7b33_0        12.0 MB
    pandoc-2.12                |       haa95532_3        14.6 MB
    panel-1.6.0                |  py310haa95532_0        21.1 MB
    param-2.2.0                |  py310haa95532_0         205 KB
    parsel-1.8.1               |  py310haa95532_0          45 KB
    parso-0.8.4                |  py310haa95532_0         195 KB
    partd-1.4.2                |  py310haa95532_0          38 KB
    pathspec-0.10.3            |  py310haa95532_0          49 KB
    patsy-1.0.1                |  py310haa95532_0         289 KB
    pep8-1.7.1                 |  py310haa95532_1          69 KB
    pillow-11.1.0              |  py310h096bfcc_0         770 KB
    pip-25.0                   |  py310haa95532_0         2.5 MB
    pkce-1.0.3                 |  py310haa95532_0           9 KB
    pkginfo-1.12.0             |  py310haa95532_0          83 KB
    platformdirs-4.3.7         |  py310haa95532_0          37 KB
    plotly-5.24.1              |  py310h9909e9c_1        10.0 MB
    pluggy-1.5.0               |  py310haa95532_0          39 KB
    ply-3.11                   |  py310haa95532_0          81 KB
    prometheus_client-0.21.1   |  py310haa95532_0         121 KB
    prompt-toolkit-3.0.43      |  py310haa95532_0         592 KB
    propcache-0.3.1            |  py310h827c3e9_0          60 KB
    protobuf-4.25.3            |  py310hf91db99_1         336 KB
    psutil-5.9.0               |  py310h827c3e9_1         388 KB
    py-cpuinfo-9.0.0           |  py310haa95532_0          62 KB
    py-lief-0.12.3             |  py310hd77b12b_0         2.0 MB
    pyarrow-16.1.0             |  py310hc64d2fc_0         3.6 MB
    pycodestyle-2.12.1         |  py310haa95532_0          87 KB
    pycosat-0.6.6              |  py310h827c3e9_2          88 KB
    pyct-0.5.0                 |  py310haa95532_0          49 KB
    pycurl-7.45.6              |  py310h51539b2_0         150 KB
    pydantic-2.10.3            |  py310haa95532_0         657 KB
    pydantic-core-2.27.1       |  py310h636fa0f_0         1.8 MB
    pydantic-settings-2.6.1    |  py310haa95532_0          56 KB
    pydeck-0.9.1               |  py310haa95532_0         5.0 MB
    pydispatcher-2.0.5         |  py310haa95532_2          20 KB
    pydocstyle-6.3.0           |  py310haa95532_0          89 KB
    pyerfa-2.0.1.5             |  py310h827c3e9_0         382 KB
    pyflakes-3.2.0             |  py310haa95532_0         141 KB
    pygithub-2.4.0             |  py310haa95532_0         1.8 MB
    pygments-2.19.1            |  py310haa95532_0         1.9 MB
    pyjwt-2.10.1               |  py310haa95532_0          77 KB
    pylint-3.3.5               |  py310haa95532_0         1.1 MB
    pylint-venv-3.0.3          |  py310haa95532_0          12 KB
    pynacl-1.5.0               |  py310h7edc060_1         1.3 MB
    pyodbc-5.2.0               |  py310h5da7b33_0          75 KB
    pyopenssl-25.0.0           |  py310hb6ff9d5_0          97 KB
    pyparsing-3.2.0            |  py310haa95532_0         424 KB
    pyqt-5.15.10               |  py310h5da7b33_1         4.2 MB
    pyqt5-sip-12.13.0          |  py310h827c3e9_1          86 KB
    pyqtwebengine-5.15.10      |  py310h5da7b33_1         143 KB
    pysocks-1.7.1              |  py310haa95532_0          28 KB
    pytables-3.10.1            |  py310he42c613_1         2.1 MB
    pytest-8.3.4               |  py310haa95532_0         1.1 MB
    python-3.10.16             |       h4607a30_1        16.3 MB
    python-dateutil-2.9.0post0 |  py310haa95532_2         281 KB
    python-dotenv-0.21.0       |  py310haa95532_0          52 KB
    python-fastjsonschema-2.20.0|  py310haa95532_0         250 KB
    python-json-logger-3.2.1   |  py310haa95532_0          25 KB
    python-lmdb-1.6.2          |  py310h5da7b33_0         149 KB
    python-lsp-black-2.0.0     |  py310haa95532_1          16 KB
    python-lsp-server-1.12.2   |  py310hbc747e5_0         175 KB
    python-xxhash-3.5.0        |  py310h827c3e9_0          32 KB
    pytoolconfig-1.2.6         |  py310haa95532_0          31 KB
    pytz-2024.1                |  py310haa95532_0         215 KB
    pyuca-1.2                  |  py310haa95532_1         726 KB
    pyviz_comms-3.0.2          |  py310haa95532_0          54 KB
    pywavelets-1.8.0           |  py310h827c3e9_0         3.5 MB
    pywin32-308                |  py310h5da7b33_0        10.5 MB
    pywin32-ctypes-0.2.2       |  py310haa95532_0          44 KB
    pywinpty-2.0.15            |  py310h72d21ff_0         230 KB
    pyyaml-6.0.2               |  py310h827c3e9_0         174 KB
    pyzmq-26.2.0               |  py310h5da7b33_0         334 KB
    qstylizer-0.2.2            |  py310haa95532_0          30 KB
    qtawesome-1.4.0            |  py310haa95532_0         1.9 MB
    qtconsole-5.6.1            |  py310haa95532_1         238 KB
    qtpy-2.4.1                 |  py310haa95532_0         127 KB
    queuelib-1.6.2             |  py310haa95532_0          29 KB
    readchar-4.0.5             |  py310haa95532_0          16 KB
    referencing-0.30.2         |  py310haa95532_0          63 KB
    regex-2024.11.6            |  py310h827c3e9_0         346 KB
    requests-2.32.3            |  py310haa95532_1         101 KB
    requests-toolbelt-1.0.0    |  py310haa95532_0          71 KB
    rfc3339-validator-0.1.4    |  py310haa95532_0          10 KB
    rfc3986-validator-0.1.1    |  py310haa95532_0          10 KB
    rich-13.9.4                |  py310haa95532_0         511 KB
    rope-1.13.0                |  py310haa95532_0         461 KB
    rpds-py-0.22.3             |  py310h636fa0f_0         248 KB
    rtree-1.0.1                |  py310h2eaa2aa_0          50 KB
    ruamel.yaml-0.18.6         |  py310h827c3e9_0         207 KB
    ruamel.yaml.clib-0.2.8     |  py310h827c3e9_0         126 KB
    ruamel_yaml-0.17.21        |  py310h2bbff1b_0         193 KB
    safetensors-0.5.3          |  py310haa69e8e_0         322 KB
    scikit-image-0.25.0        |  py310h5da7b33_0        10.7 MB
    scikit-learn-1.6.1         |  py310h585ebfc_0         8.4 MB
    scikit-learn-intelex-2023.1.1|  py310haa95532_0         114 KB
    scipy-1.13.1               |  py310h8640f81_1        23.0 MB
    scrapy-2.12.0              |  py310haa95532_1         778 KB
    seaborn-0.13.2             |  py310haa95532_2         608 KB
    semver-3.0.2               |  py310haa95532_1         103 KB
    send2trash-1.8.2           |  py310haa95532_1          85 KB
    sentry-sdk-2.18.0          |  py310haa95532_0         444 KB
    setuptools-75.8.0          |  py310haa95532_0         1.7 MB
    shellingham-1.5.0          |  py310haa95532_0          19 KB
    simdjson-3.10.1            |       h214f63a_0         275 KB
    sip-6.7.12                 |  py310h5da7b33_1         537 KB
    six-1.17.0                 |  py310haa95532_0          32 KB
    sklearn-compat-0.1.3       |  py310haa95532_0          29 KB
    smart_open-5.2.1           |  py310haa95532_0          81 KB
    sniffio-1.3.0              |  py310haa95532_0          17 KB
    soupsieve-2.5              |  py310haa95532_0          71 KB
    spdlog-1.11.0              |       h59b6b97_0         195 KB
    sphinx-7.3.7               |  py310h827c3e9_0         2.6 MB
    sphinxcontrib-serializinghtml-2.0.0|     pyhd3eb1b0_0          27 KB
    spyder-6.0.5               |  py310haa95532_0         9.9 MB
    spyder-kernels-3.0.3       |  py310hbc747e5_0         337 KB
    sqlalchemy-2.0.37          |  py310h54f65d0_0         5.9 MB
    statsmodels-0.14.4         |  py310h827c3e9_0        10.4 MB
    streamlit-1.44.1           |  py310haa95532_0         8.6 MB
    superqt-0.7.3              |  py310hbc747e5_0         186 KB
    sympy-1.13.3               |  py310haa95532_1        11.3 MB
    tabulate-0.9.0             |  py310haa95532_0          76 KB
    tbb4py-2021.8.0            |  py310h59b6b97_0          82 KB
    tenacity-9.0.0             |  py310haa95532_0          54 KB
    terminado-0.17.1           |  py310haa95532_0          33 KB
    threadpoolctl-3.5.0        |  py310h9909e9c_0          43 KB
    tifffile-2024.12.12        |  py310haa95532_0         434 KB
    tinycss2-1.4.0             |  py310haa95532_0          99 KB
    tldextract-5.1.2           |  py310haa95532_0         147 KB
    tokenizers-0.21.0          |  py310h5bc5163_0         2.0 MB
    tomli-2.0.1                |  py310haa95532_0          25 KB
    tomlkit-0.13.2             |  py310haa95532_0          86 KB
    toolz-1.0.0                |  py310haa95532_0         113 KB
    tornado-6.4.2              |  py310h827c3e9_0         680 KB
    tqdm-4.67.1                |  py310h9909e9c_0         162 KB
    traitlets-5.14.3           |  py310haa95532_0         182 KB
    transformers-4.49.0        |  py310haa95532_0        21.7 MB
    truststore-0.10.0          |  py310haa95532_0          40 KB
    twisted-23.10.0            |  py310haa95532_0         5.5 MB
    twisted-iocpsupport-1.0.2  |  py310h827c3e9_1          55 KB
    typer-0.9.0                |  py310haa95532_0          85 KB
    typing-extensions-4.12.2   |  py310haa95532_0          10 KB
    typing_extensions-4.12.2   |  py310haa95532_0          65 KB
    uc-micro-py-1.0.1          |  py310haa95532_0          11 KB
    ujson-5.10.0               |  py310h5da7b33_1         147 KB
    unicodedata2-15.1.0        |  py310h827c3e9_1         525 KB
    unidecode-1.3.8            |  py310haa95532_0         306 KB
    urllib3-2.3.0              |  py310haa95532_0         191 KB
    vs2015_runtime-14.42.34433 |       hbfb602d_5         1.2 MB
    w3lib-2.1.2                |  py310haa95532_0          36 KB
    watchdog-4.0.2             |  py310haa95532_0         140 KB
    webencodings-0.5.1         |  py310haa95532_1          21 KB
    websocket-client-1.8.0     |  py310haa95532_0         118 KB
    werkzeug-3.1.3             |  py310haa95532_0         331 KB
    whatthepatch-1.0.2         |  py310haa95532_0          23 KB
    wheel-0.45.1               |  py310haa95532_0         145 KB
    widgetsnbextension-3.6.10  |  py310haa95532_0         664 KB
    win_inet_pton-1.1.0        |  py310haa95532_0           9 KB
    wrapt-1.17.0               |  py310h827c3e9_0          61 KB
    xarray-2024.11.0           |  py310haa95532_0         2.1 MB
    xlwings-0.32.1             |  py310haa95532_1         1.2 MB
    xxhash-0.8.0               |       h2bbff1b_3          87 KB
    xyzservices-2022.9.0       |  py310haa95532_1          45 KB
    yapf-0.40.2                |  py310haa95532_0         403 KB
    yarl-1.18.0                |  py310h827c3e9_0         143 KB
    zict-3.0.0                 |  py310haa95532_0          93 KB
    zipp-3.21.0                |  py310haa95532_0          28 KB
    zope-1.0                   |  py310haa95532_1           4 KB
    zope.interface-7.1.1       |  py310h827c3e9_0         336 KB
    zstandard-0.23.0           |  py310h4fc1ca9_1         342 KB
    ------------------------------------------------------------
                                           Total:       546.3 MB

The following NEW packages will be INSTALLED:

  aext-project-file~ pkgs/main/win-64::aext-project-filebrowser-server-4.1.0-py310haa95532_0
  alembic            pkgs/main/win-64::alembic-1.13.3-py310haa95532_0
  anaconda-auth      pkgs/main/win-64::anaconda-auth-0.8.4-py310haa95532_0
  anaconda-cli-base  pkgs/main/win-64::anaconda-cli-base-0.5.2-py310haa95532_0
  async-timeout      pkgs/main/win-64::async-timeout-5.0.1-py310haa95532_0
  asyncssh           pkgs/main/win-64::asyncssh-2.17.0-py310haa95532_0
  cpp-expected       pkgs/main/win-64::cpp-expected-1.1.0-h214f63a_0
  daal4py            pkgs/main/win-64::daal4py-2023.1.1-py310hf497b98_0
  dal                pkgs/main/win-64::dal-2023.1.1-h59b6b97_48682
  datasets           pkgs/main/win-64::datasets-3.3.2-py310haa95532_0
  deprecated         pkgs/main/win-64::deprecated-1.2.13-py310haa95532_0
  dill               pkgs/main/win-64::dill-0.3.8-py310haa95532_0
  exceptiongroup     pkgs/main/win-64::exceptiongroup-1.2.0-py310haa95532_0
  gmp                pkgs/main/win-64::gmp-6.3.0-h537511b_0
  gmpy2              pkgs/main/win-64::gmpy2-2.2.1-py310h827c3e9_0
  greenlet           pkgs/main/win-64::greenlet-3.1.1-py310h5da7b33_0
  huggingface_hub    pkgs/main/win-64::huggingface_hub-0.29.2-py310haa95532_0
  importlib_metadata pkgs/main/noarch::importlib_metadata-8.5.0-hd3eb1b0_0
  mako               pkgs/main/win-64::mako-1.2.3-py310haa95532_0
  mpc                pkgs/main/win-64::mpc-1.3.1-h827c3e9_0
  mpfr               pkgs/main/win-64::mpfr-4.2.1-h56c3642_0
  multiprocess       pkgs/main/win-64::multiprocess-0.70.15-py310haa95532_0
  narwhals           pkgs/main/win-64::narwhals-1.31.0-py310haa95532_1
  nb_conda_kernels   pkgs/main/win-64::nb_conda_kernels-2.5.2-py310haa95532_1
  nbconvert-core     pkgs/main/win-64::nbconvert-core-7.16.6-py310haa95532_0
  nbconvert-pandoc   pkgs/main/win-64::nbconvert-pandoc-7.16.6-py310haa95532_0
  nlohmann_json      pkgs/main/win-64::nlohmann_json-3.11.2-h6c2663c_0
  numpy-base         pkgs/main/win-64::numpy-base-1.26.4-py310h65a83cf_0
  pandas             pkgs/main/win-64::pandas-2.2.3-py310h5da7b33_0
  pandoc             pkgs/main/win-64::pandoc-2.12-haa95532_3
  pep8               pkgs/main/win-64::pep8-1.7.1-py310haa95532_1
  pip                pkgs/main/win-64::pip-25.0-py310haa95532_0
  propcache          pkgs/main/win-64::propcache-0.3.1-py310h827c3e9_0
  psutil             pkgs/main/win-64::psutil-5.9.0-py310h827c3e9_1
  pyarrow            pkgs/main/win-64::pyarrow-16.1.0-py310hc64d2fc_0
  pydantic-settings  pkgs/main/win-64::pydantic-settings-2.6.1-py310haa95532_0
  pygithub           pkgs/main/win-64::pygithub-2.4.0-py310haa95532_0
  python-xxhash      pkgs/main/win-64::python-xxhash-3.5.0-py310h827c3e9_0
  pyuca              pkgs/main/win-64::pyuca-1.2-py310haa95532_1
  readchar           pkgs/main/win-64::readchar-4.0.5-py310haa95532_0
  safetensors        pkgs/main/win-64::safetensors-0.5.3-py310haa69e8e_0
  scikit-learn-inte~ pkgs/main/win-64::scikit-learn-intelex-2023.1.1-py310haa95532_0
  scipy              pkgs/main/win-64::scipy-1.13.1-py310h8640f81_1
  sentry-sdk         pkgs/main/win-64::sentry-sdk-2.18.0-py310haa95532_0
  setuptools         pkgs/main/win-64::setuptools-75.8.0-py310haa95532_0
  shellingham        pkgs/main/win-64::shellingham-1.5.0-py310haa95532_0
  simdjson           pkgs/main/win-64::simdjson-3.10.1-h214f63a_0
  six                pkgs/main/win-64::six-1.17.0-py310haa95532_0
  sklearn-compat     pkgs/main/win-64::sklearn-compat-0.1.3-py310haa95532_0
  spdlog             pkgs/main/win-64::spdlog-1.11.0-h59b6b97_0
  superqt            pkgs/main/win-64::superqt-0.7.3-py310hbc747e5_0
  sympy              pkgs/main/win-64::sympy-1.13.3-py310haa95532_1
  tbb4py             pkgs/main/win-64::tbb4py-2021.8.0-py310h59b6b97_0
  tokenizers         pkgs/main/win-64::tokenizers-0.21.0-py310h5bc5163_0
  transformers       pkgs/main/win-64::transformers-4.49.0-py310haa95532_0
  typer              pkgs/main/win-64::typer-0.9.0-py310haa95532_0
  typing_extensions  pkgs/main/win-64::typing_extensions-4.12.2-py310haa95532_0
  xxhash             pkgs/main/win-64::xxhash-0.8.0-h2bbff1b_3

The following packages will be REMOVED:

  aiobotocore-2.12.3-py312haa95532_0
  aioitertools-0.7.1-pyhd3eb1b0_0
  botocore-1.34.69-py312haa95532_0
  s3fs-2024.6.1-py312haa95532_0

The following packages will be UPDATED:

  aext-assistant                 4.0.15-py312haa95532_jl4_0 --> 4.1.0-py310haa95532_jl4_0
  aext-assistant-se~                 4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aext-core                      4.0.15-py312haa95532_jl4_0 --> 4.1.0-py310haa95532_jl4_0
  aext-core-server                   4.0.15-py312haa95532_1 --> 4.1.0-py310haa95532_0
  aext-panels                        4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aext-panels-server                 4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aext-share-notebo~                 4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aext-share-notebo~                 4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aext-shared                        4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  aiohappyeyeballs                    2.4.0-py312haa95532_0 --> 2.4.4-py310haa95532_0
  aiohttp                            3.10.5-py312h827c3e9_0 --> 3.11.10-py310h827c3e9_0
  altair                              5.0.1-py312haa95532_0 --> 5.5.0-py310haa95532_0
  anaconda-anon-usa~                0.4.4-py312hfc23b7f_100 --> 0.7.0-py310hfc23b7f_101
  anaconda-client                    1.12.3-py312haa95532_0 --> 1.13.0-py310haa95532_1
  anaconda-cloud-au~                  0.5.1-py312haa95532_0 --> 0.8.4-py310haa95532_0
  anaconda-navigator                  2.6.3-py312haa95532_0 --> 2.6.5-py310haa95532_0
  anaconda-toolbox                   4.0.15-py312haa95532_0 --> 4.1.0-py310haa95532_0
  anyio                               4.2.0-py312haa95532_0 --> 4.6.2-py310haa95532_0
  argon2-cffi-bindi~                 21.2.0-py312h2bbff1b_0 --> 21.2.0-py310h827c3e9_1
  arrow                               1.2.3-py312haa95532_1 --> 1.3.0-py310haa95532_0
  astroid                            2.14.2-py312haa95532_0 --> 3.3.8-py310haa95532_0
  astropy-iers-data      0.2024.9.2.0.33.23-py312haa95532_0 --> 0.2025.1.13.0.34.51-py310haa95532_0
  attrs                              23.1.0-py312haa95532_0 --> 24.3.0-py310haa95532_0
  babel                              2.11.0-py312haa95532_0 --> 2.16.0-py310haa95532_0
  bcrypt                              3.2.0-py312h2bbff1b_1 --> 3.2.0-py310h827c3e9_2
  black                              24.8.0-py312haa95532_0 --> 24.10.0-py310haa95532_0
  blinker                             1.6.2-py312haa95532_0 --> 1.9.0-py310haa95532_0
  bokeh                               3.6.0-py312haa95532_0 --> 3.6.2-py310haa95532_0
  boltons                            23.0.0-py312haa95532_0 --> 24.1.0-py310haa95532_0
  bottleneck                          1.3.7-py312he558020_0 --> 1.4.2-py310hc99e966_0
  brotli-python                       1.0.9-py312hd77b12b_8 --> 1.0.9-py310h5da7b33_9
  cachetools                          5.3.3-py312haa95532_0 --> 5.5.1-py310haa95532_0
  certifi                         2024.8.30-py312haa95532_0 --> 2025.1.31-py310haa95532_0
  cffi                               1.17.1-py312h827c3e9_0 --> 1.17.1-py310h827c3e9_1
  click                               8.1.7-py312haa95532_0 --> 8.1.8-py310haa95532_0
  conda                              24.9.2-py312haa95532_0 --> 25.3.1-py310haa95532_0
  conda-build                        24.9.0-py312haa95532_0 --> 25.3.2-py310haa95532_0
  conda-libmamba-so~                    24.9.0-pyhd3eb1b0_0 --> 25.3.0-pyhd3eb1b0_0
  conda-package-han~                  2.3.0-py312haa95532_0 --> 2.4.0-py310haa95532_0
  conda-package-str~                 0.10.0-py312haa95532_0 --> 0.11.0-py310haa95532_0
  conda-repo-cli                    1.0.114-py312haa95532_0 --> 1.0.165-py310haa95532_0
  conda-token                            0.5.0-pyhd3eb1b0_0 --> 0.6.0-pyhd3eb1b0_0
  contourpy                           1.2.0-py312h59b6b97_0 --> 1.3.1-py310h214f63a_0
  cryptography                       43.0.0-py312h89fc84f_0 --> 44.0.1-py310hbd6ee87_0
  cytoolz                            0.12.2-py312h2bbff1b_0 --> 1.0.1-py310h827c3e9_0
  dask                             2024.8.2-py312haa95532_0 --> 2025.2.0-py310haa95532_0
  dask-core                        2024.8.2-py312haa95532_0 --> 2025.2.0-py310haa95532_0
  dask-expr                          1.1.13-py312haa95532_0 --> 2.0.0-py310haa95532_0
  datashader                         0.16.3-py312haa95532_0 --> 0.18.0-py310haa95532_0
  debugpy                             1.6.7-py312hd77b12b_0 --> 1.8.11-py310h5da7b33_0
  distributed                      2024.8.2-py312haa95532_0 --> 2025.2.0-py310haa95532_0
  docutils                           0.18.1-py312haa95532_3 --> 0.21.2-py310haa95532_0
  filelock                           3.13.1-py312haa95532_0 --> 3.17.0-py310haa95532_0
  flake8                              7.0.0-py312haa95532_0 --> 7.1.1-py310haa95532_0
  flask                               3.0.3-py312haa95532_0 --> 3.1.0-py310haa95532_0
  fonttools                          4.51.0-py312h2bbff1b_0 --> 4.55.3-py310h827c3e9_0
  frozenlist                          1.4.0-py312h2bbff1b_0 --> 1.5.0-py310h827c3e9_0
  fsspec                           2024.6.1-py312haa95532_0 --> 2024.12.0-py310haa95532_0
  giflib                                   5.2.1-h8cc25b3_3 --> 5.2.2-h7edc060_0
  h5py                               3.11.0-py312h59a1360_0 --> 3.12.1-py310h535c9fb_1
  hdf5                                    1.12.1-h51c971a_3 --> 1.14.5-ha36df97_2
  holoviews                          1.19.1-py312haa95532_0 --> 1.20.2-py310haa95532_0
  hvplot                             0.11.0-py312haa95532_0 --> 0.11.2-py310haa95532_0
  imagecodecs                     2023.1.23-py312hd5bf116_1 --> 2024.9.22-py310hacb3832_0
  imageio                            2.33.1-py312haa95532_0 --> 2.37.0-py310haa95532_0
  imbalanced-learn                   0.12.3-py312haa95532_1 --> 0.13.0-py310haa95532_0
  importlib-metadata                  7.0.1-py312haa95532_0 --> 8.5.0-py310haa95532_0
  ipykernel                          6.28.0-py312haa95532_0 --> 6.29.5-py310haa95532_1
  ipython                            8.27.0-py312haa95532_0 --> 8.30.0-py310haa95532_0
  ipywidgets                          7.8.1-py312haa95532_0 --> 7.8.5-py310haa95532_0
  isort                              5.13.2-py312haa95532_0 --> 6.0.1-py310haa95532_0
  itemloaders                         1.1.0-py312haa95532_0 --> 1.3.2-py310haa95532_0
  jedi                               0.19.1-py312haa95532_0 --> 0.19.2-py310haa95532_0
  jellyfish                           1.0.1-py312h36a85e1_0 --> 1.1.3-py310h8ecf97c_0
  jinja2                              3.1.4-py312haa95532_0 --> 3.1.6-py310haa95532_0
  jupyter                             1.0.0-py312haa95532_9 --> 1.1.1-py310haa95532_0
  jupyter_client                      8.6.0-py312haa95532_0 --> 8.6.3-py310haa95532_0
  jupyter_events                     0.10.0-py312haa95532_0 --> 0.12.0-py310haa95532_0
  jupyter_server                     2.14.1-py312haa95532_0 --> 2.15.0-py310haa95532_0
  jupyter_server_te~                  0.4.4-py312haa95532_1 --> 0.5.3-py310haa95532_0
  jupyterlab                          4.2.5-py312haa95532_0 --> 4.3.4-py310haa95532_0
  jupyterlab-variab~                  3.1.0-py312haa95532_0 --> 3.2.4-py310haa95532_0
  kiwisolver                          1.4.4-py312hd77b12b_0 --> 1.4.8-py310h5da7b33_0
  lazy-object-proxy                  1.10.0-py312h2bbff1b_0 --> 1.10.0-py310h827c3e9_1
  lcms2                                     2.12-h83e58a3_0 --> 2.16-hb4a4139_0
  lerc                                       3.0-hd77b12b_0 --> 4.0.0-h5da7b33_0
  libaec                                   1.0.4-h33f27b4_1 --> 1.1.3-hcdb6601_0
  libarchive                               3.7.4-h9243413_0 --> 3.7.7-h9243413_0
  libavif                                 0.11.1-h2bbff1b_0 --> 1.1.1-h827c3e9_0
  libdeflate                                1.17-h2bbff1b_1 --> 1.22-h5bf469e_0
  libmamba                                 1.5.8-h99b1521_3 --> 2.0.5-hcd6fe79_1
  libmambapy                          1.5.8-py312h77c03ed_3 --> 2.0.5-py310h214f63a_1
  libsolv                                 0.7.24-h23ce68f_1 --> 0.7.30-hf2fb9eb_1
  libtiff                                  4.5.1-hd77b12b_0 --> 4.5.1-h44ae7cf_1
  libxml2                                 2.13.1-h24da03e_2 --> 2.13.7-h866ff63_0
  llvmlite                           0.43.0-py312hf2fb9eb_0 --> 0.44.0-py310h8b1c7eb_1
  lxml                                5.2.1-py312h395c83e_1 --> 5.3.0-py310h395c83e_1
  lz4                                 4.3.2-py312h2bbff1b_0 --> 4.3.2-py310h827c3e9_1
  markupsafe                          2.1.3-py312h2bbff1b_0 --> 3.0.2-py310h827c3e9_0
  matplotlib                          3.9.2-py312haa95532_0 --> 3.10.0-py310haa95532_0
  matplotlib-base                     3.9.2-py312hbdc63d0_0 --> 3.10.0-py310he19b0ae_0
  menuinst                            2.1.2-py312h5da7b33_0 --> 2.2.0-py310h5da7b33_1
  mistune                             2.0.4-py312haa95532_0 --> 3.1.2-py310haa95532_0
  mkl-service                         2.4.0-py312h2bbff1b_1 --> 2.4.0-py310h827c3e9_2
  mkl_fft                            1.3.10-py312h827c3e9_0 --> 1.3.11-py310h827c3e9_0
  mkl_random                          1.2.7-py312h0158946_0 --> 1.2.8-py310hc64d2fc_0
  multidict                           6.0.4-py312h2bbff1b_0 --> 6.1.0-py310h827c3e9_0
  mypy                               1.11.2-py312h827c3e9_0 --> 1.14.1-py310h827c3e9_0
  nbclient                            0.8.0-py312haa95532_0 --> 0.10.2-py310haa95532_0
  nbconvert                          7.16.4-py312haa95532_0 --> 7.16.6-py310haa95532_0
  networkx                              3.3-py312haa95532_0 --> 3.4.2-py310haa95532_0
  notebook                            7.2.2-py312haa95532_1 --> 7.3.2-py310haa95532_0
  notebook-shim                       0.2.3-py312haa95532_0 --> 0.2.4-py310haa95532_0
  numba                              0.60.0-py312h0158946_0 --> 0.61.0-py310h5da7b33_1
  numexpr                             2.8.7-py312h96b7d27_0 --> 2.10.1-py310h4cd664f_0
  openpyxl                            3.1.5-py312h827c3e9_0 --> 3.1.5-py310h827c3e9_1
  packaging                            24.1-py312haa95532_0 --> 24.2-py310haa95532_0
  panel                               1.5.2-py312haa95532_0 --> 1.6.0-py310haa95532_0
  param                               2.1.1-py312haa95532_0 --> 2.2.0-py310haa95532_0
  parso              pkgs/main/noarch::parso-0.8.3-pyhd3eb~ --> pkgs/main/win-64::parso-0.8.4-py310haa95532_0
  partd                               1.4.1-py312haa95532_0 --> 1.4.2-py310haa95532_0
  patsy                               0.5.6-py312haa95532_0 --> 1.0.1-py310haa95532_0
  pillow                             10.4.0-py312h827c3e9_0 --> 11.1.0-py310h096bfcc_0
  pkginfo                            1.10.0-py312haa95532_0 --> 1.12.0-py310haa95532_0
  platformdirs                       3.10.0-py312haa95532_0 --> 4.3.7-py310haa95532_0
  plotly                             5.24.1-py312hfc267ef_0 --> 5.24.1-py310h9909e9c_1
  pluggy                              1.0.0-py312haa95532_1 --> 1.5.0-py310haa95532_0
  prometheus_client                  0.14.1-py312haa95532_0 --> 0.21.1-py310haa95532_0
  protobuf                           4.25.3-py312h958608f_0 --> 4.25.3-py310hf91db99_1
  pycodestyle                        2.11.1-py312haa95532_0 --> 2.12.1-py310haa95532_0
  pycosat                             0.6.6-py312h2bbff1b_1 --> 0.6.6-py310h827c3e9_2
  pycurl                             7.45.3-py312h3f729d1_0 --> 7.45.6-py310h51539b2_0
  pydantic                            2.8.2-py312haa95532_0 --> 2.10.3-py310haa95532_0
  pydantic-core                      2.20.1-py312hefb1915_0 --> 2.27.1-py310h636fa0f_0
  pydeck                              0.8.0-py312haa95532_2 --> 0.9.1-py310haa95532_0
  pyerfa                            2.0.1.4-py312h4b0e54e_0 --> 2.0.1.5-py310h827c3e9_0
  pygments                           2.15.1-py312haa95532_1 --> 2.19.1-py310haa95532_0
  pyjwt                               2.8.0-py312haa95532_0 --> 2.10.1-py310haa95532_0
  pylint                             2.16.2-py312haa95532_0 --> 3.3.5-py310haa95532_0
  pynacl                              1.5.0-py312h8cc25b3_0 --> 1.5.0-py310h7edc060_1
  pyodbc                              5.1.0-py312h5da7b33_0 --> 5.2.0-py310h5da7b33_0
  pyopenssl                          24.2.1-py312haa95532_0 --> 25.0.0-py310hb6ff9d5_0
  pyparsing                           3.1.2-py312haa95532_0 --> 3.2.0-py310haa95532_0
  pyqt                              5.15.10-py312hd77b12b_0 --> 5.15.10-py310h5da7b33_1
  pyqt5-sip                         12.13.0-py312h2bbff1b_0 --> 12.13.0-py310h827c3e9_1
  pyqtwebengine                     5.15.10-py312hd77b12b_0 --> 5.15.10-py310h5da7b33_1
  pytables                           3.10.1-py312ha32dda5_0 --> 3.10.1-py310he42c613_1
  pytest                              7.4.4-py312haa95532_0 --> 8.3.4-py310haa95532_0
  python-fastjsonsc~                 2.16.2-py312haa95532_0 --> 2.20.0-py310haa95532_0
  python-json-logger                  2.0.7-py312haa95532_0 --> 3.2.1-py310haa95532_0
  python-lmdb                         1.4.1-py312hd77b12b_0 --> 1.6.2-py310h5da7b33_0
  python-lsp-black                    2.0.0-py312haa95532_0 --> 2.0.0-py310haa95532_1
  python-lsp-server                  1.10.0-py312haa95532_0 --> 1.12.2-py310hbc747e5_0
  pywavelets                          1.7.0-py312h827c3e9_0 --> 1.8.0-py310h827c3e9_0
  pywin32                               305-py312h2bbff1b_0 --> 308-py310h5da7b33_0
  pywinpty                           2.0.10-py312h5da7b33_0 --> 2.0.15-py310h72d21ff_0
  pyyaml                              6.0.1-py312h2bbff1b_0 --> 6.0.2-py310h827c3e9_0
  pyzmq                              25.1.2-py312hd77b12b_0 --> 26.2.0-py310h5da7b33_0
  qtawesome                           1.3.1-py312haa95532_0 --> 1.4.0-py310haa95532_0
  qtconsole                           5.5.1-py312haa95532_0 --> 5.6.1-py310haa95532_1
  regex                           2024.9.11-py312h827c3e9_0 --> 2024.11.6-py310h827c3e9_0
  requests                           2.32.3-py312haa95532_0 --> 2.32.3-py310haa95532_1
  rich                               13.7.1-py312haa95532_0 --> 13.9.4-py310haa95532_0
  rope                               1.12.0-py312haa95532_0 --> 1.13.0-py310haa95532_0
  rpds-py                            0.10.6-py312h062c2fa_0 --> 0.22.3-py310h636fa0f_0
  scikit-image                       0.24.0-py312h0158946_0 --> 0.25.0-py310h5da7b33_0
  scikit-learn                        1.5.1-py312h0158946_0 --> 1.6.1-py310h585ebfc_0
  scrapy                             2.11.1-py312haa95532_0 --> 2.12.0-py310haa95532_1
  seaborn                            0.13.2-py312haa95532_0 --> 0.13.2-py310haa95532_2
  semver                              3.0.2-py312haa95532_0 --> 3.0.2-py310haa95532_1
  send2trash                          1.8.2-py312haa95532_0 --> 1.8.2-py310haa95532_1
  sip                                6.7.12-py312hd77b12b_0 --> 6.7.12-py310h5da7b33_1
  sphinxcontrib-ser~ pkgs/main/win-64::sphinxcontrib-seria~ --> pkgs/main/noarch::sphinxcontrib-serializinghtml-2.0.0-pyhd3eb1b0_0
  spyder                              5.5.1-py312haa95532_4 --> 6.0.5-py310haa95532_0
  spyder-kernels                      2.5.0-py312haa95532_0 --> 3.0.3-py310hbc747e5_0
  sqlalchemy                         2.0.34-py312h54f65d0_0 --> 2.0.37-py310h54f65d0_0
  statsmodels                        0.14.2-py312h4b0e54e_0 --> 0.14.4-py310h827c3e9_0
  streamlit                          1.37.1-py312haa95532_0 --> 1.44.1-py310haa95532_0
  tenacity                            8.2.3-py312haa95532_0 --> 9.0.0-py310haa95532_0
  tifffile                        2023.4.12-py312haa95532_0 --> 2024.12.12-py310haa95532_0
  tinycss2                            1.2.1-py312haa95532_0 --> 1.4.0-py310haa95532_0
  tomlkit                            0.11.1-py312haa95532_0 --> 0.13.2-py310haa95532_0
  toolz                              0.12.0-py312haa95532_0 --> 1.0.0-py310haa95532_0
  tornado                             6.4.1-py312h827c3e9_0 --> 6.4.2-py310h827c3e9_0
  tqdm                               4.66.5-py312hfc267ef_0 --> 4.67.1-py310h9909e9c_0
  truststore                          0.8.0-py312haa95532_0 --> 0.10.0-py310haa95532_0
  twisted-iocpsuppo~                  1.0.2-py312h2bbff1b_0 --> 1.0.2-py310h827c3e9_1
  typing-extensions                  4.11.0-py312haa95532_0 --> 4.12.2-py310haa95532_0
  ujson                              5.10.0-py312h5da7b33_0 --> 5.10.0-py310h5da7b33_1
  unicodedata2                       15.1.0-py312h2bbff1b_0 --> 15.1.0-py310h827c3e9_1
  urllib3                             2.2.3-py312haa95532_0 --> 2.3.0-py310haa95532_0
  vs2015_runtime                     14.40.33807-h98bb1dd_1 --> 14.42.34433-hbfb602d_5
  watchdog                            4.0.1-py312haa95532_0 --> 4.0.2-py310haa95532_0
  werkzeug                            3.0.3-py312haa95532_0 --> 3.1.3-py310haa95532_0
  wheel                              0.44.0-py312haa95532_0 --> 0.45.1-py310haa95532_0
  widgetsnbextension                  3.6.6-py312haa95532_0 --> 3.6.10-py310haa95532_0
  wrapt                              1.14.1-py312h2bbff1b_0 --> 1.17.0-py310h827c3e9_0
  xarray                           2023.6.0-py312haa95532_0 --> 2024.11.0-py310haa95532_0
  xlwings                            0.32.1-py312haa95532_0 --> 0.32.1-py310haa95532_1
  yarl                               1.11.0-py312h827c3e9_0 --> 1.18.0-py310h827c3e9_0
  zipp                               3.17.0-py312haa95532_0 --> 3.21.0-py310haa95532_0
  zope.interface                      5.4.0-py312h2bbff1b_0 --> 7.1.1-py310h827c3e9_0
  zstandard                          0.23.0-py312h4fc1ca9_0 --> 0.23.0-py310h4fc1ca9_1

The following packages will be DOWNGRADED:

  _anaconda_depends                     2024.10-py312_mkl_0 --> 2023.03-py310_0
  alabaster                          0.7.16-py312haa95532_0 --> 0.7.16-py310haa95532_0
  anaconda-catalogs                   0.2.0-py312haa95532_1 --> 0.2.0-py310haa95532_0
  anaconda-project                   0.11.1-py312haa95532_0 --> 0.11.1-py310haa95532_0
  annotated-types                     0.6.0-py312haa95532_0 --> 0.6.0-py310haa95532_0
  astropy                             6.1.3-py312h827c3e9_0 --> 6.1.3-py310h827c3e9_0
  async-lru                           2.0.4-py312haa95532_0 --> 2.0.4-py310haa95532_0
  beautifulsoup4                     4.12.3-py312haa95532_0 --> 4.12.3-py310haa95532_0
  chardet                          4.0.0-py312haa95532_1003 --> 4.0.0-py310haa95532_1003
  cloudpickle                         3.0.0-py312haa95532_0 --> 3.0.0-py310haa95532_0
  colorama                            0.4.6-py312haa95532_0 --> 0.4.6-py310haa95532_0
  colorcet                            3.1.0-py312haa95532_0 --> 3.1.0-py310haa95532_0
  comm                                0.2.1-py312haa95532_0 --> 0.2.1-py310haa95532_0
  conda-content-tru~                  0.2.0-py312haa95532_1 --> 0.2.0-py310haa95532_1
  conda-index                         0.5.0-py312haa95532_0 --> 0.5.0-py310haa95532_0
  conda-pack                          0.7.1-py312haa95532_0 --> 0.7.1-py310haa95532_0
  constantly                        23.10.4-py312haa95532_0 --> 23.10.4-py310haa95532_0
  cookiecutter                        2.6.0-py312haa95532_0 --> 2.6.0-py310haa95532_0
  cssselect                           1.2.0-py312haa95532_0 --> 1.2.0-py310haa95532_0
  distro                              1.9.0-py312haa95532_0 --> 1.9.0-py310haa95532_0
  docstring-to-mark~                   0.11-py312haa95532_0 --> 0.11-py310haa95532_0
  et_xmlfile                          1.1.0-py312haa95532_1 --> 1.1.0-py310haa95532_0
  frozendict                          2.4.2-py312haa95532_0 --> 2.4.2-py310h2bbff1b_0
  gensim                              4.3.3-py312h0158946_0 --> 4.3.3-py310hc64d2fc_0
  gitpython                          3.1.43-py312haa95532_0 --> 3.1.43-py310haa95532_0
  h11                                0.14.0-py312haa95532_0 --> 0.14.0-py310haa95532_0
  httpcore                            1.0.2-py312haa95532_0 --> 1.0.2-py310haa95532_0
  httpx                              0.27.0-py312haa95532_0 --> 0.27.0-py310haa95532_0
  idna                                  3.7-py312haa95532_0 --> 3.7-py310haa95532_0
  imagesize                           1.4.1-py312haa95532_0 --> 1.4.1-py310haa95532_0
  inflection                          0.5.1-py312haa95532_1 --> 0.5.1-py310haa95532_0
  intake                              2.0.7-py312haa95532_0 --> 2.0.7-py310haa95532_0
  itsdangerous                        2.2.0-py312haa95532_0 --> 2.2.0-py310haa95532_0
  jmespath                            1.0.1-py312haa95532_0 --> 1.0.1-py310haa95532_0
  joblib                              1.4.2-py312haa95532_0 --> 1.4.2-py310haa95532_0
  jsonpatch                            1.33-py312haa95532_1 --> 1.33-py310haa95532_1
  jsonschema                         4.23.0-py312haa95532_0 --> 4.23.0-py310haa95532_0
  jsonschema-specif~               2023.7.1-py312haa95532_0 --> 2023.7.1-py310haa95532_0
  jupyter-lsp                         2.2.0-py312haa95532_0 --> 2.2.0-py310haa95532_0
  jupyter_console                     6.6.3-py312haa95532_1 --> 6.6.3-py310haa95532_0
  jupyter_core                        5.7.2-py312haa95532_0 --> 5.7.2-py310haa95532_0
  jupyterlab_server                  2.27.3-py312haa95532_0 --> 2.27.3-py310haa95532_0
  keyring                            24.3.1-py312haa95532_0 --> 24.3.1-py310haa95532_0
  lazy_loader                           0.4-py312haa95532_0 --> 0.4-py310haa95532_0
  linkify-it-py                       2.0.0-py312haa95532_0 --> 2.0.0-py310haa95532_0
  locket                              1.0.0-py312haa95532_0 --> 1.0.0-py310haa95532_0
  markdown                            3.4.1-py312haa95532_0 --> 3.4.1-py310haa95532_0
  markdown-it-py                      2.2.0-py312haa95532_1 --> 2.2.0-py310haa95532_1
  matplotlib-inline                   0.1.6-py312haa95532_0 --> 0.1.6-py310haa95532_0
  mdit-py-plugins                     0.3.0-py312haa95532_0 --> 0.3.0-py310haa95532_0
  mdurl                               0.1.0-py312haa95532_0 --> 0.1.0-py310haa95532_0
  more-itertools                     10.3.0-py312haa95532_0 --> 10.3.0-py310haa95532_0
  mpmath                              1.3.0-py312haa95532_0 --> 1.3.0-py310haa95532_0
  msgpack-python                      1.0.3-py312h59b6b97_0 --> 1.0.3-py310h59b6b97_0
  multipledispatch                    0.6.0-py312haa95532_0 --> 0.6.0-py310haa95532_0
  mypy_extensions                     1.0.0-py312haa95532_0 --> 1.0.0-py310haa95532_0
  navigator-updater                   0.5.1-py312haa95532_0 --> 0.5.1-py310haa95532_0
  nbformat                           5.10.4-py312haa95532_0 --> 5.10.4-py310haa95532_0
  nest-asyncio                        1.6.0-py312haa95532_0 --> 1.6.0-py310haa95532_0
  nltk                                3.9.1-py312haa95532_0 --> 3.9.1-py310haa95532_0
  numpy                              1.26.4-py312hfd52020_0 --> 1.26.4-py310h055cbcc_0
  numpydoc                            1.7.0-py312haa95532_0 --> 1.7.0-py310haa95532_0
  overrides                           7.4.0-py312haa95532_0 --> 7.4.0-py310haa95532_0
  parsel                              1.8.1-py312haa95532_0 --> 1.8.1-py310haa95532_0
  pathspec                           0.10.3-py312haa95532_0 --> 0.10.3-py310haa95532_0
  pkce                                1.0.3-py312haa95532_0 --> 1.0.3-py310haa95532_0
  ply                                  3.11-py312haa95532_1 --> 3.11-py310haa95532_0
  prompt-toolkit                     3.0.43-py312haa95532_0 --> 3.0.43-py310haa95532_0
  py-cpuinfo                          9.0.0-py312haa95532_0 --> 9.0.0-py310haa95532_0
  py-lief                            0.12.3-py312hd77b12b_0 --> 0.12.3-py310hd77b12b_0
  pyct                                0.5.0-py312haa95532_0 --> 0.5.0-py310haa95532_0
  pydispatcher                        2.0.5-py312haa95532_3 --> 2.0.5-py310haa95532_2
  pydocstyle                          6.3.0-py312haa95532_0 --> 6.3.0-py310haa95532_0
  pyflakes                            3.2.0-py312haa95532_0 --> 3.2.0-py310haa95532_0
  pylint-venv                         3.0.3-py312haa95532_0 --> 3.0.3-py310haa95532_0
  pysocks                             1.7.1-py312haa95532_0 --> 1.7.1-py310haa95532_0
  python                                  3.12.7-h14ffc60_0 --> 3.10.16-h4607a30_1
  python-dateutil                2.9.0post0-py312haa95532_2 --> 2.9.0post0-py310haa95532_2
  python-dotenv                      0.21.0-py312haa95532_0 --> 0.21.0-py310haa95532_0
  pytoolconfig                        1.2.6-py312haa95532_0 --> 1.2.6-py310haa95532_0
  pytz                               2024.1-py312haa95532_0 --> 2024.1-py310haa95532_0
  pyviz_comms                         3.0.2-py312haa95532_0 --> 3.0.2-py310haa95532_0
  pywin32-ctypes                      0.2.2-py312haa95532_0 --> 0.2.2-py310haa95532_0
  qstylizer                           0.2.2-py312haa95532_0 --> 0.2.2-py310haa95532_0
  qtpy                                2.4.1-py312haa95532_0 --> 2.4.1-py310haa95532_0
  queuelib                            1.6.2-py312haa95532_0 --> 1.6.2-py310haa95532_0
  referencing                        0.30.2-py312haa95532_0 --> 0.30.2-py310haa95532_0
  requests-toolbelt                   1.0.0-py312haa95532_0 --> 1.0.0-py310haa95532_0
  rfc3339-validator                   0.1.4-py312haa95532_0 --> 0.1.4-py310haa95532_0
  rfc3986-validator                   0.1.1-py312haa95532_0 --> 0.1.1-py310haa95532_0
  rtree                               1.0.1-py312h2eaa2aa_0 --> 1.0.1-py310h2eaa2aa_0
  ruamel.yaml                        0.18.6-py312h827c3e9_0 --> 0.18.6-py310h827c3e9_0
  ruamel.yaml.clib                    0.2.8-py312h827c3e9_0 --> 0.2.8-py310h827c3e9_0
  ruamel_yaml                       0.17.21-py312h2bbff1b_0 --> 0.17.21-py310h2bbff1b_0
  smart_open                          5.2.1-py312haa95532_0 --> 5.2.1-py310haa95532_0
  sniffio                             1.3.0-py312haa95532_0 --> 1.3.0-py310haa95532_0
  soupsieve                             2.5-py312haa95532_0 --> 2.5-py310haa95532_0
  sphinx                              7.3.7-py312h827c3e9_0 --> 7.3.7-py310h827c3e9_0
  tabulate                            0.9.0-py312haa95532_0 --> 0.9.0-py310haa95532_0
  terminado                          0.17.1-py312haa95532_0 --> 0.17.1-py310haa95532_0
  threadpoolctl                       3.5.0-py312hfc267ef_0 --> 3.5.0-py310h9909e9c_0
  tldextract                          5.1.2-py312haa95532_0 --> 5.1.2-py310haa95532_0
  tomli                               2.0.1-py312haa95532_1 --> 2.0.1-py310haa95532_0
  traitlets                          5.14.3-py312haa95532_0 --> 5.14.3-py310haa95532_0
  twisted                           23.10.0-py312haa95532_0 --> 23.10.0-py310haa95532_0
  uc-micro-py                         1.0.1-py312haa95532_0 --> 1.0.1-py310haa95532_0
  unidecode                           1.3.8-py312haa95532_0 --> 1.3.8-py310haa95532_0
  w3lib                               2.1.2-py312haa95532_0 --> 2.1.2-py310haa95532_0
  webencodings                        0.5.1-py312haa95532_2 --> 0.5.1-py310haa95532_1
  websocket-client                    1.8.0-py312haa95532_0 --> 1.8.0-py310haa95532_0
  whatthepatch                        1.0.2-py312haa95532_0 --> 1.0.2-py310haa95532_0
  win_inet_pton                       1.1.0-py312haa95532_0 --> 1.1.0-py310haa95532_0
  xyzservices                      2022.9.0-py312haa95532_1 --> 2022.9.0-py310haa95532_1
  yapf                               0.40.2-py312haa95532_0 --> 0.40.2-py310haa95532_0
  zict                                3.0.0-py312haa95532_0 --> 3.0.0-py310haa95532_0
  zope                                  1.0-py312haa95532_1 --> 1.0-py310haa95532_1



Downloading and Extracting Packages:
gensim-4.3.3         | 42.1 MB   | ############################################################################ | 100%
dal-2023.1.1         | 26.5 MB   | ############################################################################ | 100%
scipy-1.13.1         | 23.0 MB   | ############################################################################ | 100%
transformers-4.49.0  | 21.7 MB   | ############################################################################ | 100%
panel-1.6.0          | 21.1 MB   | ############################################################################ | 100%
llvmlite-0.44.0      | 19.6 MB   | ############################################################################ | 100%
datashader-0.18.0    | 17.0 MB   | ############################################################################ | 100%
python-3.10.16       | 16.3 MB   | ############################################################################ | 100%
pandoc-2.12          | 14.6 MB   | ############################################################################ | 100%
pandas-2.2.3         | 12.0 MB   | ############################################################################ | 100%
astropy-6.1.3        | 11.8 MB   | ############################################################################ | 100%
sympy-1.13.3         | 11.3 MB   | #######################################################################3     |  94%
scikit-image-0.25.0  | 10.7 MB   | ############################################################################ | 100%
pywin32-308          | 10.5 MB   | ############################################################################ | 100%
statsmodels-0.14.4   | 10.4 MB   | ############################################################################ | 100%
notebook-7.3.2       | 10.3 MB   | ############################################################################ | 100%
imagecodecs-2024.9.2 | 10.1 MB   | ###########################################################################7 | 100%
plotly-5.24.1        | 10.0 MB   | ####################################################################         |  90%
spyder-6.0.5         | 9.9 MB    | ######################################################################       |  92%
daal4py-2023.1.1     | 9.7 MB    | ############################################################################ | 100%
matplotlib-base-3.10 | 9.5 MB    | ######################################################################8      |  93%
numpy-base-1.26.4    | 8.6 MB    | #########################################################################2   |  96%
streamlit-1.44.1     | 8.6 MB    | ###########################################################################  |  99%
scikit-learn-1.6.1   | 8.4 MB    | ########################################################################2    |  95%
mypy-1.14.1          | 8.4 MB    | ###########################################################################6 | 100%
babel-2.16.0         | 6.8 MB    | #######################################################################6     |  94%
sqlalchemy-2.0.37    | 5.9 MB    | ################################################################1            |  84%
bokeh-3.6.2          | 5.5 MB    | ########################################################################4    |  95%
 ... (more hidden) ...






Preparing transaction: done
Verifying transaction: done
Executing transaction: \ Enabling nb_conda_kernels...
CONDA_PREFIX: C:\Users\test\anaconda3
Status: enabled

| menuinst Exception
Traceback (most recent call last):
  File "C:\Users\test\anaconda3\Lib\site-packages\conda\gateways\disk\create.py", line 261, in make_menu
    menuinst.install(
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 170, in _install_adapter
    install(metadata, target_prefix=prefix, **kwargs)
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\utils.py", line 426, in wrapper_elevate
    return func(
           ^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 62, in install
    paths += menu_item.create()
             ^^^^^^^^^^^^^^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\platforms\win.py", line 159, in create
    from .win_utils.winshortcut import create_shortcut
ModuleNotFoundError: No module named 'menuinst.platforms.win_utils.winshortcut'menuinst Exception
Traceback (most recent call last):
  File "C:\Users\test\anaconda3\Lib\site-packages\conda\gateways\disk\create.py", line 261, in make_menu
    menuinst.install(
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 170, in _install_adapter
    install(metadata, target_prefix=prefix, **kwargs)
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\utils.py", line 426, in wrapper_elevate
    return func(
           ^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 62, in install
    paths += menu_item.create()
             ^^^^^^^^^^^^^^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\platforms\win.py", line 159, in create
    from .win_utils.winshortcut import create_shortcut
ModuleNotFoundError: No module named 'menuinst.platforms.win_utils.winshortcu/ menuinst Exception
Traceback (most recent call last):
  File "C:\Users\test\anaconda3\Lib\site-packages\conda\gateways\disk\create.py", line 261, in make_menu
    menuinst.install(
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 170, in _install_adapter
    install(metadata, target_prefix=prefix, **kwargs)
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\utils.py", line 426, in wrapper_elevate
    return func(
           ^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\api.py", line 62, in install
    paths += menu_item.create()
             ^^^^^^^^^^^^^^^^^^
  File "C:\Users\test\anaconda3\Lib\site-packages\menuinst\platforms\win.py", line 159, in create
    from .win_utils.winshortcut import create_shortcut
ModuleNotFoundError: No module named 'menuinst.platforms.win_utils.winshortcudone

PackagesNotFoundError: The following packages are missing from the target environment:
  - aiofiles



PackagesNotFoundError: The following packages are missing from the target environment:
  - aiogram


Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aiohappyeyeballs


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    aiohttp-3.9.5              |  py310h2bbff1b_0         685 KB
    async-timeout-4.0.3        |  py310haa95532_0          13 KB
    ------------------------------------------------------------
                                           Total:         698 KB

The following packages will be REMOVED:

  aiohappyeyeballs-2.4.4-py310haa95532_0

The following packages will be DOWNGRADED:

  aiohttp                           3.11.10-py310h827c3e9_0 --> 3.9.5-py310h2bbff1b_0
  async-timeout                       5.0.1-py310haa95532_0 --> 4.0.3-py310haa95532_0



Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - aiohttp


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    autopep8-1.6.0             |     pyhd3eb1b0_1          43 KB
    backcall-0.2.0             |     pyhd3eb1b0_0          13 KB
    boto3-1.37.10              |  py310haa95532_0         187 KB
    botocore-1.37.10           |  py310haa95532_0         8.6 MB
    flake8-4.0.1               |     pyhd3eb1b0_1         118 KB
    ipython-7.31.1             |  py310haa95532_1         1.0 MB
    jedi-0.18.1                |  py310haa95532_1         983 KB
    mccabe-0.6.1               |  py310haa95532_2          15 KB
    pycodestyle-2.8.0          |     pyhd3eb1b0_0          41 KB
    pyflakes-2.4.0             |     pyhd3eb1b0_0          60 KB
    python-lsp-black-1.0.0     |     pyhd3eb1b0_0           8 KB
    python-lsp-server-1.3.3    |     pyhd3eb1b0_0          43 KB
    qdarkstyle-3.0.2           |     pyhd3eb1b0_0         337 KB
    qtconsole-5.2.2            |     pyhd3eb1b0_0          92 KB
    s3transfer-0.11.2          |  py310haa95532_0         181 KB
    sacremoses-0.0.43          |     pyhd3eb1b0_0         284 KB
    spyder-5.2.2               |  py310haa95532_1         9.4 MB
    spyder-kernels-2.2.1       |  py310haa95532_0         117 KB
    transformers-2.1.1         |     pyhd3eb1b0_0         136 KB
    ------------------------------------------------------------
                                           Total:        21.6 MB

The following NEW packages will be INSTALLED:

  backcall           pkgs/main/noarch::backcall-0.2.0-pyhd3eb1b0_0
  boto3              pkgs/main/win-64::boto3-1.37.10-py310haa95532_0
  botocore           pkgs/main/win-64::botocore-1.37.10-py310haa95532_0
  s3transfer         pkgs/main/win-64::s3transfer-0.11.2-py310haa95532_0
  sacremoses         pkgs/main/noarch::sacremoses-0.0.43-pyhd3eb1b0_0

The following packages will be REMOVED:

  aiohttp-3.9.5-py310h2bbff1b_0
  aiosignal-1.2.0-pyhd3eb1b0_0
  anaconda-catalogs-0.2.0-py310haa95532_0
  async-timeout-4.0.3-py310haa95532_0
  datasets-3.3.2-py310haa95532_0
  frozenlist-1.5.0-py310h827c3e9_0
  multiprocess-0.70.15-py310haa95532_0
  python-xxhash-3.5.0-py310h827c3e9_0
  xxhash-0.8.0-h2bbff1b_3

The following packages will be SUPERSEDED by a higher-priority channel:

  flake8             pkgs/main/win-64::flake8-7.1.1-py310h~ --> pkgs/main/noarch::flake8-4.0.1-pyhd3eb1b0_1
  mccabe             pkgs/main/noarch::mccabe-0.7.0-pyhd3e~ --> pkgs/main/win-64::mccabe-0.6.1-py310haa95532_2
  pycodestyle        pkgs/main/win-64::pycodestyle-2.12.1-~ --> pkgs/main/noarch::pycodestyle-2.8.0-pyhd3eb1b0_0
  pyflakes           pkgs/main/win-64::pyflakes-3.2.0-py31~ --> pkgs/main/noarch::pyflakes-2.4.0-pyhd3eb1b0_0
  python-lsp-black   pkgs/main/win-64::python-lsp-black-2.~ --> pkgs/main/noarch::python-lsp-black-1.0.0-pyhd3eb1b0_0
  python-lsp-server  pkgs/main/win-64::python-lsp-server-1~ --> pkgs/main/noarch::python-lsp-server-1.3.3-pyhd3eb1b0_0
  qtconsole          pkgs/main/win-64::qtconsole-5.6.1-py3~ --> pkgs/main/noarch::qtconsole-5.2.2-pyhd3eb1b0_0
  transformers       pkgs/main/win-64::transformers-4.49.0~ --> pkgs/main/noarch::transformers-2.1.1-pyhd3eb1b0_0

The following packages will be DOWNGRADED:

  autopep8                               2.0.4-pyhd3eb1b0_0 --> 1.6.0-pyhd3eb1b0_1
  ipython                            8.30.0-py310haa95532_0 --> 7.31.1-py310haa95532_1
  jedi                               0.19.2-py310haa95532_0 --> 0.18.1-py310haa95532_1
  qdarkstyle                             3.2.3-pyhd3eb1b0_0 --> 3.0.2-pyhd3eb1b0_0
  spyder                              6.0.5-py310haa95532_0 --> 5.2.2-py310haa95532_1
  spyder-kernels                      3.0.3-py310hbc747e5_0 --> 2.2.1-py310haa95532_0



Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: \ Insufficient permissions to write menu folder.  Falling back to user location

done

PackagesNotFoundError: The following packages are missing from the target environment:
  - aioitertools



PackagesNotFoundError: The following packages are missing from the target environment:
  - aiosignal


Channels:
 - defaults
Platform: win-64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: C:\Users\test\anaconda3

  removed specs:
    - alabaster


The following packages will be REMOVED:

  _anaconda_depends-2023.03-py310_0
  alabaster-0.7.16-py310haa95532_0
  appdirs-1.4.4-pyhd3eb1b0_0
  arrow-1.3.0-py310haa95532_0
  astroid-3.3.8-py310haa95532_0
  astropy-6.1.3-py310h827c3e9_0
  astropy-iers-data-0.2025.1.13.0.34.51-py310haa95532_0
  atomicwrites-1.4.0-py_0
  automat-20.2.0-py_0
  autopep8-1.6.0-pyhd3eb1b0_1
  bcrypt-3.2.0-py310h827c3e9_2
  binaryornot-0.4.4-pyhd3eb1b0_1
  black-24.10.0-py310haa95532_0
  boto3-1.37.10-py310haa95532_0
  botocore-1.37.10-py310haa95532_0
  c-blosc2-2.12.0-h2f4ed9d_0
  cloudpickle-3.0.0-py310haa95532_0
  colorcet-3.1.0-py310haa95532_0
  constantly-23.10.4-py310haa95532_0
  cookiecutter-2.6.0-py310haa95532_0
  cssselect-1.2.0-py310haa95532_0
  curl-8.9.1-h3f729d1_0
  cycler-0.11.0-pyhd3eb1b0_0
  cytoolz-1.0.1-py310h827c3e9_0
  daal4py-2023.1.1-py310hf497b98_0
  dal-2023.1.1-h59b6b97_48682
  dask-2025.2.0-py310haa95532_0
  dask-core-2025.2.0-py310haa95532_0
  dask-expr-2.0.0-py310haa95532_0
  datashader-0.18.0-py310haa95532_0
  diff-match-patch-20200713-pyhd3eb1b0_0
  dill-0.3.8-py310haa95532_0
  distributed-2025.2.0-py310haa95532_0
  docutils-0.21.2-py310haa95532_0
  et_xmlfile-1.1.0-py310haa95532_0
  flake8-4.0.1-pyhd3eb1b0_1
  flask-3.1.0-py310haa95532_0
  fonttools-4.55.3-py310h827c3e9_0
  gensim-4.3.3-py310hc64d2fc_0
  gmp-6.3.0-h537511b_0
  gmpy2-2.2.1-py310h827c3e9_0
  h5py-3.12.1-py310h535c9fb_1
  hdf5-1.14.5-ha36df97_2
  heapdict-1.0.1-pyhd3eb1b0_0
  holoviews-1.20.2-py310haa95532_0
  hvplot-0.11.2-py310haa95532_0
  hyperlink-21.0.0-pyhd3eb1b0_0
  icc_rt-2022.1.0-h6049295_2
  imageio-2.37.0-py310haa95532_0
  imagesize-1.4.1-py310haa95532_0
  imbalanced-learn-0.13.0-py310haa95532_0
  incremental-22.10.0-pyhd3eb1b0_0
  inflection-0.5.1-py310haa95532_0
  iniconfig-1.1.1-pyhd3eb1b0_0
  intake-2.0.7-py310haa95532_0
  intervaltree-3.1.0-pyhd3eb1b0_0
  ipython_genutils-0.2.0-pyhd3eb1b0_1
  ipywidgets-7.8.5-py310haa95532_0
  isort-6.0.1-py310haa95532_0
  itemadapter-0.3.0-pyhd3eb1b0_0
  itemloaders-1.3.2-py310haa95532_0
  itsdangerous-2.2.0-py310haa95532_0
  jellyfish-1.1.3-py310h8ecf97c_0
  jmespath-1.0.1-py310haa95532_0
  joblib-1.4.2-py310haa95532_0
  jq-1.6-haa95532_1
  jupyter-1.1.1-py310haa95532_0
  jupyter_console-6.6.3-py310haa95532_0
  jupyterlab_widgets-1.0.0-pyhd3eb1b0_1
  kiwisolver-1.4.8-py310h5da7b33_0
  lazy_loader-0.4-py310haa95532_0
  libspatialindex-1.9.3-h6c2663c_0
  libxslt-1.1.41-h0739af5_0
  llvmlite-0.44.0-py310h8b1c7eb_1
  locket-1.0.0-py310haa95532_0
  lxml-5.3.0-py310h395c83e_1
  lz4-4.3.2-py310h827c3e9_1
  lzo-2.10-he774522_2
  m2w64-libwinpthread-git-5.0.0.4634.697f757-2
  matplotlib-3.10.0-py310haa95532_0
  matplotlib-base-3.10.0-py310he19b0ae_0
  mccabe-0.6.1-py310haa95532_2
  mpc-1.3.1-h827c3e9_0
  mpfr-4.2.1-h56c3642_0
  mpmath-1.3.0-py310haa95532_0
  msgpack-python-1.0.3-py310h59b6b97_0
  multipledispatch-0.6.0-py310haa95532_0
  networkx-3.4.2-py310haa95532_0
  nltk-3.9.1-py310haa95532_0
  numba-0.61.0-py310h5da7b33_1
  numpydoc-1.7.0-py310haa95532_0
  openpyxl-3.1.5-py310h827c3e9_1
  paramiko-2.8.1-pyhd3eb1b0_0
  parsel-1.8.1-py310haa95532_0
  partd-1.4.2-py310haa95532_0
  pathspec-0.10.3-py310haa95532_0
  patsy-1.0.1-py310haa95532_0
  pep8-1.7.1-py310haa95532_1
  pexpect-4.8.0-pyhd3eb1b0_3
  plotly-5.24.1-py310h9909e9c_1
  prompt_toolkit-3.0.43-hd3eb1b0_0
  protego-0.1.16-py_0
  ptyprocess-0.7.0-pyhd3eb1b0_2
  py-cpuinfo-9.0.0-py310haa95532_0
  pyasn1-0.4.8-pyhd3eb1b0_0
  pyasn1-modules-0.2.8-py_0
  pycodestyle-2.8.0-pyhd3eb1b0_0
  pyct-0.5.0-py310haa95532_0
  pycurl-7.45.6-py310h51539b2_0
  pydispatcher-2.0.5-py310haa95532_2
  pydocstyle-6.3.0-py310haa95532_0
  pyerfa-2.0.1.5-py310h827c3e9_0
  pyflakes-2.4.0-pyhd3eb1b0_0
  pylint-3.3.5-py310haa95532_0
  pyls-spyder-0.4.0-pyhd3eb1b0_0
  pyodbc-5.2.0-py310h5da7b33_0
  pyopenssl-25.0.0-py310hb6ff9d5_0
  pyparsing-3.2.0-py310haa95532_0
  pytables-3.10.1-py310he42c613_1
  pytest-8.3.4-py310haa95532_0
  python-lmdb-1.6.2-py310h5da7b33_0
  python-lsp-black-1.0.0-pyhd3eb1b0_0
  python-lsp-jsonrpc-1.1.2-pyhd3eb1b0_0
  python-lsp-server-1.3.3-pyhd3eb1b0_0
  python-slugify-5.0.2-pyhd3eb1b0_0
  pytoolconfig-1.2.6-py310haa95532_0
  pywavelets-1.8.0-py310h827c3e9_0
  qdarkstyle-3.0.2-pyhd3eb1b0_0
  qstylizer-0.2.2-py310haa95532_0
  qtawesome-1.4.0-py310haa95532_0
  qtconsole-5.2.2-pyhd3eb1b0_0
  queuelib-1.6.2-py310haa95532_0
  regex-2024.11.6-py310h827c3e9_0
  requests-file-1.5.1-pyhd3eb1b0_0
  rope-1.13.0-py310haa95532_0
  rtree-1.0.1-py310h2eaa2aa_0
  s3transfer-0.11.2-py310haa95532_0
  sacremoses-0.0.43-pyhd3eb1b0_0
  scikit-image-0.25.0-py310h5da7b33_0
  scikit-learn-1.6.1-py310h585ebfc_0
  scikit-learn-intelex-2023.1.1-py310haa95532_0
  scipy-1.13.1-py310h8640f81_1
  scrapy-2.12.0-py310haa95532_1
  seaborn-0.13.2-py310haa95532_2
  service_identity-18.1.0-pyhd3eb1b0_1
  sklearn-compat-0.1.3-py310haa95532_0
  smart_open-5.2.1-py310haa95532_0
  snowballstemmer-2.2.0-pyhd3eb1b0_0
  sortedcontainers-2.4.0-pyhd3eb1b0_0
  sphinx-7.3.7-py310h827c3e9_0
  sphinxcontrib-applehelp-1.0.2-pyhd3eb1b0_0
  sphinxcontrib-devhelp-1.0.2-pyhd3eb1b0_0
  sphinxcontrib-htmlhelp-2.0.0-pyhd3eb1b0_0
  sphinxcontrib-jsmath-1.0.1-pyhd3eb1b0_0
  sphinxcontrib-qthelp-1.0.3-pyhd3eb1b0_0
  sphinxcontrib-serializinghtml-2.0.0-pyhd3eb1b0_0
  spyder-5.2.2-py310haa95532_1
  spyder-kernels-2.2.1-py310haa95532_0
  statsmodels-0.14.4-py310h827c3e9_0
  sympy-1.13.3-py310haa95532_1
  tbb4py-2021.8.0-py310h59b6b97_0
  tblib-1.7.0-pyhd3eb1b0_0
  text-unidecode-1.3-pyhd3eb1b0_0
  textdistance-4.2.1-pyhd3eb1b0_0
  threadpoolctl-3.5.0-py310h9909e9c_0
  three-merge-0.1.1-pyhd3eb1b0_0
  tifffile-2024.12.12-py310haa95532_0
  tldextract-5.1.2-py310haa95532_0
  tomlkit-0.13.2-py310haa95532_0
  toolz-1.0.0-py310haa95532_0
  transformers-2.1.1-pyhd3eb1b0_0
  twisted-23.10.0-py310haa95532_0
  twisted-iocpsupport-1.0.2-py310h827c3e9_1
  unicodedata2-15.1.0-py310h827c3e9_1
  unidecode-1.3.8-py310haa95532_0
  w3lib-2.1.2-py310haa95532_0
  werkzeug-3.1.3-py310haa95532_0
  widgetsnbextension-3.6.10-py310haa95532_0
  xarray-2024.11.0-py310haa95532_0
  xlwings-0.32.1-py310haa95532_1
  yapf-0.40.2-py310haa95532_0
  zict-3.0.0-py310haa95532_0
  zope-1.0-py310haa95532_1
  zope.interface-7.1.1-py310h827c3e9_0



Downloading and Extracting Packages:

Preparing transaction: done
Verifying transaction: done
Executing transaction: / Insufficient permissions to write menu folder.  Falling back to user location

/ Insufficient permissions to write menu folder.  Falling back to user location

-