01 https://doi.org/10.1016/j.automatica.2014.02.015

Firstly, for Algorithm 1, the offline-policy iteration algorithm, I applied value iteration instead of policy iteration because I didn't know how the author obtained the stable control policy K1.

Secondly, for Algorithm 2, the online-policy iteration, I haven't been able to reproduce it yet due to two points that I'm not quite clear about two point. One point is that in order to ensure the Persistent Excitation (PE), it's necessary to add a probing noise to the control input. However, I don't understand what the specific form of this signal should be like. Another point is about Batch Least Squares (Batch LS) and Recursive Least Squares (Recursive LS). I think what I'm currently applying should be Batch LS, but when solving the P matrix, I encountered the problem that the matrix is non-invertible. 
