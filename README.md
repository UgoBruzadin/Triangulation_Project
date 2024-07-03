# Triangulation_Scripts
 
Triangulating the Neural Correlates of Consciousness (NCCs)

This project's goals are to:

1. Decode from EEG data from three experiments using machine learning
2. Apply temporal generalization to each experiment, showing time-relationships and staiblity of signal over time in decoding
3. Test different algorithms in pilot data and show the generalizabitlity of one experiment to the other two by applying the model from one experiment's decoding session to the other one.

In sum, this projects' goal was to show that it is feasible to use the model from one experiment to decode the other two, and therefore show that they share a common neural signal. We call this a triangulation of neural correlates. These three experiments are commonly used in consciosuness research, and the generalization between them will help us identify common Neural Correlates of Consiousness, that is, where in the brain are the sources of awareness. In this case, visual awareness.

This jupyter notebook was created by me and uses various tools to test that the Triangulation project is possible.

I ran 6 participants data through multiple pipelines, testing various algorithms and hyperparameters. In the end, all 6 participants showed significant signs of triangulation, with logistic regression being the strongest algorithm among the ones tested, including neural networks.

Here's an example of the participant with strongest's generalization across all three experiments. Significance was tested against boostrapped random chance, controlling for multiple-comparisons.

![image](https://github.com/UgoBruzadin/Triangulation_Project/assets/25592470/73be9f79-d780-48c4-971b-476150e885ab)

