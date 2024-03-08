# :satellite: Remote Sensing based Multi-view Datasets
List of remote sensing (RS) multi-view datasets for exploring multi-view fusion learning. :satellite: :earth_americas: :satellite:

This is a complementary source used in the following paper:  
```
Common Practices and Taxonomy in Deep Multi-view Fusion for Remote Sensing Applications
```

| Dataset | RS views | Temporal? | Task | Region | URL | Additional URL|
|---------|----------|-----------|------|--------|-----|---------------|
University of Houston | UAV-based: HS and RGB optical, DSM (LiDAR) | :-1: | Image Segmentation | USA | https://hyperspectral.ee.uh.edu/?page_id=1075 | .. |
MSLCC | MS optical (S2), SAR (S1) | :-1: | Image Segmentation | Germany | https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-12760/22294_read-51180 | ..|
ISPRS 2D Challenge  | UAV-based: MS optical, DSM |  :-1: | Image Segmentation | Germany | https://www.isprs.org/education/benchmarks/UrbanSemLab | .. |
So2Sat LCZ42 ([Zhu et al. 2020](https://doi.org/10.1109/MGRS.2020.2964708)) | MS Optical (S2), SAR (S1) | :-1: | Image Classification | Global | https://mediatum.ub.tum.de/1483140 | https://doi.org/10.14459/2018mp1483140 |
Sen1Floods11 ([Bonafilia et al. 2020](https://doi.org/10.1109/CVPRW50498.2020.00113)) | MS optical (S2), SAR (S1) | :-1: | Image Segmentation | Global | https://github.com/cloudtostreet/Sen1Floods11 | .. |
AI4Food ([Kondmann et al. 2021](https://openreview.net/forum?id=uUa4jNMLjrL)) | 2 MS optical (S2, PlanetFusion), SAR (S1) | :+1: | Image Classification | Germany | https://doi.org/10.34911/rdnt.z9y7vu | .. |
ForestNet ([Irvin et al. 2020](https://arxiv.org/abs/2011.05479)) | MS optical (L8), DSM (SRTM), weather (NCEP) | :+1: | Image Segmentation | Indonesia | https://stanfordmlgroup.github.io/projects/forestnet/ |.. |
Dams ([Donchyts et al. 2021](https://ui.adsabs.harvard.edu/abs/2021AGUFMGC43D..05D/abstract)) | MS optical (S2) including VI, SAR (S1), DSM | :-1: | Image Segmentation | Global | https://www.kaggle.com/datasets/gdonchyts/global-dams-from-space | .. |
LandCoverNet ([Alemohammad et al. 2021](https://doi.org/10.34911/rdnt.d2ce8i)) | 2 MS optical (S2, L8), SAR (S1) | :+1:  | Image Segmentation | Global | https://doi.org/10.34911/rdnt.d2ce8i | .. |
BigEarthNet-MM ([Sumbul et al. 2021](https://10.1109/MGRS.2021.3089174)) | MS optical (S2), SAR (S1) | :-1: | Multi-label Classification | Europe | https://bigearth.net/ | .. |
EarthNet ([Requena et al. 2021](https://doi.org/10.1109/CVPRW53098.2021.00124)) | MS optical (S2), weather (E-OBS), DSM (EUDEM) | :+1: | Image Regression | Europe | https://www.earthnet.tech/ | https://www.earthnet.tech/en21x/download/ |
CropHarvest ([Tseng et al. 2021](https://openreview.net/forum?id=JtjzUXPEaCu)) | MS optical+NDVI (S2), SAR (S1), weather (ERA5), DSM (SRTM) |  :+1: | Pixel-wise Classification | Global | https://github.com/nasaharvest/cropharvest | .. |
DynamicEarthNet ([Toker et al. 2022](https://doi.org/10.1109/CVPR52688.2022.02048))| 2 MS optical (S2, PlanetFusion), SAR (S1) | :+1: | Image Segmentation | Global | https://mediatum.ub.tum.de/1483140 | https://doi.org/10.14459/2018mp1483140 |
Ombria ([Drakonakis et al. 2022](https://doi.org/10.1109/JSTARS.2022.3155559)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | Global | https://github.com/geodrak/OMBRIA | .. |
PASTIS-R ([Garnot et al. 2022](https://doi.org/10.1016/j.isprsjprs.2022.03.012)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | France | https://github.com/VSainteuf/pastis-benchmark | .. |
SEN12MS-CR-TS ([Ebel et al. 2022](https://doi.org/10.1109/TGRS.2022.3146246)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | Global | https://patricktum.github.io/cloud_removal/ | https://patricktum.github.io/cloud_removal/sen12mscrts/ |
WHU-OPT-SAR ([Li et al. 2022](https://doi.org/10.1016/j.jag.2021.102638)) | MS Optical (G1), SAR (G3) | :-1: | Image Segmentation | China | https://github.com/AmberHen/WHU-OPT-SAR-dataset | .. |
CloudSEN12 ([Aybar et al. 2022](https://doi.org/10.1038/s41597-022-01878-2)) | MS optical (S2), SAR (S1), DSM (MERIT) | :-1: | Image Segmentation | Global | https://cloudsen12.github.io/ | .. |       
Satlas ([Bastani et al. 2022](https://arxiv.org/abs/2211.15660)) | MS optical (S2 and NAIP) | :+1: | Multiple Tasks | Global | https://github.com/allenai/satlas | .. |
MultiEarth  ([Cha et al. 2022](https://arxiv.org/abs/2306.04738)) | MS Optical (S2 and L8), SAR (S1) | :+1: | Multiple Tasks | Global | https://sites.google.com/view/rainforest-challenge/multiearth-2023 | .. |
MDAS  ([Hu et al. 2023](https://doi.org/10.5194/essd-15-113-2023))| MS (S2) and HS (EnMAP, HySpex) optical, SAR (S1), DSM (DLR 3K) |  :-1: | Pixel-wise Classification |  Germany | https://mediatum.ub.tum.de/1657312 | https://doi.org/10.14459/2022mp1657312 |
TreeSatAI ([Ahlswede et al. 2023](https://doi.org/10.5194/essd-15-681-2023)) | 2 MS optical (S2, UAV), SAR (S1) | :-1: | Pixel-wise Classification | Germany | https://zenodo.org/record/6780578 | https://doi.org/10.5281/zenodo.6780578 |
BEN-GE ([Mommert et al. 2023](https://arxiv.org/abs/2307.01741)) | MS optical (S2), SAR (S1), DSM (GLO-30), weather (ERA5) | :-1: | Image Segmentation | Europe | https://github.com/HSG-AIML/ben-ge | .. |

* The *RS Views* column contains the views (and source where it was obtained), *Temporal?* column indicates if the labels have a temporal scope. 

> Feel free to ask me to update some content! 

---

Some abbrevations
| Abbrevation | name |
|--- | --- |
| DSM | Digital Surface Map |
| EnMAP | Environmental Mapping and Analysis Program |
| G1 | Gaofen-1 |
| G3 | Gaofen-3 |
| L7 | Landsat-7 |
| L8 | Landsat-8 |
| NAIP | National Agriculture Imagery Program |
| NCEP | National Centers for Environmental Prediction |
| S1 | Sentinel-1 |
| S2 | Sentinel-2 |
| SRTM | Shuttle Radar Topography Mission | 
| UAV | Unnamed Aerial Vehicle |