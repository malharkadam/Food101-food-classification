# Food_Vision

## DeepFood Paper: https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:655747d1-2d84-3d10-b3fc-e00000a7d3d3
### Use TensorFlow Datasets to Download Data

For many of the most popular datasets in the machine learning world (often referred to and used as benchmarks), you can access them through TensorFlow Datasets (TFDS).

What is TensorFlow Datasets?

A place for prepared and ready-to-use machine learning datasets.

Why use TensorFlow Datasets?

Load data already in Tensors
Practice on well established datasets
Experiment with differet data loading techniques (like we're going to use in this notebook)
Experiment with new TensorFlow features quickly (such as mixed precision training)
Why not use TensorFlow Datasets?

The datasets are static (they don't change, like your real-world datasets would)
Might not be suited for your particular problem (but great for experimenting)
To begin using TensorFlow Datasets we can import it under the alias tfds.
