# assignment_1

>This is a program that use Neuron Network to let the machine learn XOR with 2-bit inputs.

## Compile & Run

### Compile 
    make
    cd bin
### Run
    ./run
## Example
Enter the number of Layers in Neural Network:
4   
Enter number of neurons in layer[1]:
2   
Enter number of neurons in layer[2]:
4   
Enter number of neurons in layer[3]:
4   
Enter number of neurons in layer[4]:
1   

Created Layer: 1    
Number of Neurons in Layer 1: 2 
Neuron 1 in Layer 1 created 
Neuron 2 in Layer 1 created 

Created Layer: 2    
Number of Neurons in Layer 2: 4 
Neuron 1 in Layer 2 created 
Neuron 2 in Layer 2 created 
Neuron 3 in Layer 2 created 
Neuron 4 in Layer 2 created 

Created Layer: 3    
Number of Neurons in Layer 3: 4 
Neuron 1 in Layer 3 created 
Neuron 2 in Layer 3 created 
Neuron 3 in Layer 3 created 
Neuron 4 in Layer 3 created 

Created Layer: 4    
Number of Neurons in Layer 4: 1 
Neuron 1 in Layer 4 created 


Initializing weights...
0:w[0][0]: 0.605810
1:w[0][0]: 0.705541
2:w[0][0]: 0.319974
3:w[0][0]: 0.215312
0:w[0][1]: 0.227372
1:w[0][1]: 0.207902
2:w[0][1]: 0.251316
3:w[0][1]: 0.091894
0:w[1][0]: 0.867804
1:w[1][0]: 0.807287
2:w[1][0]: 0.848030
3:w[1][0]: 0.338652
0:w[1][1]: 0.074524
1:w[1][1]: 0.326578
2:w[1][1]: 0.033888
3:w[1][1]: 0.167714
0:w[1][2]: 0.261093
1:w[1][2]: 0.993973
2:w[1][2]: 0.561518
3:w[1][2]: 0.795863
0:w[1][3]: 0.617838
1:w[1][3]: 0.110547
2:w[1][3]: 0.242498
3:w[1][3]: 0.452187
0:w[2][0]: 0.252594
0:w[2][1]: 0.482730
0:w[2][2]: 0.920476
0:w[2][3]: 0.073715

Neural Network Created Successfully...

Enter the learning rate (Usually 0.15): 
0.15

Enter the number of training examples:
4
Enter the Inputs for training example[0]:
0 0

Enter the Inputs for training example[1]:
0 1

Enter the Inputs for training example[2]:
1 0

Enter the Inputs for training example[3]:
1 1

Enter the Desired Outputs (Labels) for training example[0]: 
0

Enter the Desired Outputs (Labels) for training example[1]: 
1

Enter the Desired Outputs (Labels) for training example[2]: 
1

Enter the Desired Outputs (Labels) for training example[3]: 
0

Enter input to test:
0 0
Output: 0

Enter input to test:
0 1
Output: 1

Enter input to test:
1 0
Output: 1

Enter input to test:
1 1
Output: 0
