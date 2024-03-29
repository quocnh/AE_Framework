# Empirical Evaluation of Autoencoder Models for Anomaly Detection in Packet-based NIDS

This repository contains the code for the project "Empirical Evaluation of Autoencoder Models for Anomaly Detection in Packet-based NIDS". The code and proposed framework are provided that can be used to reproduce our work for anomaly detection using Autoencoder in packet-based NIDS.

## Dataset
https://usf.box.com/s/lq5f9slvrazlxzz8mcpgwh5orphwjput

## Paper abstract

**<p align="center">Figure 1: Network traffic anomaly detection framework using autoencoders.</p>**
<p align="center">
<img src="https://github.com/quocnh/AE_Framework/blob/main/AE_frame3.png"/>
</p>


Anomaly detection is critical for network security. Unsupervised learning models trained on benign network traffic data aim to detect anomalies without relying on attack data sets. Autoencoder-based models have emerged as a promising approach for detecting anomalies in network intrusion data. While autoencoder models have predominantly been utilized in flow-based approaches, which are suitable for offline analysis, there is a notable gap in research concerning unsupervised learning, particularly autoencoder-based techniques, for packet-based network intrusion detection. Packet-based network intrusion detection systems (NIDS) enable real-time detection at a granular level, making this area of investigation crucial.

This paper compares autoencoder models for anomaly detection in packet-based NIDS. A methodological framework is presented for implementing an autoencoder-based network intrusion detection mechanism with packet data. A novel reconstruction error metric is proposed for autoencoders, which is evaluated at different threshold levels to compare the detection accuracies of network traffic anomalies. The effectiveness of autoencoder models is demonstrated on various network attacks and adversarial samples obtained from publicly available network intrusion data sets. The analysis highlights the strengths and limitations of different autoencoders for network traffic anomaly detection. The insights obtained from the empirical evaluation offer valuable guidance to researchers and practitioners aiming to develop an autoencoder-based network intrusion detection mechanism.

## Project Structure
```
|---- Source_Code
|---- Hyperparameter_Tuning
|---- README.md
```
## Citation
If you find this repository useful in your research, please cite the following articles as: 

```
@article{
  title={Empirical Evaluation of Autoencoder Models for Anomaly Detection in Packet-based NIDS},
  author={Hore, Soumyadeep; Nguyen, Quoc; Xu, Yulun; Shah, Ankit; Bastian, Nathaniel; Le, Trung},
  journal={The 2023 6th IEEE Conference on Dependable and Secure Computing (IEEE DSC 2023)},
  year={2023}
}
https://doi.org/10.36227/techrxiv.24043608.v1
```
