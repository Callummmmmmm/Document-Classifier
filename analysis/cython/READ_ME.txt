To compile anagular_distance.so for your environment follow the steps below.

1. Install or upgrade the cython package

% pip install --upgrade cython

2. In a terminal, change directory to the python directory:

% cd <cython_dir>

3. Check your numpy version.

4. If your numpy version is 1.x run setup_numpy_1.py in a terminal as follows:

% python setup_numpy_1.py build_ext --inplace

If your numpy version is 2.x run setup_numpy_2.py in a terminal as follows:

% python setup_numpy_2.py build_ext --inplace

You may see some warnings but these can be ignored.

5. A shared object file named angular_distance.<cython_info>.so will be created at the top-level of the cython folder. Rename the shared object to angular_distance.so

6. Copy angular_distance.so to the analysis/mapping/_library/ folder.

