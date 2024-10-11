# Code to identify the type of gait limitation

<p>
To reproduce the results obtained in the article ‘Mobility Deficit Identification and Compensation through an Artificial Neural Network and Adaptive Controller Design during Gait’, you should consider the following procedure:
- Pre-processing and proccesing
- Prediction


## Codes 

### Pre-processing and proccesing:

<p> 
The code used for the pre-processing and processing of EMG signals was performed in R software using the following libraries: dummies, neuralnet, library(nnet), library(gmodels) and library(caret).

### Prediction:

<p> 
Values v1 to v24 correspond to the data provided by the Wavelet Transform referring to each class: normal, constraint 1, constraint 2, constraint 3.


###### NOTE: The complete code can be found in the ‘limitation identification’ section. Also, consider in line #4 of the code, the exact location where you have downloaded the .csv file.


If you need to use this information, please cite us like:

@article{XXX,
  title={Mobility Deficit Identification and Compensation through an Artificial Neural Network and Adaptive Controller Design during Gait},
  volume={XX}, 
  url={XXXXXX},
  abstractNote={This article presents a progressive compensation strategy for gait recovery in patients with different degrees of limited knee mobility, based on angular analysis and muscle electrical activity, and artificial intelligence. Ten subjects were tested during gait on a flat surface simulating 4 conditions of limited knee mobility with an active knee brace. Data on the amplitude of the electrical signal from 3 leg muscles were analyzed: rectus femoris, tibialis anterior, and gastrocnemius. In addition to the electromyography sensors, an angular position sensor was placed on the knee joint. An artificial neural network was trained to identify the type of limitation of each patient in their muscle activity. A knee orthosis with a linear actuator was designed to compensate for the loss of force during knee flexion-extension movement, according with limiting condition. The actuator trajectory is controlled through a model reference adaptive controller with a fuzzy logic-based adaptation mechanism. The simulation demonstrates the efficiency of this strategy, despite the high-amplitude disturbances in the system.},
  number={XXX},
  journal={IEEE Latin America Transactions},
  author={Chaparro-Cárdenas, Silvia L., Castillo-Castañeda, Eduardo, and Lozano-Guzmán Alejandro A.},
  year={2024},
  month={XXXX},
  pages={XXX-XXX}
}

