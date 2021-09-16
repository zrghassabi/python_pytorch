# python_pytorch examples
Based on Tutorial https://towardsdatascience.com/understanding-pytorch-with-an-example-a-step-by-step-tutorial-81fc5f8c4e8e


Example1= Linear Regression using Numpy (run on CPU) and Matplotlib

Example2= Linear Regression using Tensors (run on GPU)

Example 3= Linear Regression using nn.sequential model using torch.nn.linear(1,1) (pytorch linear model, no need to define parameters a and b in y=a+b*x)

Example 4= Linear Regression using nn.module model (Define a Class with _init_ ( includes nn.linear(1,1) and forward sections (returns nn.linear(1,1))

Example 5= 

   5-1) Generalization of Training step ( A function that get Loss, Model, Optimizer and return train step or corresponding Loss, this function will be used in training loop
   
   5_2) creating Dataset class ( it includes __init__(self), __len__(self), __get_item__(self, index), using _get_item, you load big dataset on demand) to use in Dataloader . Detaloader will create mini-batches of Data, will shuffle data. 

   5_3) Building Dataloader for test data and evaluation of model with test data

