# Intrusion-Detection-using-Machine-Learning

In this repository, I have applied various machine learning algorithms to detect intrusion in a network. The dataset that I considered for classification problem is "KDDCUP99" which is the dataset for intrusion detection in a computer network. 
The dataset is classified in various types of attacks. This dataset is taken from http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html.
For reference I have read and considered "A Fast Probing Detection Method using Hybrid Machine Learning Algorithms" research paper.

The dataset contains the information of traffic in a computer network system. The dataset has most of the data for normal traffic. There are majorly 4 types of attacks as the labels in this dataset. Those are denial-of-service (DOS) attack, unauthorized access from a remote machine (R2L) attack, unauthorized access to local superuser (root) privileges (U2R), surveillance and other probing attacks.

These attacks are further classified in the following types:

1) The attacks black, land, neptune, pod, smurf and teardrop are the types of DOS attacks.
2) The attacks like buffer_overflow, loadmodule, perl, rootkit are the types of U2R attacks.
3) ftp_write, guess_passwd, imap, multihop, phf, spf, warezclient, warezmaster are the types of R2L attacks.
4) nmap, ipsweep, portsweep, satan are the probing attacks.

As discussed above, since the dataset has more than 2 classes, the algorithms like Logistic Regression, Neural Nets and deep learning algorithms are applied to create the models. Accuracy of each of these algorithms are discussed in detail in ipython notebooks.

It is interesting to note that this project is developed without using any high-level libraries like Tensorflow, Keras or Scikit-learn. 
Since this project is developed as a part of classroom assignment, you may find discussion about other dataset like "Rain in Australia", you may ignore this if you are looking specifically for "Intrusion Detection."
