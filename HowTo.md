How to use FUNPSY

# Installation #

The code is managed with SVN. This is a more efficient way to be up to date with latest versions. Please make sure your operating system has SVN installed and checkout the code from:
https://code.google.com/p/funpsy/source/checkout

For an introduction to SVN, see: http://svnbook.red-bean.com/


# How to prepare your data #

Funpsy currently works with data from experiments were all subjects are undergoing the same stimulation in sync (e.g. watching a feature film). It is an extension of methods such as intersubject correlation (https://code.google.com/p/isc-toolbox/) with the added temporal dimension. The phase synchrony method has however also been used successfully at rest with real data and models (see for example http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004100).

The toolbox has been tested with data preprocessed following the FEAT FSL pipeline with coregistration to the 2mm MNI 152 template. Other spatial resolutions or volume sizes are allowed as long as the user provides a matching mask of voxels of interests of the same size of the data.

# How to run it #

The easiest way is for you to open funpsy\_demo.m and look at the comments. Just run funpsy\_demo with your dataset and parameters of choice to obtain all the results.

## More detailed description of funpsy\_demo.m ##

### Inputting the data ###

### Selecting a bandpass filter ###
TR is important!

### Intersubject phase synchronization ###

### Dynamic functional connectivity with seed based phase synchronization (SBPS) ###

### Intersubject SBPS ###

### How to prepare your ROIs ###

### Statistics ###

### Output formats ###

### Group based analysis ###

### Model based analysis (GLM) ###