# Triangulation_Scripts
 
Triangulating the Neural Correlates of Consciousness (NCCs)

This project's goals are to:

1. Decode from EEG data from three experiments using machine learning
2. Apply temporal generalization to each experiment, showing time-relationships and staiblity of signal over time in decoding
3. Test different algorithms in pilot data and show the generalizabitlity of one experiment to the other two by applying the model from one experiment's decoding session to the other one.

In sum, this projects' goal was to show that it is feasible to use the model from one experiment to decode the other two, and therefore show that they share a common neural signal. We call this a triangulation of neural correlates. These three experiments are commonly used in consciosuness research, and the generalization between them will help us identify common Neural Correlates of Consiousness, that is, where in the brain are the sources of awareness. In this case, visual awareness.

This jupyter notebook was created by me and uses various tools to test that the Triangulation project is possible.

I ran 6 participants data through multiple pipelines, testing various algorithms and hyperparameters. In the end, all 6 participants showed significant signs of triangulation, with logistic regression being the strongest algorithm among the ones tested, including neural networks.

Here's an example of the participant with strongest's generalization across all three experiments.

![image](https://github.com/UgoBruzadin/Triangulation_Project/assets/25592470/15477e43-c802-4157-93e2-cb9e83eb48d3)

![image](https://github.com/UgoBruzadin/Triangulation_Project/assets/25592470/39104732-53e0-4eb7-a5e1-4c7e408f9193)
