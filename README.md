# profilometry_nx2


An environment and simple notebooks for noodling with the Zygo NX2 datx profilometry data used to characterize flyer cutting results for optimization. Nothing really clever but it has some example data files from the AIMD-L NX2 and uses the h5py to library to list the metadata and load the associated interferometry data into a dataframe. It uses datx2py from [George Kaplan's GIST](https://gist.github.com/g-s-k/ccffb1e84df065a690e554f4b40cfd3a) of  the same name. It's set up to work in a conda environment:


1. Clone this repo and cd to it.
2. ```create env -f environment.yml```
3. ```activate profilometry```
4. Try the notebooks



