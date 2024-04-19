# SomnoGuard: Real-time Drowsiness and Fatigue Detection System for Drivers

SomnoGuard is an advanced deep learning-based system designed to detect drowsiness and fatigue in real-time among drivers. The alarming statistics highlighting the impact of drowsiness and fatigue on road safety have been the driving force behind the development of this algorithm. By alerting drivers at an early stage, we aim to significantly reduce the mortality rate associated with such risks.

## Key Features

- Utilizes Convolutional Neural Networks (CNN) to detect the state of the driver's eyes, indicating drowsiness.
- Implements the Yawning Detection algorithm using the Lip Activity Ratio (LAR) for fatigue detection.
- Provides real-time monitoring and alerts to drivers when signs of drowsiness or fatigue are detected.

## Usage

1. Run the main script to launch the SomnoGuard application.
2. Connect the driver monitoring system to the appropriate sensors and cameras.
3. The system will continuously monitor the driver's eyes and mouth, detect signs of drowsiness and fatigue, and provide real-time alerts.

## Model Architecture

![Model Architecture](Images/Architecture.png)

The architecture diagram above provides a detailed view of the layers and components of the CNN used in SomnoGuard.

## Résultats

### Confusion Matrix

![Confusion Matrix](Images/MatriceConfusion.png)

The confusion matrix provides insights into the accuracy of the model across different classes.

### Classification Report

![Classification Report](Images/ClassReport.png)

The classification report shows precision, recall, and F1-score metrics for each class, providing a comprehensive overview of model performance.

### Resultas

![System in Action](Images/results1.png)
![Detection Example](Images/results2.png)

These images illustrate the real-time detection capabilities of SomnoGuard, showing the system actively monitoring and detecting signs of fatigue.

## Roadmap

- Implement the proposed work on an embedded system to reduce computation time and improve real-world utilization.
- Integrate an infrared lighting system that activates only during nighttime for enhanced scene acquisition.
- Incorporate gaze direction analysis to precisely monitor the driver's focus.

## Presentation

[View the Presentation on Prezi](https://prezi.com/p/mv94z4ipr4om/projet15/?fallback=1)

## Contributors

BADI Oumaima & BELFROUH Sanae

Feel free to contribute to this project by opening issues, submitting pull requests, or suggesting new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
