# Datasets for Identification of Gaps in the Images of Shleves in Supermarkets

## Description of the datasets
Here, we provide the annotations of the publicly available datasets: Grocery Products [1], WebMarket [2] and Grozi 120 [3] for identification of gaps in the images of shelves. We select 305,98, and 50 number of shelf images respectively from Grocery Products [1], WebMarket [2] and Grozi 120 [3], and create ground truths pecifying gap/non-gap regions. For each dataset, we randomly choose approximately 60% of these shelf images as train-set and rest 40% as test-set. The train-set includes 184, 59, and 30 number of shelf images in Grocery Products [1], WebMarket [2] and Grozi 120 [3] respectively while test-set contains 121, 39, and 20 number of images in the respective datasets.

## The paper
<b>Title:</b> - Graph-based Modelling of Superpixels for Automatic Identification of Empty Shelves in Supermarkets
<b>Authors</b>: Bikash Santra*, Udita Ghosh*, and Dipti Prasad Mukherjee, Indian Statistical Institute, Kolkata
<b>Journal</b>: Pattern Recognition

*These authors have the eaual contributions.

## Citing these gap detection datasets
If you use these datasets now, then you can cite this github repository. The BibTeX entry is the following.<br><br>
@misc{gap:datasets:2021,<br>
  Author = {Santra, Bikash and Ghosh, Udita and Mukherjee, Dipti Prasad},<br>
  Title = {Datasets for Identification of Gaps in the Images of Shleves in Supermarkets},<br>
  Year = {2021},<br>
  Publisher = {GitHub},<br>
  Journal = {GitHub repository},<br>
  Howpublished = {\url{https://github.com/gapDetection/gapDetectionDatasets}}<br>
}


## Example Images
A few example images and their corresponding masks are shown below.

### 1) GroZi-120 [1]

Image
![Alt text](./GroZi-120/Train/Images/001.jpg?raw=true "Title")

Mask
![Alt text](./001.jpg?raw=true "Title")


### 2) Grocery Products [2]

Image
![Alt text](./268_Image.jpg?raw=true "Title")

Mask
![Alt text](./268.jpg?raw=true "Title")


### 3) WebMarket [3]

Image
![Alt text](./WebMarket/Train/Images/db251.jpg?raw=true "Title")

Mask
![Alt text](./db251.jpg?raw=true "Title")

<b>References:</b></br>
[1] Marian George and Christian Floerkemeier. Recognizing products: A per-exemplar multi-label image classification approach. In European Conference on Computer Vision, pages 440–455. Springer, 2014 </br>
[2] Yuhang Zhang, Lei Wang, Richard Hartley, and Hongdong Li. Where's the weet-bix? In Asian Conference on Computer Vision, pages 800–810. Springer, 2007 </br>
[3] Michele Merler, Carolina Galleguillos, and Serge Belongie. Recognizing groceries in situ using in vitro training data. In Computer Vision and Pattern Recognition, 2007. CVPR'07. IEEE Conference on, pages 1–8. IEEE, 2007. </br>
