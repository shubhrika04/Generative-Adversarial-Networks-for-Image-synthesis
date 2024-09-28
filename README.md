In this project, we aimed to develop an advanced image synthesis system using Generative Adversarial Networks (GANs), 
focusing on Conditional GANs (cGANs) and CycleGANs to address both paired and unpaired image-to-image translation tasks. 
We utilized the Edges2Shoes dataset for paired data tasks like sketch-to-image translation, training the cGAN model to transform shoe designs into photorealistic images. 
For unpaired data tasks, such as converting daylight urban scenes into nighttime, we employed the CycleGAN model using the Cityscapes dataset, ensuring domain adaptation without paired training data.

We meticulously optimized each model by fine-tuning hyperparameters and leveraging advanced deep learning techniques to improve the quality of image synthesis.
After analyzing the performance of both models individually, we proposed a hybrid approach to combine the strengths of both cGAN and CycleGAN, 
thereby enhancing the flexibility and accuracy of the image synthesis process. The project was implemented using Python, TensorFlow, and cloud-based platforms like Google Colab to handle the computational requirements, 
including large datasets and intensive GPU processing. The final results demonstrated significant improvements in the visual fidelity and accuracy of the generated images.
