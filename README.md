
(base) C:\Users\yun10>pip3 install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'

(base) C:\Users\yun10>pip3 install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'

(base) C:\Users\yun10>python3 setup.py install
Python
(base) C:\Users\yun10>pip3 install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'

(base) C:\Users\yun10>conda
usage: conda-script.py [-h] [-V] command ...

conda is a tool for managing and deploying applications, environments and packages.

Options:

positional arguments:
  command
    clean             Remove unused packages and caches.
    compare           Compare packages between conda environments.
    config            Modify configuration values in .condarc. This is modeled after the git config command. Writes to the
                      user .condarc file (C:\Users\yun10\.condarc) by default. Use the --show-sources flag to display all
                      identified configuration locations on your computer.
    create            Create a new conda environment from a list of specified packages.
    info              Display information about current conda install.
    init              Initialize conda for shell interaction.
    install           Installs a list of packages into a specified conda environment.
    list              List installed packages in a conda environment.
    package           Low-level conda package utility. (EXPERIMENTAL)
    remove (uninstall)
                      Remove a list of packages from a specified conda environment. Use `--all` flag to remove all packages
                      and the environment itself.
    rename            Renames an existing environment.
    run               Run an executable in a conda environment.
    search            Search for packages and display associated information.The input is a MatchSpec, a query language for
                      conda packages. See examples below.
    update (upgrade)  Updates conda packages to the latest compatible version.
    notices           Retrieves latest channel notifications.

options:
  -h, --help          Show this help message and exit.
  -V, --version       Show the conda version number and exit.

conda commands available from other packages (legacy):
  build
  content-trust
  convert
  debug
  develop
  env
  index
  inspect
  metapackage
  pack
  render
  repo
  server
  skeleton
  token
  verify

(base) C:\Users\yun10>conda activate opensw

EnvironmentNameNotFound: Could not find conda environment: opensw
You can list all discoverable environments with `conda info --envs`.



(base) C:\Users\yun10>conda create -n opensw python=3.7
Retrieving notices: ...working... done
Collecting package metadata (current_repodata.json): done
Solving environment: failed with repodata from current_repodata.json, will retry with next repodata source.
Collecting package metadata (repodata.json): done
Solving environment: done


==> WARNING: A newer version of conda exists. <==
  current version: 23.3.1
  latest version: 23.10.0

Please update conda by running

    $ conda update -n base -c defaults conda

Or to minimize the number of packages updated during conda update use

     conda install conda=23.10.0



## Package Plan ##

  environment location: C:\Users\yun10\anaconda3\envs\opensw

  added / updated specs:
    - python=3.7


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    certifi-2022.12.7          |   py37haa95532_0         149 KB
    pip-22.3.1                 |   py37haa95532_0         2.7 MB
    python-3.7.16              |       h6244533_0        17.2 MB
    setuptools-65.6.3          |   py37haa95532_0         1.1 MB
    wheel-0.38.4               |   py37haa95532_0          82 KB
    wincertstore-0.2           |   py37haa95532_2          15 KB
    ------------------------------------------------------------
                                           Total:        21.3 MB

The following NEW packages will be INSTALLED:

  ca-certificates    pkgs/main/win-64::ca-certificates-2023.08.22-haa95532_0
  certifi            pkgs/main/win-64::certifi-2022.12.7-py37haa95532_0
  openssl            pkgs/main/win-64::openssl-1.1.1w-h2bbff1b_0
  pip                pkgs/main/win-64::pip-22.3.1-py37haa95532_0
  python             pkgs/main/win-64::python-3.7.16-h6244533_0
  setuptools         pkgs/main/win-64::setuptools-65.6.3-py37haa95532_0
  sqlite             pkgs/main/win-64::sqlite-3.41.2-h2bbff1b_0
  vc                 pkgs/main/win-64::vc-14.2-h21ff451_1
  vs2015_runtime     pkgs/main/win-64::vs2015_runtime-14.27.29016-h5e58377_2
  wheel              pkgs/main/win-64::wheel-0.38.4-py37haa95532_0
  wincertstore       pkgs/main/win-64::wincertstore-0.2-py37haa95532_2


Proceed ([y]/n)? y


Downloading and Extracting Packages

Preparing transaction: done
Verifying transaction: done
Executing transaction: done
#
# To activate this environment, use
#
#     $ conda activate opensw
#
# To deactivate an active environment, use
#
#     $ conda deactivate


(base) C:\Users\yun10>conda activate opensw

(opensw) C:\Users\yun10>pip3 install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'

(opensw) C:\Users\yun10>pip3 install -r requirements.txt
ERROR: Could not open requirements file: [Errno 2] No such file or directory: 'requirements.txt'

(opensw) C:\Users\yun10>git clone https://github.com/Y0ungOne/Mask_RCNN.git
fatal: destination path 'Mask_RCNN' already exists and is not an empty directory.

(opensw) C:\Users\yun10>git clone https://github.com/Y0ungOne/Mask_RCNN.git
Cloning into 'Mask_RCNN'...
remote: Enumerating objects: 955, done.
remote: Total 955 (delta 0), reused 0 (delta 0), pack-reused 955
Receiving objects: 100% (955/955), 137.67 MiB | 16.90 MiB/s, done.
Resolving deltas: 100% (558/558), done.
Updating files: 100% (76/76), done.

(opensw) C:\Users\yun10>cd Mask_RCNN

