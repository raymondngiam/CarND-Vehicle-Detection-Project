# Udacity Self Driving Car Nanodegree
## Vehicle Detection Project 

### Overview

This is a project for Udacity's Self Driving Car Nanodegree. The objective is to create a software pipeline to identify the vehicles from video stream of a front-facing camera on a car.

![Screenshot](/images/Screenshot.png)

### Video demo

You can see the video demo of the final outcome at [here](https://vimeo.com/246795777).

### Final report

You can view the final report of this project at [writeup.pdf](https://github.com/raymondngiam/CarND-Vehicle-Detection-Project/blob/master/writeup.pdf).

### Dependencies

- python==3.5.2
- jupyter
- numpy
- matplotlib
- opencv3
- scikit-image
- scikit-learn
- scipy
- pandas
- ffmpeg
- moviepy

### Installation

**Install Anaconda:**

Follow the instructions on the [Anaconda download site](https://www.continuum.io/downloads).

**Create environment:**

For users with CPU only, running this command will create a new `conda` environment that is provisioned with all libraries you need to run the codes.

```
$ conda env create -f environment.yml
```

**Uninstall environment:**

To uninstall the environment:

```
$ conda env remove -n vehicle-detection
```

**Activate environment:**

In order to use the environment, you will need to activate it. This must be done **each** time you open a new terminal window. 

```
$ source activate vehicle-detection
```

To exit the environment, simply close the terminal window or run the following command:

```
$ source deactivate vehicle-detection
```

### How to run

Extract image directories in `vehicle.zip`, `non-vehicles.zip` and `addon.zip` to the path `./`

You can step then through the Jupyter Notebook at [notebook.ipynb](https://github.com/raymondngiam/CarND-Vehicle-Detection-Project/blob/master/notebook.ipynb).

