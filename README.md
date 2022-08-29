## augment-tao
This notebook dowload KIIT dataset and ingests the downloaded KITTI dataset and augments the dataset. For this use case we add
a spatial rotation of 10 degrees.
a color space hue rotation of 5 degrees.
Note: The offline augmentation graph has a very small GPU footprint. Therefore, to maximize GPU utilization you may use a larger batch size by using the --batch_size option on the command line. By default this parameter is set to 4. The number of images that can be fit in a batch is governed by the memory available in your GPU.
##PBNET
