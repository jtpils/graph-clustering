# Clustering techniques in graphs and application to point cloud data

In the following we compared two techniques of **clustering** **Kmeans** and **spectral clustering**. For spectral clustering we implemented the **Normalized Spectral Clustering technique from Ng, Jordan, and Weiss** described in following reference:

> *A Tutorial on Spectral Clustering*, Ulrike von Luxburg, 2007

In **part I** we used a generative model of graphs called **mixed membership stochastic block model (MMSBM)** from reference:

> *Mixed Membership Stochastic Block models*, Edoardo M. Airoldi, David M. Blei, Stephen E. Fienberg, Eric P. Xing, 2008

We show how kmeans and spectral clustering performs in this framework

In **part II** we used the previous methods of graph clustering to perform **clustering on a point cloud data (PCD)**

Again we show how kmeans and spectral clustering performs in this framework

## Part I: mixed membership stochastic block model (MMSBM)

Here is a summarized presentation of the generative model:

<p align="center">
  <img src="img/mmsbm_gen.png" width="90%">
</p>

### low complexity graphs

We sampled MMSBM graphs with parameters:

<p align="left">
  <img src="img/mmsbm_lc.png" width="20%">
</p>

<p align="center">
  <img src="img/mmsbm_show_0-05.png" width="75%">
</p>

<p align="center">
  <img src="img/mmsbm_truth_0-05.png" width="20%">
</p>

<p align="center">
  <img src="img/mmsbm_kmeans_0-05.png" width="20%">
</p>

<p align="center">
  <img src="img/mmsbm_spectral_0-05.png" width="20%">
</p>

### medium complexity graphs

We sampled MMSBM graphs with parameters:

<p align="left">
  <img src="img/mmsbm_mc.png" width="20%">
</p>

<p align="center">
  <img src="img/mmsbm_show_0-3.png" width="85%">
</p>

<p align="center">
  <img src="img/mmsbm_truth_0-3.png" width="35%">
</p>

<p align="center">
  <img src="img/mmsbm_kmeans_0-3.png" width="35%">
</p>

<p align="center">
  <img src="img/mmsbm_spectral_0-3.png" width="85%">
</p>

## Part II: Application to Point Cloud Data


