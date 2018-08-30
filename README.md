# FS-BCC
Bayesian Chain Classifier (BCC) presented by See Zaragoza et al. "Bayesian Classifier Chains for Multi-dimensional Classification. IJCAI 2011. It is an algorithm for multilabel classification task.
This project implementes Feature Selection in the original algorithm.
The source code can be integrate in MEKA following instruction below.
##Prerequisites
You need to donwload MEKA source code avidable in https://github.com/Waikato/meka.
Import the Maven project in Eclipse IDE or similar.
##Integrate
* Donwload this repository
* Replace the file meka/src/main/java/meka/classifiers/multilabel/cc/CNode.java for CNode.java
* Add the file FSBCC.java in the folder meka/src/main/java/meka/classifiers/multilabel/
* For more help follow [Tutorial](http://waikato.github.io/meka/documentation/#meka-tutorial) of MEKA.
