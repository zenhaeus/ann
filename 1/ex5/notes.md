- Naive, 2 hidden layers
    Loss: 0.337781 (validation), 0.0591621 (training)
    Accuracy: 0.8861 (validation), 0.9784 (training)
- 2 hidden layers, batch normalization between
    Loss: 0.347847 (validation), 0.0628772 (training)
    Accuracy: 0.8811 (validation), 0.976633 (training)
- 2 hidden layers, batch normalization before and between
    Loss: 0.33677 (validation), 0.0513677 (training)
    Accuracy: 0.8846 (validation), 0.9806 (training)
- 2 hidden layers, batch normalization + dropout before and between
    Loss: 0.324449 (validation), 0.360214 (training)
    Accuracy: 0.8835 (validation), 0.86525 (training)
- 2 hidden layers, dropout before, batch normalization + dropout between
    Loss: 0.333724 (validation), 0.368651 (training)
    Accuracy: 0.8787 (validation), 0.862133 (training)
- 2 hidden layers, batch normalization + dropout before and between, L1(0.01), kernel only
    Loss: 0.99199 (validation), 1.11049 (training)
    Accuracy: 0.8155 (validation), 0.770217 (training)
- 2 hidden layers, batch normalization + dropout before and between, L1(0.01)
    Loss: 1.05785 (validation), 1.17058 (training)
    Accuracy: 0.8147 (validation), 0.77295 (training)
- 2 hidden layers, batch normalization + dropout before and between, L1(0.001)
    Loss: 0.638032 (validation), 0.709431 (training)
    Accuracy: 0.8501 (validation), 0.820217 (training)
- 2 hidden layers, batch normalization + dropout before and between, L1(0.0001)
    Loss: 0.455933 (validation), 0.507505 (training)
    Accuracy: 0.8723 (validation), 0.850433 (training)
- 2 hidden layers, batch normalization + dropout before and between, L2(0.001)
    Loss: 0.414332 (validation), 0.472909 (training)
    Accuracy: 0.8702 (validation), 0.8464 (training)
- 2 hidden layers, batch normalization + dropout before, between and after
    Loss: 0.340673 (validation), 0.41063 (training)
    Accuracy: 0.8768 (validation), 0.8496 (training)
- 2 hidden layers, batch normalization + dropout before, between and after (2)
    Loss: 0.32734 (validation), 0.359697 (training)
    Accuracy: 0.8794 (validation), 0.864983 (training)
- 2 hidden layers, batch normalization + dropout before and between (MNIST)
    Loss: 0.325486 (validation), 0.36349 (training)
    Accuracy: 0.882 (validation), 0.863783 (training)
