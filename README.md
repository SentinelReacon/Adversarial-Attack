# Adversarial-Attack

This project familiarizes the domain of Adversarial Machine learning and the attacks that can be performed on the machine learning model to fool it. 

## Dataset
The dataset used in this project was facial images from a bunch of students. The dataset is not publicly available but a similar dataset can be used whose structure is as follows 



    folder 

        -- class 1
            -- image 1
            -- image 2
            .
            .
            -- image n
        -- class 2
            -- image 1
            .
            .
        .
        .
        -- class n

Train a CNN model using your own dataset, save its weights and then add paths to those dataset and model weights in the adversarial attack notebook. This will train the adversarial perturbation which would make the model misclassify the given inputs.