# MFIFB：Multi-focus Image Fusion Benchmark

This is the official webpage for MFIFB. To the best of our knowledge, MFIFB is the first (and the only one to date) benchmark in the field of multi-focus image fusion (MFIF), aiming to provide a platform to perform fair and comprehensive performance comparision of MFIF algorithms. Currently, **105 image pairs, 30 fusion algorithms and 20 evaluation metrics** are integrated in MFIFB, which can be utilize to compare performances. All the fusion results are currently made available that can be used by users directly.

For more details, please refer to: 
 
**Multi-focus Image Fusion: A Benchmark**  
Xingchen Zhang.  
From: Imperial College London  
Contact: xingchen.zhang@imperial.ac.uk  
[[Download paper](https://arxiv.org/abs/2005.01116)]

### Abstract
Multi-focus image fusion (MFIF) has attracted considerable interests due to its numerous applications. While much progress has been made in recent years with efforts on developing various MFIF algorithms, some issues significantly hinder the fair and comprehensive performance comparison of MFIF methods, such as the lack of large-scale test set and the random choices of objective evaluation metrics in the literature. To solve these issues, this paper presents a multi-focus image fusion benchmark (MFIFB) which consists a test set of 105 image pairs, a code library of 30 MFIF algorithms, and 20 evaluation metrics. MFIFB is the first benchmark in the field of MFIF and provides the community a platform to compare MFIF algorithms fairly and comprehensively. Extensive experiments have been conducted using the proposed MFIFB to understand the performance of these algorithms. By analyzing the experimental results, effective MFIF algorithms are identified. More importantly, some observations on the status of the MFIF field are given, which can help to understand this field better.

### Methods integrated
1. ASR [1]
2. BFMF [2]
3. BGSC [3]
4. CBF [4]
5. CNN [5]
6. CSR [6]
7. DCT_Corr [7]
8. DCT_EOL [7]
9. DPRL [8]
10. DSIFT [9]
11. DWTDE [10]
12. ECNN [11]
13. GD [12]
14. GFDF [13]
15. GFF [14]
16. IFCNN [15]
17. IFM [16]
18. MFM [17]
19. MGFF [18]
20. MST_SR [19]
21. MSVD [20]
22. MWGF [21]
23. NSCT_SR [19]
24. PCANet [22]
25. QB [23]
26. PR_SR [19]
27. SESF [24]
28. SFMD [25]
29. SVDDCT [26]
30. TF [27]

### Evaluation metrics integrated
1. Avgerage gradient
2. Cross entropy
3. Edge intensity
4. Entropy
5. NMI
6. FMI
7. PSNR
8. Qab/f
9. Qcb
10. Qcv
11. Qc
12. Qncie
13. Qp
14. Qw
15. Qy
16. Spatial frequency
17. SD 
18. TE
19. SSIM
20. VIF


### Examples of fused images
![](https://github.com/xingchenzhang/MFIFB/blob/master/result-lytro-19.jpg)

### Citation
If you find these results and use these results in your work, please consider citing:
    
    @misc{zhang2020multifocus,    
    title={Multi-focus Image Fusion: A Benchmark},
    author={Xingchen Zhang},
    year={2020},
    eprint={2005.01116},
    archivePrefix={arXiv},
    primaryClass={cs.CV}}

### References
[1] Y. Liu and Z. Wang, “Simultaneous image fusion and denoising with adaptive sparse representation,” IET Image
Processing, vol. 9, no. 5, pp. 347–357, 2014.  
[2] Y. Zhang, X. Bai, and T. Wang, “Boundary finding based
multi-focus image fusion through multi-scale morphological focus-measure,” Information fusion, vol. 35, pp.
81–101, 2017.  
[3] J. Tian, L. Chen, L. Ma, and W. Yu, “Multi-focus image fusion using a bilateral gradient-based sharpness
criterion,” Optics communications, vol. 284, no. 1, pp.80–87, 2011.  
[4] B. K. Shreyamsha Kumar. Image fusion based on pixel significance using cross bilateral filter. Signal, Image and Video
Processing, 9(5):1193–1204, Jul 2015.   
[5] Y. Liu, X. Chen, H. Peng, and Z. Wang, “Multi-focus image fusion with a deep convolutional neural network,”
Information Fusion, vol. 36, pp. 191–207, 2017.  
[6] Y. Liu, X. Chen, R. K. Ward, and Z. J. Wang, “Image fusion with convolutional sparse representation,” IEEE
signal processing letters, vol. 23, no. 12, pp. 1882–1886, 2016.  
[7] M. Amin-Naji and A. Aghagolzadeh, “Multi-focus image fusion in dct domain using variance and energy of
laplacian and correlation coefficient for visual sensor networks,” Journal of AI and Data Mining, vol. 6, no. 2, pp. 233–250, 2018.  
[8] J. Li, X. Guo, G. Lu, B. Zhang, Y. Xu, F. Wu, and D. Zhang, “Drpl: Deep regression pair learning for multi-focus image fusion,” IEEE Transactions on Image Processing, vol. 29, pp. 4816–4831, 2020.  
[9] Y. Liu, S. Liu, and Z. Wang, “Multi-focus image fusion with dense sift,” Information Fusion, vol. 23, pp. 139–155, 2015.  
[10] Y. Liu and Z. Wang, “Multi-focus image fusion based on wavelet transform and adaptive block,” Journal of image and graphics, vol. 18, no. 11, pp. 1435–1444, 2013.   
[11] M. Amin-Naji, A. Aghagolzadeh, and M. Ezoji, “Ensemble of CNN for Multi-Focus Image Fusion,” Information Fusion, vol. 51, no. February, pp. 201–214, 2019.  
[12] S. Paul, I. S. Sevcenco, and P. Agathoklis, “Multiexposure and multi-focus image fusion in gradient domain,” Journal of Circuits, Systems and Computers, vol. 25, no. 10, p. 1650123, 2016.  
[13] X. Qiu, M. Li, L. Zhang, and X. Yuan, “Guided filterbased multi-focus image fusion through focus region detection,” Signal Processing: Image Communication, vol. 72, pp. 35–46, 2019.      
[14] S. Li, X. Kang, and J. Hu. Image fusion with guided filtering. IEEE Transactions on Image
processing, 22(7):2864–2875, 2013.  
[15] Y. Zhang, Y. Liu, P. Sun, H. Yan, X. Zhao, and L. Zhang, “IFCNN: A general image fusion framework based on convolutional neural network,” Information Fusion, vol. 54, no. August 2018, pp. 99–118, 2020.  
[16] S. Li, X. Kang, J. Hu, and B. Yang, “Image matting for fusion of multi-focus images in dynamic scenes,” Information Fusion, vol. 14, no. 2, pp. 147–162, 2013.  
[17] J. Ma, Z. Zhou, B. Wang, and M. Dong, “Multi-focus image fusion based on multi-scale focus measures and generalized random walk,” in 2017 36th Chinese Control Conference (CCC). IEEE, 2017, pp. 5464–5468.    
[18] D. P. Bavirisetti, G. Xiao, J. Zhao, R. Dhuli, and G. Liu. Multi-scale guided image and video
fusion: A fast and efficient approach. Circuits, Systems, and Signal Processing, 38(12):5576–5605, Dec 2019.  
[19] Y. Liu, S. Liu, and Z. Wang. A general framework for image fusion based on multi-scale transform and
sparse representation. Information Fusion, 24:147–164, 2015.      
[20] VPS Naidu. Image fusion technique using multi-resolution singular value decomposition. Defence Science Journal,
61(5):479–484, 2011.  
[21] Z. Zhou, S. Li, and B. Wang, “Multi-scale weighted gradient-based fusion for multi-focus images,” Information Fusion, vol. 20, pp. 60–72, 2014.  
[22] X. Song and X.-J. Wu, “Multi-focus Image Fusion with PCA Filters of PCANet,” in IAPR Workshop on Multimodal Pattern Recognition of Social Signals in HumanComputer Interaction. Springer, 2018, pp. 1–17.  
[23] X. Bai, Y. Zhang, F. Zhou, and B. Xue, “Quadtreebased multi-focus image fusion using a weighted focusmeasure,” Information Fusion, vol. 22, pp. 105–118, 2015.  
[24] B. Ma, X. Ban, H. Huang, and Y. Zhu, “Sesf-fuse: An unsupervised deep model for multi-focus image fusion,” arXiv preprint arXiv:1908.01703, 2019.  
[25] H. Li, L. Li, and J. Zhang, “Multi-focus image fusion based on sparse feature matrix decomposition and morphological filtering,” Optics Communications, vol. 342, pp. 1–11, 2015.  
[26] M. Amin-Naji, P. Ranjbar-Noiey, and A. Aghagolzadeh, “Multi-focus image fusion using singular value decomposition in dct domain,” in 2017 10th Iranian Conference on Machine Vision and Image Processing (MVIP). IEEE, 2017, pp. 45–51.  
[27] J. Ma, Z. Zhou, B. Wang, L. Miao, and H. Zong, “Multifocus image fusion using boosted random walks-based algorithm with two-scale focus maps,” Neurocomputing, vol. 335, pp. 9–20, 2019.