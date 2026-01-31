## Mars Terrain Segmentation

This challenge involved segmenting black and white Mars images into five classes: **Background, Soil, Bedrock, Sand, and Big Rocks**. We built a deep learning model from scratch, optimizing it for the **Mean Intersection over Union (MeanIOU) metric**.

<img src="img/sample.png" alt="Sample segmentation" width="300">

Mars terrain segmentation is challenging due to strong class imbalance, low-resolution grayscale imagery, and subtle visual differences between terrain types, especially for small and rare structures such as Big Rocks. Moreover, as said before, images were black and white.

While designing and implementing our solution, we explored:
- Dataset cleaning and analysis
- Data augmentation
- Custom semantic segmentation architectures
- Hyperparameter tuning
- Loss engineering for class imbalance
- Multi-path feature extraction
- Challenge-driven optimization strategies
- The model performance was evaluated using Mean Intersection over Union (MeanIOU) on the official challenge test set.

## Libraries

The core implementation was developed using TensorFlow Keras. We also used NumPy, Matplotlib, and Seaborn for secondary purposes.
Additional experiments with alternative architectures were conducted using PyTorch. We also used Optuna for automated hyperparameter optimization.

## More Info

Refer to the [report](report.pdf) and [notebooks](/notebooks).

## Team

I thank my colleagues and friends [Matteo Salari](https://github.com/matteo-salari), [Davide Salonico](https://github.com/DavideSalonico) and [Federica Topazio](https://github.com/federicatopazio) who worked with me on this project.
