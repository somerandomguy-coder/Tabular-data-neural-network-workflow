# Tabular-data-neural-network-workflow
Follow best practice to create a good neural network architecture that works well with tabular data.

The video that inspired this repo: https://www.youtube.com/watch?v=WPQOkoXhdBQ

## Project phase:
###  Experiment with google colab
1. Preparation
- Handling *missing* data
- Dealing *categorical* data
- Dealing *text* data
- *Normalize* data

2. Design
- *K-fold cross validation*
- Benchmark with *other model type*
- Start with *low capacity* network (1 hidden layer + direct input-output like residual connection to capture linear relationship)
- Determine *output* activation and loss function according to the target distribution (for regression only)
- Choosing *hidden layer* activation function
- Choosing *batch size*
- Choosing *learning rate* (using learning rate range test)
- Design the learning rate *cycle* (warm up, decay, cool down)
- Choosing number of *epoch* (binary search)
3. Training
- Compare prediction to actual data *distribution* *in-training* (mostly for regression)
- Track training and validation *loss*
- Examine *confident* & *confusion*
4. Assessment
- Compare with other model in the benchmark
 <img width="1882" height="768" alt="image" src="https://github.com/user-attachments/assets/ecafee3f-7969-400c-af0e-2847098c2619" />


### Convert to python code
