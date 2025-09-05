# :satellite: Remote Sensing based Multi-view Datasets

> List created based on our work [*Common Practices and Taxonomy in Deep Multiview Fusion for Remote Sensing Applications*](https://ieeexplore.ieee.org/document/10418966)
---

List of remote sensing (RS) multi-view datasets for exploring multi-view fusion learning. :satellite: :earth_americas: :satellite:

| Dataset | RS views | Temporal? | Task | Region | URL | Additional URL|
|---------|----------|-----------|------|--------|-----|---------------|
GlobalGeoTree ([Mu et al.](https://arxiv.org/abs/2505.12513)) | MS optical (S2), weather, DEM, soil properties | :+1: | Image Classification | Global | https://huggingface.co/datasets/yann111/GlobalGeoTree | ... |
FLAIR-HUB ([Garioud et al.](https://arxiv.org/abs/2506.07080)) | MS optical (S2, SPOT), aerial, DEM, SAR (S1) | :-1: | Image Segmentation | France | https://huggingface.co/datasets/IGNF/FLAIR-HUB | ... |
MagicBathyNet | optical (S2, SPOT), aerial, DEM | :-1: | Classification | Cyprus/Poland | https://zenodo.org/records/10470959 | ... |
AllClear ([Zhou et al. 2024](http://arxiv.org/abs/2410.23891)) | MS optical (S2, L8, and L9), SAR (S1) | :-1: | Image Regression | Global | https://allclear.cs.cornell.edu/ | .. |
CropDeepTrans ([Barriere et al. 2024](https://www.sciencedirect.com/science/article/pii/S0034425724001214)) | MS optical (S2), metadata | :+1: | Image Classification | Netherlands and France | https://jeodpp.jrc.ec.europa.eu/ftp/jrc-opendata/DRLL/CropDeepTrans/ | .. |
MMEarth ( [Nedungadi et al. 2024](http://arxiv.org/abs/2405.02771) ) | MS optical (S2), SAR (S1), DSM (aster DEM), vegetation height, landcover, biome, ecoregion, weather (ERA5) | :-1: | None (unsupervised) | Global | https://github.com/vishalned/MMEarth-data |.. |
Fields of The World (FTW)  ([Kernel et al. 2024](https://arxiv.org/abs/2409.16252v1)) | two optical images from S2 | :-1: | Image Segmentation | Global | https://source.coop/repositories/kerner-lab/fields-of-the-world/description| .. |
CropNet Dataset ([Lin et al. 2024](https://ieeexplore.ieee.org/abstract/document/10376769)) | Optical (S2), weather | :+1: | Image Regression | USA |  https://huggingface.co/datasets/fudong03/Tiny-CropNet | .. |
SICKLE ([Sani et al. 2024](https://ieeexplore.ieee.org/abstract/document/10376769)) | MS optical (S2 and L8), Radar (S1) | :+1: | Image Regression, Segmentation | India| https://sites.google.com/iiitd.ac.in/sickle/home | .. |
GreenEarthNet ([Benson et al. 2024](https://arxiv.org/abs/2303.16198)) | MS optical (S2), weather, elevation | :+1: | Image Regression | Europe | https://github.com/earthnet2021/earthnet-minicuber | .. |
Globe230k ([Shi et al. 2023](https://spj.science.org/doi/10.34133/remotesensing.0078)) | RGB+NDVI optical (S2), DEM (NASA), SAR (S1) | :-1: | Image Segmentation | Global | https://zenodo.org/records/8429200 | .. |
Crop Yield Prediction ([Perich et al. 2023](https://doi.org/10.1016/j.fcr.2023.108824))| MS optical (S2), weather | :+1: | Pixel-wise regression | Switzerland | https://www.research-collection.ethz.ch/handle/20.500.11850/595228 | ..|
BEN-GE ([Mommert et al. 2023](https://arxiv.org/abs/2307.01741)) | MS optical (S2), SAR (S1), DSM (GLO-30), weather (ERA5) | :-1: | Image Segmentation | Europe | https://github.com/HSG-AIML/ben-ge | .. |
TreeSatAI ([Ahlswede et al. 2023](https://doi.org/10.5194/essd-15-681-2023)) | 2 MS optical (S2, UAV), SAR (S1) | :-1: | Pixel-wise Classification | Germany | https://zenodo.org/record/6780578 | https://doi.org/10.5281/zenodo.6780578 |
MDAS  ([Hu et al. 2023](https://doi.org/10.5194/essd-15-113-2023))| MS (S2) and HS (EnMAP, HySpex) optical, SAR (S1), DSM (DLR 3K) |  :-1: | Pixel-wise Classification |  Germany | https://mediatum.ub.tum.de/1657312 | https://doi.org/10.14459/2022mp1657312 |
MultiEarth  ([Cha et al. 2022](https://arxiv.org/abs/2306.04738)) | MS optical (S2 and L8), SAR (S1) | :+1: | Multiple Tasks | Global | https://sites.google.com/view/rainforest-challenge/multiearth-2023 | .. |
Satlas ([Bastani et al. 2022](https://arxiv.org/abs/2211.15660)) | MS optical (S2 and NAIP) | :+1: | Multiple Tasks | Global | https://github.com/allenai/satlas | .. |
CloudSEN12 ([Aybar et al. 2022](https://doi.org/10.1038/s41597-022-01878-2)) | MS optical (S2), SAR (S1), DSM (MERIT) | :-1: | Image Segmentation | Global | https://cloudsen12.github.io/ | .. |       
WHU-OPT-SAR ([Li et al. 2022](https://doi.org/10.1016/j.jag.2021.102638)) | MS Optical (G1), SAR (G3) | :-1: | Image Segmentation | China | https://github.com/AmberHen/WHU-OPT-SAR-dataset | .. |
SEN12MS-CR-TS ([Ebel et al. 2022](https://doi.org/10.1109/TGRS.2022.3146246)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | Global | https://patricktum.github.io/cloud_removal/ | https://patricktum.github.io/cloud_removal/sen12mscrts/ |
PASTIS-R ([Garnot et al. 2022](https://doi.org/10.1016/j.isprsjprs.2022.03.012)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | France | https://github.com/VSainteuf/pastis-benchmark | .. |
Ombria ([Drakonakis et al. 2022](https://doi.org/10.1109/JSTARS.2022.3155559)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | Global | https://github.com/geodrak/OMBRIA | .. |
DynamicEarthNet ([Toker et al. 2022](https://doi.org/10.1109/CVPR52688.2022.02048))| 2 MS optical (S2, PlanetFusion), SAR (S1) | :+1: | Image Segmentation | Global | https://mediatum.ub.tum.de/1483140 | https://doi.org/10.14459/2018mp1483140 |
MultiSenGE ([Wenger et al. 2022](https://isprs-annals.copernicus.org/articles/V-3-2022/635/2022/)) | MS optical (S2), SAR (S1) | :+1: | Image Segmentation | France | https://zenodo.org/records/6375466 | .. |
RapidAI4EO ([Marchisio et al. 2021](https://ieeexplore.ieee.org/abstract/document/9883198)) | MS optical (S2), MS optical (Planet) | :+1: | Image segmentation | Europe | https://rapidai4eo.radiant.earth/ | .. |
CropHarvest ([Tseng et al. 2021](https://openreview.net/forum?id=JtjzUXPEaCu)) | MS optical+NDVI (S2), SAR (S1), weather (ERA5), DSM (SRTM) |  :+1: | Pixel-wise Classification | Global | https://github.com/nasaharvest/cropharvest | .. |
EarthNet ([Requena et al. 2021](https://doi.org/10.1109/CVPRW53098.2021.00124)) | MS optical (S2), weather (E-OBS), DSM (EUDEM) | :+1: | Image Regression | Europe | https://www.earthnet.tech/ | https://www.earthnet.tech/en21x/download/ |
BigEarthNet-MM ([Sumbul et al. 2021](https://10.1109/MGRS.2021.3089174)) | MS optical (S2), SAR (S1) | :-1: | Multi-label Classification | Europe | https://bigearth.net/ | .. |
LandCoverNet ([Alemohammad et al. 2021](https://doi.org/10.34911/rdnt.d2ce8i)) | 2 MS optical (S2, L8), SAR (S1) | :+1:  | Image Segmentation | Global | https://doi.org/10.34911/rdnt.d2ce8i | .. |
Dams ([Donchyts et al. 2021](https://ui.adsabs.harvard.edu/abs/2021AGUFMGC43D..05D/abstract)) | MS optical (S2) including VI, SAR (S1), DSM | :-1: | Image Segmentation | Global | https://www.kaggle.com/datasets/gdonchyts/global-dams-from-space | .. |
LFMC from SAR ([Rao et al](https://doi.org/10.1016/j.rse.2020.111797)) | MS Optical (L8), SAR (S1), weather, elevation, soil | :+1: |  Pixel-wise Regression | USA | https://github.com/kkraoj/lfmc_from_sar | https://beta.source.coop/repositories/stanford/sar-moisture-conent/description/ |
ForestNet ([Irvin et al. 2020](https://arxiv.org/abs/2011.05479)) | MS optical (L8), DSM (SRTM), weather (NCEP) | :+1: | Image Segmentation | Indonesia | https://stanfordmlgroup.github.io/projects/forestnet/ |.. |
AI4Food ([Kondmann et al. 2021](https://openreview.net/forum?id=uUa4jNMLjrL)) | 2 MS optical (S2, PlanetFusion), SAR (S1) | :+1: | Image Classification | Germany | https://doi.org/10.34911/rdnt.z9y7vu | .. |
Sen1Floods11 ([Bonafilia et al. 2020](https://doi.org/10.1109/CVPRW50498.2020.00113)) | MS optical (S2), SAR (S1) | :-1: | Image Segmentation | Global | https://github.com/cloudtostreet/Sen1Floods11 | .. |
So2Sat LCZ42 ([Zhu et al. 2020](https://doi.org/10.1109/MGRS.2020.2964708)) | MS Optical (S2), SAR (S1) | :-1: | Image Classification | Global | https://mediatum.ub.tum.de/1483140 | https://doi.org/10.14459/2018mp1483140 |
CrisisMMD | optical, text (tweets) | :-1: | Classification | Global | https://crisisnlp.qcri.org/crisismmd | ... |
ISPRS 2D Challenge  | UAV-based: MS optical, DSM |  :-1: | Image Segmentation | Germany | https://www.isprs.org/education/benchmarks/UrbanSemLab | .. |
MSLCC | MS optical (S2), SAR (S1) | :-1: | Image Segmentation | Germany | https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-12760/22294_read-51180 | ..|
University of Houston | UAV-based: HS and RGB optical, DSM (LiDAR) | :-1: | Image Segmentation | USA | https://hyperspectral.ee.uh.edu/?page_id=1075 | .. |

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
