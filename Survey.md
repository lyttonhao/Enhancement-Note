# Survey on Reference Enhancement

##  Personal Photo Enhancement Using Example Images

2010 TOG, NEEL JOSHI Microsoft Research WOJCIECH MATUSIK Disney Research EDWARD H. ADELSON MIT CSAIL and  DAVID J. KRIEGMAN University of California, San Diego

### Enhancement:

 *  global image corrections
 	*  image deblurring 
 	*  exposure and color correction
 *  face-specific enhancements
 	*  like **Liu [2007]**
 	*  >> The aligned, intrinsic prior layers are used directly for a patch- based method, and we also create eigenspaces for these layers.

### Overview:

 1. Automatically detect faces on target images and prior images. 
 2. Align and segment faces in target and prior images.
 3. Decompose images into color, texture, and lighting layers. 
 4. Perform global image corrections.
 5. Perform face-specific enhancements.

##  Personalization of Image Enhancement

2010 CVPR, Sing Bing Kang, Ashish Kapoor, Dani Lishchinski

Incorporating user preference in automatic image enhancement
Filters:
![Alt text](images/2.png )

##  Collaborative Personalization of Image Enhancement

2011 CVPR, Juan C. Caicedo, Ashish Kapoor, **Sing Bing Kang**

User identity and User preferences --> image enhancement

![Alt text](images/1.png "Overview")
Collaborative filtering --> recommender systems

## Collaborative Personalization of Image Enhancement
2014 IJCV 
  combine the above two papers

## Content-Aware Automatic Photo Enhancement
2012 CG
Liad Kaufman Dani Lischinski Michael Werman

##  Face Hallucination on Personal Photo Albums
2013 ACCV, Yuan Ren Loke, Ping Tan, and Ashraf A. Kassim

* Image selectection 
* Image alignment
* face hallucination by MRF 

## Non-Rigid Dense Correspondence with Applications for Image Enhancement
2011 TOG, Yoav HaCohen, Eli Shechtman, Dan B Goldman, Dani Lishchinski

Dense Correspondence
![Alt text](images/3.png )

compare to SIFT-Flow [Liu, 2008], Generalized PatchMatch (GPM), sparse SIFT corespondence [Lowe 2004]

applications

* local color transfer
* deblurring
* mask transder


##  Deblurring by Example using Dense Correspondence

2013 ICCV, Yoav HaCohen, Eli Shechtman, Dani Lishchinski

using a sharp reference example that contains some shared content with the blurry photo

extend non-rigid dense correspondence (NRDC)

* correspondence for blur kernel esitimation and a local prior for deconvolution
* spatically varying blur estimation

##  Deblurring Face Images with Exemplars

2014 ECCV, Jinshan Pan1, Zhe Hu2, Zhixun Su, and Ming-Hsuan Yang
[Project Page](https://eng.ucmerced.edu/people/zhu/ECCV14_facedeblur.html)

find best match example --> use its contour as salient edges for kernel estimation
