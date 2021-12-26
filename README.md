# TLRM
In this research, we present a problem of queuing time aware next POI recommendation and demonstrate how it is non-trivial to both recommend a next POI and simultaneously predict its queuing time. To solve this problem, we propose a multi-task, multi head attention transformer model called TLR-M. The model recommends next POIs to the target users and predicts queuing time to access the POIs simultaneously. By utilizing multi-head attention, the TLR-M model can integrate long range dependencies between any two POI visit efficiently and evaluate their contribution to select next POIs and to predict queuing time.  To use this code in your research work please cite the following paper.  Sajal Halder, Kwan Hui Lim, Jeﬀrey Chan, and Xiuzhen Zhang. Transformer-based multi-task learning for queuing time aware next poi recommendation. In Paciﬁc-Asia Conference on Knowledge Discovery and Data Mining, pages 510–523. Springer, 2021, DOI: https://doi.org/10.1007/978-3-030-75765-6_41


# Implemtation Details
In this TLR-M model implemenation, we have used transformer based attention machanism that has been implemented in python programing language. We use tensorflow, keras and attention machanism. 

Required Packages:

tensorflow: 2.4.1

pandas: 1.2.2

Here we added only one dataset (Melbourne). If you are interested to know about more datasets email at sajal.halder@student.rmit.edu.au or sajal.csedu01@gmail.com
