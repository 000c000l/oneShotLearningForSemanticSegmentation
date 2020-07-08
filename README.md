# oneShotLearningForSemanticSegmentation

This repo contains the code from this paper:
  
  https://arxiv.org/pdf/1803.09597v2.pdf#cite.Lake2015

To generate the cluttered omniglot dataset:
  
    run "get_omniglot.ipynb" 
  
    then run "get_dataset.ipynb"
  
  This will create 5 datasets:
  
    1. train for training
    
    2. test-train for testing the model normal way
    
    3. test-oneShot for testing the model in oneShot learning way
    
    4. val-train for validation during the training
    
    5. val-oneShot for validation during the oneShot learning
    
  To train the network:
  
         run upto the 2nd cell for siamese-u-net.ipynb
      
  To test the network:
  
         run the 3rd cell of the same siamese-u-net.ipynb after training the network
         
  