(opensw) C:\Users\yun10\Mask_RCNN>pip3 install -r requirements.txt
Collecting numpy
  Downloading numpy-1.21.6-cp37-cp37m-win_amd64.whl (14.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 14.0/14.0 MB 13.6 MB/s eta 0:00:00
Collecting scipy
  Downloading scipy-1.7.3-cp37-cp37m-win_amd64.whl (34.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 34.1/34.1 MB 13.1 MB/s eta 0:00:00
Collecting Pillow
  Downloading Pillow-9.5.0-cp37-cp37m-win_amd64.whl (2.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.5/2.5 MB 16.2 MB/s eta 0:00:00
Collecting cython
  Downloading Cython-3.0.5-cp37-cp37m-win_amd64.whl (2.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.7/2.7 MB 21.7 MB/s eta 0:00:00
Collecting matplotlib
  Downloading matplotlib-3.5.3-cp37-cp37m-win_amd64.whl (7.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.2/7.2 MB 11.5 MB/s eta 0:00:00
Collecting scikit-image
  Downloading scikit_image-0.19.3-cp37-cp37m-win_amd64.whl (12.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 12.1/12.1 MB 12.6 MB/s eta 0:00:00
Collecting tensorflow>=1.3.0
  Downloading tensorflow-2.11.0-cp37-cp37m-win_amd64.whl (1.9 kB)
Collecting keras>=2.0.8
  Downloading keras-2.11.0-py2.py3-none-any.whl (1.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.7/1.7 MB 21.5 MB/s eta 0:00:00
Collecting opencv-python
  Downloading opencv_python-4.8.1.78-cp37-abi3-win_amd64.whl (38.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 38.1/38.1 MB 14.9 MB/s eta 0:00:00
Collecting h5py
  Downloading h5py-3.8.0-cp37-cp37m-win_amd64.whl (2.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.6/2.6 MB 16.8 MB/s eta 0:00:00
Collecting imgaug
  Downloading imgaug-0.4.0-py2.py3-none-any.whl (948 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 948.0/948.0 kB 20.0 MB/s eta 0:00:00
Collecting IPython[all]
  Downloading ipython-7.34.0-py3-none-any.whl (793 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 793.8/793.8 kB 16.7 MB/s eta 0:00:00
Collecting kiwisolver>=1.0.1
  Downloading kiwisolver-1.4.5-cp37-cp37m-win_amd64.whl (55 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 55.8/55.8 kB 2.8 MB/s eta 0:00:00
Collecting cycler>=0.10
  Using cached cycler-0.11.0-py3-none-any.whl (6.4 kB)
Collecting pyparsing>=2.2.1
  Using cached pyparsing-3.1.1-py3-none-any.whl (103 kB)
Collecting python-dateutil>=2.7
  Using cached python_dateutil-2.8.2-py2.py3-none-any.whl (247 kB)
Collecting fonttools>=4.22.0
  Downloading fonttools-4.38.0-py3-none-any.whl (965 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 965.4/965.4 kB 20.3 MB/s eta 0:00:00
Collecting packaging>=20.0
  Downloading packaging-23.2-py3-none-any.whl (53 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 53.0/53.0 kB 2.7 MB/s eta 0:00:00
Collecting PyWavelets>=1.1.1
  Downloading PyWavelets-1.3.0-cp37-cp37m-win_amd64.whl (4.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.2/4.2 MB 20.4 MB/s eta 0:00:00
Collecting networkx>=2.2
  Downloading networkx-2.6.3-py3-none-any.whl (1.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.9/1.9 MB 24.6 MB/s eta 0:00:00
Collecting tifffile>=2019.7.26
  Downloading tifffile-2021.11.2-py3-none-any.whl (178 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 178.9/178.9 kB ? eta 0:00:00
Collecting imageio>=2.4.1
  Downloading imageio-2.31.2-py3-none-any.whl (313 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 313.2/313.2 kB 9.5 MB/s eta 0:00:00
Collecting tensorflow-intel==2.11.0
  Downloading tensorflow_intel-2.11.0-cp37-cp37m-win_amd64.whl (266.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 266.3/266.3 MB 5.1 MB/s eta 0:00:00
Collecting astunparse>=1.6.0
  Downloading astunparse-1.6.3-py2.py3-none-any.whl (12 kB)
Collecting grpcio<2.0,>=1.24.3
  Downloading grpcio-1.59.3-cp37-cp37m-win_amd64.whl (4.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.3/4.3 MB 17.3 MB/s eta 0:00:00
Collecting flatbuffers>=2.0
  Downloading flatbuffers-23.5.26-py2.py3-none-any.whl (26 kB)
Collecting absl-py>=1.0.0
  Downloading absl_py-2.0.0-py3-none-any.whl (130 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 130.2/130.2 kB 7.5 MB/s eta 0:00:00
Collecting tensorflow-io-gcs-filesystem>=0.23.1
  Downloading tensorflow_io_gcs_filesystem-0.31.0-cp37-cp37m-win_amd64.whl (1.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.5/1.5 MB 15.9 MB/s eta 0:00:00
Requirement already satisfied: setuptools in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow-intel==2.11.0->tensorflow>=1.3.0->-r requirements.txt (line 7)) (65.6.3)
Collecting libclang>=13.0.0
  Downloading libclang-16.0.6-py2.py3-none-win_amd64.whl (24.4 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 24.4/24.4 MB 17.7 MB/s eta 0:00:00
Collecting google-pasta>=0.1.1
  Downloading google_pasta-0.2.0-py3-none-any.whl (57 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 57.5/57.5 kB 3.1 MB/s eta 0:00:00
Collecting tensorboard<2.12,>=2.11
  Downloading tensorboard-2.11.2-py3-none-any.whl (6.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 6.0/6.0 MB 20.2 MB/s eta 0:00:00
Collecting typing-extensions>=3.6.6
  Downloading typing_extensions-4.7.1-py3-none-any.whl (33 kB)
Collecting termcolor>=1.1.0
  Downloading termcolor-2.3.0-py3-none-any.whl (6.9 kB)
Collecting opt-einsum>=2.3.2
  Downloading opt_einsum-3.3.0-py3-none-any.whl (65 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 65.5/65.5 kB 3.7 MB/s eta 0:00:00
Collecting protobuf<3.20,>=3.9.2
  Downloading protobuf-3.19.6-cp37-cp37m-win_amd64.whl (896 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 896.6/896.6 kB 18.9 MB/s eta 0:00:00
Collecting six>=1.12.0
  Using cached six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting wrapt>=1.11.0
  Downloading wrapt-1.16.0-cp37-cp37m-win_amd64.whl (37 kB)
Collecting gast<=0.4.0,>=0.2.1
  Downloading gast-0.4.0-py3-none-any.whl (9.8 kB)
Collecting tensorflow-estimator<2.12,>=2.11.0
  Downloading tensorflow_estimator-2.11.0-py2.py3-none-any.whl (439 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 439.2/439.2 kB 26.8 MB/s eta 0:00:00
Collecting Shapely
  Downloading shapely-2.0.2-cp37-cp37m-win_amd64.whl (1.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.5/1.5 MB 22.9 MB/s eta 0:00:00
Collecting pygments
  Downloading pygments-2.17.2-py3-none-any.whl (1.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 18.9 MB/s eta 0:00:00
Collecting matplotlib-inline
  Downloading matplotlib_inline-0.1.6-py3-none-any.whl (9.4 kB)
Collecting backcall
  Downloading backcall-0.2.0-py2.py3-none-any.whl (11 kB)
Collecting colorama
  Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Collecting prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0
  Downloading prompt_toolkit-3.0.41-py3-none-any.whl (385 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 385.5/385.5 kB 23.5 MB/s eta 0:00:00
Collecting decorator
  Downloading decorator-5.1.1-py3-none-any.whl (9.1 kB)
Collecting pickleshare
  Downloading pickleshare-0.7.5-py2.py3-none-any.whl (6.9 kB)
Collecting jedi>=0.16
  Downloading jedi-0.19.1-py2.py3-none-any.whl (1.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.6/1.6 MB 16.6 MB/s eta 0:00:00
Collecting traitlets>=4.2
  Downloading traitlets-5.9.0-py3-none-any.whl (117 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 117.4/117.4 kB 6.7 MB/s eta 0:00:00
Collecting notebook
  Downloading notebook-6.5.6-py3-none-any.whl (529 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 529.8/529.8 kB 16.2 MB/s eta 0:00:00
Collecting ipywidgets
  Downloading ipywidgets-8.1.1-py3-none-any.whl (139 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 139.4/139.4 kB 8.6 MB/s eta 0:00:00
Collecting ipykernel
  Downloading ipykernel-6.16.2-py3-none-any.whl (138 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 138.5/138.5 kB 8.6 MB/s eta 0:00:00
Collecting qtconsole
  Downloading qtconsole-5.4.4-py3-none-any.whl (121 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 121.9/121.9 kB 7.0 MB/s eta 0:00:00
Collecting nose>=0.10.1
  Downloading nose-1.3.7-py3-none-any.whl (154 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 154.7/154.7 kB 9.0 MB/s eta 0:00:00
Collecting nbconvert
  Downloading nbconvert-7.6.0-py3-none-any.whl (290 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 290.4/290.4 kB 17.5 MB/s eta 0:00:00
Collecting Sphinx>=1.3
  Downloading sphinx-5.3.0-py3-none-any.whl (3.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.2/3.2 MB 18.4 MB/s eta 0:00:00
Collecting nbformat
  Downloading nbformat-5.8.0-py3-none-any.whl (77 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.4/77.4 kB 4.2 MB/s eta 0:00:00
Collecting testpath
  Downloading testpath-0.6.0-py3-none-any.whl (83 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 83.9/83.9 kB 4.6 MB/s eta 0:00:00
Collecting ipyparallel
  Downloading ipyparallel-8.6.1-py3-none-any.whl (298 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 298.1/298.1 kB 18.0 MB/s eta 0:00:00
Collecting requests
  Downloading requests-2.31.0-py3-none-any.whl (62 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 62.6/62.6 kB 3.5 MB/s eta 0:00:00
Collecting parso<0.9.0,>=0.8.3
  Downloading parso-0.8.3-py2.py3-none-any.whl (100 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 100.8/100.8 kB ? eta 0:00:00
Collecting wcwidth
  Downloading wcwidth-0.2.12-py2.py3-none-any.whl (34 kB)
Collecting sphinxcontrib-applehelp
  Downloading sphinxcontrib_applehelp-1.0.2-py2.py3-none-any.whl (121 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 121.2/121.2 kB 6.9 MB/s eta 0:00:00
Collecting sphinxcontrib-qthelp
  Downloading sphinxcontrib_qthelp-1.0.3-py2.py3-none-any.whl (90 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 90.6/90.6 kB 5.0 MB/s eta 0:00:00
Collecting sphinxcontrib-serializinghtml>=1.1.5
  Downloading sphinxcontrib_serializinghtml-1.1.5-py2.py3-none-any.whl (94 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 94.0/94.0 kB 5.2 MB/s eta 0:00:00
Collecting Jinja2>=3.0
  Downloading Jinja2-3.1.2-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.1/133.1 kB 8.2 MB/s eta 0:00:00
Collecting sphinxcontrib-htmlhelp>=2.0.0
  Downloading sphinxcontrib_htmlhelp-2.0.0-py2.py3-none-any.whl (100 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 100.5/100.5 kB ? eta 0:00:00
Collecting snowballstemmer>=2.0
  Downloading snowballstemmer-2.2.0-py2.py3-none-any.whl (93 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 93.0/93.0 kB 5.2 MB/s eta 0:00:00
Collecting importlib-metadata>=4.8
  Downloading importlib_metadata-6.7.0-py3-none-any.whl (22 kB)
Collecting docutils<0.20,>=0.14
  Downloading docutils-0.19-py3-none-any.whl (570 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 570.5/570.5 kB 18.1 MB/s eta 0:00:00
Collecting sphinxcontrib-jsmath
  Downloading sphinxcontrib_jsmath-1.0.1-py2.py3-none-any.whl (5.1 kB)
Collecting babel>=2.9
  Downloading Babel-2.13.1-py3-none-any.whl (10.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.1/10.1 MB 21.5 MB/s eta 0:00:00
Collecting alabaster<0.8,>=0.7
  Downloading alabaster-0.7.13-py3-none-any.whl (13 kB)
Collecting imagesize>=1.3
  Downloading imagesize-1.4.1-py2.py3-none-any.whl (8.8 kB)
Collecting sphinxcontrib-devhelp
  Downloading sphinxcontrib_devhelp-1.0.2-py2.py3-none-any.whl (84 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 84.7/84.7 kB 5.0 MB/s eta 0:00:00
Requirement already satisfied: certifi>=2017.4.17 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from requests->IPython[all]->-r requirements.txt (line 12)) (2022.12.7)
Collecting charset-normalizer<4,>=2
  Downloading charset_normalizer-3.3.2-cp37-cp37m-win_amd64.whl (98 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 98.1/98.1 kB 5.9 MB/s eta 0:00:00
Collecting urllib3<3,>=1.21.1
  Downloading urllib3-2.0.7-py3-none-any.whl (124 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 124.2/124.2 kB 7.1 MB/s eta 0:00:00
Collecting idna<4,>=2.5
  Downloading idna-3.4-py3-none-any.whl (61 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.5/61.5 kB 3.4 MB/s eta 0:00:00
Collecting debugpy>=1.0
  Downloading debugpy-1.7.0-cp37-cp37m-win_amd64.whl (5.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.0/5.0 MB 21.2 MB/s eta 0:00:00
Collecting psutil
  Downloading psutil-5.9.6-cp37-abi3-win_amd64.whl (252 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 252.3/252.3 kB 15.1 MB/s eta 0:00:00
Collecting tornado>=6.1
  Downloading tornado-6.2-cp37-abi3-win_amd64.whl (425 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 425.3/425.3 kB 25.9 MB/s eta 0:00:00
Collecting pyzmq>=17
  Downloading pyzmq-25.1.1-cp37-cp37m-win_amd64.whl (1.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 18.9 MB/s eta 0:00:00
Collecting jupyter-client>=6.1.12
  Downloading jupyter_client-7.4.9-py3-none-any.whl (133 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.5/133.5 kB 7.7 MB/s eta 0:00:00
Collecting nest-asyncio
  Downloading nest_asyncio-1.5.8-py3-none-any.whl (5.3 kB)
Collecting entrypoints
  Downloading entrypoints-0.4-py3-none-any.whl (5.3 kB)
Collecting tqdm
  Downloading tqdm-4.66.1-py3-none-any.whl (78 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.3/78.3 kB 4.5 MB/s eta 0:00:00
Collecting jupyterlab-widgets~=3.0.9
  Downloading jupyterlab_widgets-3.0.9-py3-none-any.whl (214 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 214.9/214.9 kB 12.8 MB/s eta 0:00:00
Collecting comm>=0.1.3
  Downloading comm-0.1.4-py3-none-any.whl (6.6 kB)
Collecting widgetsnbextension~=4.0.9
  Downloading widgetsnbextension-4.0.9-py3-none-any.whl (2.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 18.3 MB/s eta 0:00:00
Collecting nbclient>=0.5.0
  Downloading nbclient-0.7.4-py3-none-any.whl (73 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 73.1/73.1 kB ? eta 0:00:00
Collecting beautifulsoup4
  Downloading beautifulsoup4-4.12.2-py3-none-any.whl (142 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 143.0/143.0 kB 8.3 MB/s eta 0:00:00
Collecting jupyter-core>=4.7
  Downloading jupyter_core-4.12.0-py3-none-any.whl (89 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 89.9/89.9 kB 5.3 MB/s eta 0:00:00
Collecting tinycss2
  Downloading tinycss2-1.2.1-py3-none-any.whl (21 kB)
Collecting defusedxml
  Downloading defusedxml-0.7.1-py2.py3-none-any.whl (25 kB)
Collecting markupsafe>=2.0
  Downloading MarkupSafe-2.1.3-cp37-cp37m-win_amd64.whl (17 kB)
Collecting mistune<4,>=2.0.3
  Downloading mistune-3.0.2-py3-none-any.whl (47 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 48.0/48.0 kB 2.5 MB/s eta 0:00:00
Collecting pandocfilters>=1.4.1
  Downloading pandocfilters-1.5.0-py2.py3-none-any.whl (8.7 kB)
Collecting jupyterlab-pygments
  Downloading jupyterlab_pygments-0.2.2-py2.py3-none-any.whl (21 kB)
Collecting bleach!=5.0.0
  Downloading bleach-6.0.0-py3-none-any.whl (162 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 162.5/162.5 kB 4.9 MB/s eta 0:00:00
Collecting jsonschema>=2.6
  Downloading jsonschema-4.17.3-py3-none-any.whl (90 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 90.4/90.4 kB ? eta 0:00:00
Collecting fastjsonschema
  Downloading fastjsonschema-2.19.0-py3-none-any.whl (23 kB)
Collecting ipython-genutils
  Downloading ipython_genutils-0.2.0-py2.py3-none-any.whl (26 kB)
Collecting Send2Trash>=1.8.0
  Downloading Send2Trash-1.8.2-py3-none-any.whl (18 kB)
Collecting argon2-cffi
  Downloading argon2_cffi-23.1.0-py3-none-any.whl (15 kB)
Collecting terminado>=0.8.3
  Downloading terminado-0.17.1-py3-none-any.whl (17 kB)
Collecting prometheus-client
  Downloading prometheus_client-0.17.1-py3-none-any.whl (60 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 60.6/60.6 kB 3.1 MB/s eta 0:00:00
Collecting nbclassic>=0.4.7
  Downloading nbclassic-1.0.0-py3-none-any.whl (10.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.0/10.0 MB 11.4 MB/s eta 0:00:00
Collecting pyzmq>=17
  Downloading pyzmq-24.0.1-cp37-cp37m-win_amd64.whl (1.0 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.0/1.0 MB 10.7 MB/s eta 0:00:00
Collecting qtpy>=2.4.0
  Downloading QtPy-2.4.1-py3-none-any.whl (93 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 93.5/93.5 kB 2.7 MB/s eta 0:00:00
Requirement already satisfied: wheel<1.0,>=0.23.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from astunparse>=1.6.0->tensorflow-intel==2.11.0->tensorflow>=1.3.0->-r requirements.txt (line 7)) (0.38.4)
Collecting pytz>=2015.7
  Using cached pytz-2023.3.post1-py2.py3-none-any.whl (502 kB)
Collecting webencodings
  Downloading webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Collecting zipp>=0.5
  Downloading zipp-3.15.0-py3-none-any.whl (6.8 kB)
Collecting pyrsistent!=0.17.0,!=0.17.1,!=0.17.2,>=0.14.0
  Downloading pyrsistent-0.19.3-cp37-cp37m-win_amd64.whl (62 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 62.6/62.6 kB 3.3 MB/s eta 0:00:00
Collecting importlib-resources>=1.4.0
  Downloading importlib_resources-5.12.0-py3-none-any.whl (36 kB)
Collecting attrs>=17.4.0
  Downloading attrs-23.1.0-py3-none-any.whl (61 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.2/61.2 kB 3.2 MB/s eta 0:00:00
Collecting pkgutil-resolve-name>=1.3.10
  Downloading pkgutil_resolve_name-1.3.10-py3-none-any.whl (4.7 kB)
Collecting pywin32>=1.0
  Downloading pywin32-306-cp37-cp37m-win_amd64.whl (9.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 9.3/9.3 MB 7.6 MB/s eta 0:00:00
Collecting jupyter-server>=1.8
  Downloading jupyter_server-1.24.0-py3-none-any.whl (347 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 347.5/347.5 kB 10.9 MB/s eta 0:00:00
Collecting notebook-shim>=0.2.3
  Downloading notebook_shim-0.2.3-py3-none-any.whl (13 kB)
Collecting tensorboard-data-server<0.7.0,>=0.6.0
  Downloading tensorboard_data_server-0.6.1-py3-none-any.whl (2.4 kB)
Collecting google-auth<3,>=1.6.3
  Downloading google_auth-2.23.4-py2.py3-none-any.whl (183 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 183.3/183.3 kB ? eta 0:00:00
Collecting google-auth-oauthlib<0.5,>=0.4.1
  Downloading google_auth_oauthlib-0.4.6-py2.py3-none-any.whl (18 kB)
Collecting tensorboard-plugin-wit>=1.6.0
  Downloading tensorboard_plugin_wit-1.8.1-py3-none-any.whl (781 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 781.3/781.3 kB 12.4 MB/s eta 0:00:00
Collecting werkzeug>=1.0.1
  Downloading Werkzeug-2.2.3-py3-none-any.whl (233 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 233.6/233.6 kB 7.2 MB/s eta 0:00:00
Collecting markdown>=2.6.8
  Downloading Markdown-3.4.4-py3-none-any.whl (94 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 94.2/94.2 kB ? eta 0:00:00
Collecting pywinpty>=1.1.0
  Downloading pywinpty-2.0.10-cp37-none-win_amd64.whl (1.4 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.4/1.4 MB 14.9 MB/s eta 0:00:00
Collecting argon2-cffi-bindings
  Downloading argon2_cffi_bindings-21.2.0-cp36-abi3-win_amd64.whl (30 kB)
Collecting soupsieve>1.2
  Downloading soupsieve-2.4.1-py3-none-any.whl (36 kB)
Collecting rsa<5,>=3.1.4
  Downloading rsa-4.9-py3-none-any.whl (34 kB)
Collecting cachetools<6.0,>=2.0.0
  Downloading cachetools-5.3.2-py3-none-any.whl (9.3 kB)
Collecting pyasn1-modules>=0.2.1
  Downloading pyasn1_modules-0.3.0-py2.py3-none-any.whl (181 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 181.3/181.3 kB 10.7 MB/s eta 0:00:00
Collecting requests-oauthlib>=0.7.0
  Downloading requests_oauthlib-1.3.1-py2.py3-none-any.whl (23 kB)
Collecting websocket-client
  Downloading websocket_client-1.6.1-py3-none-any.whl (56 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 56.9/56.9 kB 2.9 MB/s eta 0:00:00
Collecting anyio<4,>=3.1.0
  Downloading anyio-3.7.1-py3-none-any.whl (80 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 80.9/80.9 kB 4.7 MB/s eta 0:00:00
Collecting cffi>=1.0.1
  Downloading cffi-1.15.1-cp37-cp37m-win_amd64.whl (179 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 179.3/179.3 kB 11.3 MB/s eta 0:00:00
Collecting exceptiongroup
  Downloading exceptiongroup-1.2.0-py3-none-any.whl (16 kB)
Collecting sniffio>=1.1
  Downloading sniffio-1.3.0-py3-none-any.whl (10 kB)
Collecting pycparser
  Downloading pycparser-2.21-py2.py3-none-any.whl (118 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 118.7/118.7 kB 7.2 MB/s eta 0:00:00
Collecting pyasn1<0.6.0,>=0.4.6
  Downloading pyasn1-0.5.1-py2.py3-none-any.whl (84 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 84.9/84.9 kB 5.0 MB/s eta 0:00:00
Collecting oauthlib>=3.0.0
  Downloading oauthlib-3.2.2-py3-none-any.whl (151 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 151.7/151.7 kB 8.8 MB/s eta 0:00:00
Installing collected packages: webencodings, wcwidth, tensorboard-plugin-wit, snowballstemmer, pywin32, pytz, pickleshare, nose, libclang, ipython-genutils, flatbuffers, fastjsonschema, backcall, zipp, wrapt, widgetsnbextension, websocket-client, urllib3, typing-extensions, traitlets, tornado, tinycss2, testpath, termcolor, tensorflow-io-gcs-filesystem, tensorflow-estimator, tensorboard-data-server, sphinxcontrib-serializinghtml, sphinxcontrib-qthelp, sphinxcontrib-jsmath, sphinxcontrib-htmlhelp, sphinxcontrib-devhelp, sphinxcontrib-applehelp, soupsieve, sniffio, six, Send2Trash, pyzmq, pywinpty, pyrsistent, pyparsing, pygments, pycparser, pyasn1, psutil, protobuf, prompt-toolkit, prometheus-client, pkgutil-resolve-name, Pillow, parso, pandocfilters, packaging, oauthlib, numpy, networkx, nest-asyncio, mistune, markupsafe, keras, jupyterlab-widgets, jupyterlab-pygments, imagesize, idna, grpcio, gast, fonttools, exceptiongroup, entrypoints, docutils, defusedxml, decorator, debugpy, cython, cycler, colorama, charset-normalizer, cachetools, babel, alabaster, absl-py, werkzeug, tqdm, tifffile, terminado, Shapely, scipy, rsa, requests, qtpy, PyWavelets, python-dateutil, pyasn1-modules, opt-einsum, opencv-python, matplotlib-inline, kiwisolver, jupyter-core, Jinja2, jedi, importlib-resources, importlib-metadata, imageio, h5py, google-pasta, comm, cffi, bleach, beautifulsoup4, astunparse, anyio, Sphinx, scikit-image, requests-oauthlib, matplotlib, markdown, jupyter-client, IPython, google-auth, attrs, argon2-cffi-bindings, jsonschema, ipywidgets, ipykernel, imgaug, google-auth-oauthlib, argon2-cffi, tensorboard, qtconsole, nbformat, ipyparallel, tensorflow-intel, nbclient, tensorflow, nbconvert, jupyter-server, notebook-shim, nbclassic, notebook
Successfully installed IPython-7.34.0 Jinja2-3.1.2 Pillow-9.5.0 PyWavelets-1.3.0 Send2Trash-1.8.2 Shapely-2.0.2 Sphinx-5.3.0 absl-py-2.0.0 alabaster-0.7.13 anyio-3.7.1 argon2-cffi-23.1.0 argon2-cffi-bindings-21.2.0 astunparse-1.6.3 attrs-23.1.0 babel-2.13.1 backcall-0.2.0 beautifulsoup4-4.12.2 bleach-6.0.0 cachetools-5.3.2 cffi-1.15.1 charset-normalizer-3.3.2 colorama-0.4.6 comm-0.1.4 cycler-0.11.0 cython-3.0.5 debugpy-1.7.0 decorator-5.1.1 defusedxml-0.7.1 docutils-0.19 entrypoints-0.4 exceptiongroup-1.2.0 fastjsonschema-2.19.0 flatbuffers-23.5.26 fonttools-4.38.0 gast-0.4.0 google-auth-2.23.4 google-auth-oauthlib-0.4.6 google-pasta-0.2.0 grpcio-1.59.3 h5py-3.8.0 idna-3.4 imageio-2.31.2 imagesize-1.4.1 imgaug-0.4.0 importlib-metadata-6.7.0 importlib-resources-5.12.0 ipykernel-6.16.2 ipyparallel-8.6.1 ipython-genutils-0.2.0 ipywidgets-8.1.1 jedi-0.19.1 jsonschema-4.17.3 jupyter-client-7.4.9 jupyter-core-4.12.0 jupyter-server-1.24.0 jupyterlab-pygments-0.2.2 jupyterlab-widgets-3.0.9 keras-2.11.0 kiwisolver-1.4.5 libclang-16.0.6 markdown-3.4.4 markupsafe-2.1.3 matplotlib-3.5.3 matplotlib-inline-0.1.6 mistune-3.0.2 nbclassic-1.0.0 nbclient-0.7.4 nbconvert-7.6.0 nbformat-5.8.0 nest-asyncio-1.5.8 networkx-2.6.3 nose-1.3.7 notebook-6.5.6 notebook-shim-0.2.3 numpy-1.21.6 oauthlib-3.2.2 opencv-python-4.8.1.78 opt-einsum-3.3.0 packaging-23.2 pandocfilters-1.5.0 parso-0.8.3 pickleshare-0.7.5 pkgutil-resolve-name-1.3.10 prometheus-client-0.17.1 prompt-toolkit-3.0.41 protobuf-3.19.6 psutil-5.9.6 pyasn1-0.5.1 pyasn1-modules-0.3.0 pycparser-2.21 pygments-2.17.2 pyparsing-3.1.1 pyrsistent-0.19.3 python-dateutil-2.8.2 pytz-2023.3.post1 pywin32-306 pywinpty-2.0.10 pyzmq-24.0.1 qtconsole-5.4.4 qtpy-2.4.1 requests-2.31.0 requests-oauthlib-1.3.1 rsa-4.9 scikit-image-0.19.3 scipy-1.7.3 six-1.16.0 sniffio-1.3.0 snowballstemmer-2.2.0 soupsieve-2.4.1 sphinxcontrib-applehelp-1.0.2 sphinxcontrib-devhelp-1.0.2 sphinxcontrib-htmlhelp-2.0.0 sphinxcontrib-jsmath-1.0.1 sphinxcontrib-qthelp-1.0.3 sphinxcontrib-serializinghtml-1.1.5 tensorboard-2.11.2 tensorboard-data-server-0.6.1 tensorboard-plugin-wit-1.8.1 tensorflow-2.11.0 tensorflow-estimator-2.11.0 tensorflow-intel-2.11.0 tensorflow-io-gcs-filesystem-0.31.0 termcolor-2.3.0 terminado-0.17.1 testpath-0.6.0 tifffile-2021.11.2 tinycss2-1.2.1 tornado-6.2 tqdm-4.66.1 traitlets-5.9.0 typing-extensions-4.7.1 urllib3-2.0.7 wcwidth-0.2.12 webencodings-0.5.1 websocket-client-1.6.1 werkzeug-2.2.3 widgetsnbextension-4.0.9 wrapt-1.16.0 zipp-3.15.0

(opensw) C:\Users\yun10\Mask_RCNN>python3 setup.py install
Python
(opensw) C:\Users\yun10\Mask_RCNN>cd balloon_dataset
지정된 경로를 찾을 수 없습니다.

(opensw) C:\Users\yun10\Mask_RCNN>cd datasets

(opensw) C:\Users\yun10\Mask_RCNN\datasets>cd balloon_dataset

(opensw) C:\Users\yun10\Mask_RCNN\datasets\balloon_dataset>python balloon.py train --dataset=../../datasets/balloon --weights=coco
python: can't open file 'balloon.py': [Errno 2] No such file or directory

(opensw) C:\Users\yun10\Mask_RCNN\datasets\balloon_dataset>cd../..

(opensw) C:\Users\yun10\Mask_RCNN>cd samples/balloon

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>python balloon.py train --dataset=../../datasets/balloon --weights=coco
Traceback (most recent call last):
  File "balloon.py", line 43, in <module>
    from mrcnn import model as modellib, utils
  File "C:\Users\yun10\Mask_RCNN\mrcnn\model.py", line 19, in <module>
    import tensorflow as tf
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\__init__.py", line 81, in <module>
    from ._api.v2 import summary
  File "<frozen importlib._bootstrap>", line 983, in _find_and_load
  File "<frozen importlib._bootstrap>", line 967, in _find_and_load_unlocked
  File "<frozen importlib._bootstrap>", line 677, in _load_unlocked
  File "<frozen importlib._bootstrap_external>", line 724, in exec_module
  File "<frozen importlib._bootstrap_external>", line 818, in get_code
  File "<frozen importlib._bootstrap_external>", line 916, in get_data
KeyboardInterrupt

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>python balloon.py train --dataset=../../datasets/balloon --weights=coco
Traceback (most recent call last):
  File "balloon.py", line 43, in <module>
    from mrcnn import model as modellib, utils
  File "C:\Users\yun10\Mask_RCNN\mrcnn\model.py", line 255, in <module>
    class ProposalLayer(KE.Layer):
AttributeError: module 'keras.engine' has no attribute 'Layer'

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>pip uninstall tensorflow keras
Found existing installation: tensorflow 2.11.0
Uninstalling tensorflow-2.11.0:
  Would remove:
    c:\users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow-2.11.0.dist-info\*
Proceed (Y/n)? y
  Successfully uninstalled tensorflow-2.11.0
Found existing installation: keras 2.11.0
Uninstalling keras-2.11.0:
  Would remove:
    c:\users\yun10\anaconda3\envs\opensw\lib\site-packages\keras-2.11.0.dist-info\*
    c:\users\yun10\anaconda3\envs\opensw\lib\site-packages\keras\*
Proceed (Y/n)? y
  Successfully uninstalled keras-2.11.0

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>pip install tensorflow==1.14.0 keras==2.0.8
Collecting tensorflow==1.14.0
  Downloading tensorflow-1.14.0-cp37-cp37m-win_amd64.whl (68.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 68.3/68.3 MB 7.6 MB/s eta 0:00:00
Collecting keras==2.0.8
  Downloading Keras-2.0.8-py2.py3-none-any.whl (276 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 276.1/276.1 kB 16.6 MB/s eta 0:00:00
Requirement already satisfied: protobuf>=3.6.1 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (3.19.6)
Collecting astor>=0.6.0
  Downloading astor-0.8.1-py2.py3-none-any.whl (27 kB)
Requirement already satisfied: google-pasta>=0.1.6 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (0.2.0)
Collecting tensorflow-estimator<1.15.0rc0,>=1.14.0rc0
  Downloading tensorflow_estimator-1.14.0-py2.py3-none-any.whl (488 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 488.5/488.5 kB 15.4 MB/s eta 0:00:00
Requirement already satisfied: grpcio>=1.8.6 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (1.59.3)
Requirement already satisfied: gast>=0.2.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (0.4.0)
Requirement already satisfied: wheel>=0.26 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (0.38.4)
Collecting keras-preprocessing>=1.0.5
  Downloading Keras_Preprocessing-1.1.2-py2.py3-none-any.whl (42 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 42.6/42.6 kB 2.0 MB/s eta 0:00:00
Collecting tensorboard<1.15.0,>=1.14.0
  Downloading tensorboard-1.14.0-py3-none-any.whl (3.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.1/3.1 MB 16.8 MB/s eta 0:00:00
Requirement already satisfied: numpy<2.0,>=1.14.5 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (1.21.6)
Requirement already satisfied: six>=1.10.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (1.16.0)
Collecting keras-applications>=1.0.6
  Downloading Keras_Applications-1.0.8-py3-none-any.whl (50 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 50.7/50.7 kB 2.5 MB/s eta 0:00:00
Requirement already satisfied: termcolor>=1.1.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (2.3.0)
Requirement already satisfied: wrapt>=1.11.1 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (1.16.0)
Requirement already satisfied: absl-py>=0.7.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorflow==1.14.0) (2.0.0)
Requirement already satisfied: scipy>=0.14 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from keras==2.0.8) (1.7.3)
Collecting pyyaml
  Downloading PyYAML-6.0.1-cp37-cp37m-win_amd64.whl (153 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 153.2/153.2 kB 8.9 MB/s eta 0:00:00
Requirement already satisfied: h5py in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from keras-applications>=1.0.6->tensorflow==1.14.0) (3.8.0)
Requirement already satisfied: markdown>=2.6.8 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (3.4.4)
Requirement already satisfied: setuptools>=41.0.0 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (65.6.3)
Requirement already satisfied: werkzeug>=0.11.15 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (2.2.3)
Requirement already satisfied: importlib-metadata>=4.4 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from markdown>=2.6.8->tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (6.7.0)
Requirement already satisfied: MarkupSafe>=2.1.1 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from werkzeug>=0.11.15->tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (2.1.3)
Requirement already satisfied: zipp>=0.5 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from importlib-metadata>=4.4->markdown>=2.6.8->tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (3.15.0)
Requirement already satisfied: typing-extensions>=3.6.4 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from importlib-metadata>=4.4->markdown>=2.6.8->tensorboard<1.15.0,>=1.14.0->tensorflow==1.14.0) (4.7.1)
Installing collected packages: tensorflow-estimator, pyyaml, keras-preprocessing, astor, keras-applications, keras, tensorboard, tensorflow
  Attempting uninstall: tensorflow-estimator
    Found existing installation: tensorflow-estimator 2.11.0
    Uninstalling tensorflow-estimator-2.11.0:
      Successfully uninstalled tensorflow-estimator-2.11.0
  Attempting uninstall: tensorboard
    Found existing installation: tensorboard 2.11.2
    Uninstalling tensorboard-2.11.2:
      Successfully uninstalled tensorboard-2.11.2
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
tensorflow-intel 2.11.0 requires keras<2.12,>=2.11.0, but you have keras 2.0.8 which is incompatible.
tensorflow-intel 2.11.0 requires tensorboard<2.12,>=2.11, but you have tensorboard 1.14.0 which is incompatible.
tensorflow-intel 2.11.0 requires tensorflow-estimator<2.12,>=2.11.0, but you have tensorflow-estimator 1.14.0 which is incompatible.
Successfully installed astor-0.8.1 keras-2.0.8 keras-applications-1.0.8 keras-preprocessing-1.1.2 pyyaml-6.0.1 tensorboard-1.14.0 tensorflow-1.14.0 tensorflow-estimator-1.14.0

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>pip uninstall h5py
Found existing installation: h5py 3.8.0
Uninstalling h5py-3.8.0:
  Would remove:
    c:\users\yun10\anaconda3\envs\opensw\lib\site-packages\h5py-3.8.0.dist-info\*
    c:\users\yun10\anaconda3\envs\opensw\lib\site-packages\h5py\*
Proceed (Y/n)? y
  Successfully uninstalled h5py-3.8.0

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>pip install h5py==2.10.0
Collecting h5py==2.10.0
  Downloading h5py-2.10.0-cp37-cp37m-win_amd64.whl (2.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.5/2.5 MB 15.9 MB/s eta 0:00:00
Requirement already satisfied: numpy>=1.7 in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from h5py==2.10.0) (1.21.6)
Requirement already satisfied: six in c:\users\yun10\anaconda3\envs\opensw\lib\site-packages (from h5py==2.10.0) (1.16.0)
Installing collected packages: h5py
ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
tensorflow-intel 2.11.0 requires keras<2.12,>=2.11.0, but you have keras 2.0.8 which is incompatible.
tensorflow-intel 2.11.0 requires tensorboard<2.12,>=2.11, but you have tensorboard 1.14.0 which is incompatible.
tensorflow-intel 2.11.0 requires tensorflow-estimator<2.12,>=2.11.0, but you have tensorflow-estimator 1.14.0 which is incompatible.
Successfully installed h5py-2.10.0

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>python balloon.py train --dataset=../../datasets/balloon --weights=coco
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:516: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  _np_qint8 = np.dtype([("qint8", np.int8, 1)])
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:517: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  _np_quint8 = np.dtype([("quint8", np.uint8, 1)])
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:518: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  _np_qint16 = np.dtype([("qint16", np.int16, 1)])
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:519: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  _np_quint16 = np.dtype([("quint16", np.uint16, 1)])
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:520: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  _np_qint32 = np.dtype([("qint32", np.int32, 1)])
C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\framework\dtypes.py:525: FutureWarning: Passing (type, 1) or '1type' as a synonym of type is deprecated; in a future version of numpy, it will be understood as (type, (1,)) / '(1,)type'.
  np_resource = np.dtype([("resource", np.ubyte, 1)])
Traceback (most recent call last):
  File "balloon.py", line 43, in <module>
    from mrcnn import model as modellib, utils
  File "C:\Users\yun10\Mask_RCNN\mrcnn\model.py", line 19, in <module>
    import tensorflow as tf
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\__init__.py", line 28, in <module>
    from tensorflow.python import pywrap_tensorflow  # pylint: disable=unused-import
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\__init__.py", line 83, in <module>
    from tensorflow.python import keras
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\__init__.py", line 26, in <module>
    from tensorflow.python.keras import activations
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\activations.py", line 24, in <module>
    from tensorflow.python.keras.utils.generic_utils import deserialize_keras_object
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\utils\__init__.py", line 39, in <module>
    from tensorflow.python.keras.utils.multi_gpu_utils import multi_gpu_model
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\utils\multi_gpu_utils.py", line 22, in <module>
    from tensorflow.python.keras.engine.training import Model
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\engine\training.py", line 40, in <module>
    from tensorflow.python.keras.engine import network
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\engine\network.py", line 39, in <module>
    from tensorflow.python.keras import saving
  File "C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\saving\__init__.py", line 33, in <module>
    from tensorflow.python.keras.saving.saved_model import export_saved_model
ImportError: cannot import name 'export_saved_model' from 'tensorflow.python.keras.saving.saved_model' (C:\Users\yun10\anaconda3\envs\opensw\lib\site-packages\tensorflow\python\keras\saving\saved_model\__init__.py)

(opensw) C:\Users\yun10\Mask_RCNN\samples\balloon>
열심히 해보았지만 마지막에 이상한 오류로인해 더이상 진해할 수 없었습니다 죄송합니다..