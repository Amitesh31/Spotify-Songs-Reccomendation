# Spotify_GCN

The increasing demand for personalized music experiences has led to the development of ad-
vanced recommendation systems. This project focuses on designing a Spotify Songs Recommenda-
tion System leveraging Graph Neural Networks (GNNs), including LightGCN and SAGEConv, to
predict playlist-track relationships effectively. By utilizing the Spotify Million Playlist Dataset, we
represent user-song interactions as a bipartite graph, applying K-core analysis to reduce compu-
tational complexity while preserving critical structural information. The system optimizes recom-
mendations using Bayesian Personalized Ranking (BPR) Loss, ensuring precise ranking of relevant
tracks. Our approach balances efficiency and representation richness, with LightGCN providing
scalability for large datasets and SAGEConv enabling nuanced neighborhood aggregations. The
evaluation metrics, Recall@K and ROC-AUC, demonstrate the effectiveness of the proposed mod-
els, with SAGEConv outperforming LightGCN in capturing user preferences.


## The Models that we used for our project were: 
1. LightGCN

![Diagram of the project](lightgcn.png "Project Diagram")

2. SageCONV

![Diagram of the project](sageConv.PNG "Project Diagram")



Here were our results: 
1. ROC_AUC
   
![Diagram of the project](ROC_AUC.png "Project Diagram")

2. Training Loss
 
![Diagram of the project](Training_loss.png "Project Diagram")

3. Recall @ K vs K

![Diagram of the project](Recall@k_vs_k.png "Project Diagram")

4. Recall by Number of Epochs
   
![Diagram of the project](Recall@Kforepochs.png "Project Diagram")
