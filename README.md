# Neural Machine Translation

## Description
Using a Transormer model for English to Spanish translation.
<br>
See ```NMT.ipynb``` for more details

### Contributor(s)
* Tate larkin

### Machine Learning Model
I used a Transformer model as described in the [Attention is All you Need](https://proceedings.neurips.cc/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf) paper. This architecture utilizes only attention mechanisms to track relationships and find patterns in data. It uses self-attention to weight the significance of each part of the input data. Inputs are embedded, positionally encoded, and sent through an encoder and decoder with multiple iterations of Multi-Head Attention layers which runs through attention mechanisms multiple times in parallel. It then uses a final point-wise network for its predictions.
<br>

Scaled Dot Product Attention and Multi-Head Attention diagrams
<p align="middle">
  <img width="300" alt="ScaledDotProductAttn" src="https://user-images.githubusercontent.com/70344865/168853068-6bbf752d-2294-4e03-9f01-55bae063268b.png">
 <img src="https://user-images.githubusercontent.com/70344865/168852860-f858a97f-0eb9-4dfe-8b7f-609a32f1db84.png" width="300"></img>
</p>

<br>

Full Model
<p align="center">
  <img src="https://user-images.githubusercontent.com/70344865/168329344-4978b250-fd0d-4a78-a280-0fb277451f74.png" width="400" height="600"></img>
</p>

## Model
<p align="center">
  <img src="https://user-images.githubusercontent.com/70344865/159397653-e090029c-9e30-4ee1-ac35-9ec3b398719a.png" width="500" height="700"></img>
</p>
