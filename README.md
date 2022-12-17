# FloatAquacultureAreaDataset
A GF-1 remote sensing dataset of year 2017 in LianYunGang, China.
# Dataset Link

# Title
Reverse Attention Dual-Stream Network for Raft Laver Aquaculture Areas Recognition from GF-1 Remote Sensing Images
# Abstract
Extraction of laver aquaculture areas from remote sensing images is very important for laver aquaculture monitoring and scientific management. However, due to the large differences in spectral features of laver aquaculture areas caused by factors such as different growth stages and harvesting conditions, the traditional extraction methods of laver aquaculture areas still face great challenges. In this paper, a Reverse Attention Dual-stream Network (RADNet) is proposed for the extraction of laver aquaculture areas with weak spectral responses by comprehensively considering both the aquaculture boundary and surrounding sea background information. RADNet consists of a boundary stream and a segmentation stream. Considering the weaker spectral responses of some laver aquaculture areas, we introduce a reverse attention module (RAM) in the segmentation stream to amplify the weaker responses of inapparent laver aquaculture areas. To suppress the response of non-boundary details in the boundary stream, we design a boundary attention module (BAM), which is guided by high-level semantics from the segmentation stream. The structure information of the laver aquaculture area learnt from the boundary stream will be fed back to the segmentation stream through a specially designed boundary guidance structure. Based on the GF-1 multispectral remote sensing images in the eastern coast of Lianyungang, China, the laver aquaculture area extraction is studied. Experimental results show that the proposed RADNet model performs better in extracting inapparent laver aquaculture areas compared to state-of-the-art models.
# Dataset Description
This dataset contains 3400 256*256 images for training and 760 for validation and testing. Note that the images in the training set are normalised using the maximum-minimum method.
# Dataset Process
Note that after processing, the label will be in 0-1, where 1 stands for aquaculture area, 0 stands for seawayer. In addition, we have additionally provided ground truth maps of the aquaculture area boundaries, with 0 stands seawater and 1 stands the boundary.
