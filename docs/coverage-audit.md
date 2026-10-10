# Historical coverage audit

Checked on **2026-10-10**. This audit supplements the earlier 2025-onward update with papers published through 2024.

## Result

Added **46 entries**: 17 main-conference non-DL, 6 main-conference DL, 16 Miscellaneous non-DL, and 7 Miscellaneous DL. Of these, 12 are from 2023 and 8 from 2024. Two duplicate preprint rows were removed, for a net increase of 44 entries. Earlier 2025-onward additions were preserved.

## Search scope

- Title screening of [CVF open-access proceedings](https://openaccess.thecvf.com/): CVPR 2013-2024, ICCV 2013/2015/2017/2019/2021/2023, and WACV 2020-2024 (23 conference editions). CVPR 2018-2020 and ICCV 2019 were checked through their daily lists; their older index pages do not support `day=all`.
- Title screening of the [ECVA proceedings archive](https://www.ecva.net/papers.php): ECCV 2018/2020/2022/2024. No additional matching-title omissions were found in these four editions.
- Targeted searches of ECCV before 2018, SIGGRAPH/SIGGRAPH Asia, AAAI, NeurIPS, journals, workshops, surveys, and author publication/project pages. These venues were not screened edition by edition.
- Backward searches for foundational reflection separation, shape reconstruction, reflectance, thermal imaging, and dehazing papers. Confirmed additions extend back to 1990.
- Search terms included American and British spellings: polarization/polarisation, polarized/polarised, polarizing/polarising, polarimetric, ellipsometry, Stokes, and Mueller. Geometric polar coordinates, epipolar geometry, neural-network polarization/pruning, and fluid-mechanical Stokes equations were excluded.

The proceedings screen found **10 missing papers**: 8 CVPR, 1 ICCV, and 1 WACV. Each retained candidate was checked against its abstract, paper, publisher record, or author/institutional record. Repo cells contain author-provided resources when verified; an empty cell does not mean code is unavailable.

## Classification and metadata corrections

- Moved **Polarimetric Monocular Dense Mapping Using Relative Deep Depth Prior** to Miscellaneous DL: the [paper](https://arxiv.org/html/2102.05212v1) explicitly uses a neural-network depth estimate to disambiguate polarization cues.
- Moved **A Reconfigurable Camera Add-On...** to the main non-DL list: the [author project](https://resources.mpi-inf.mpg.de/KaleidoCam/) identifies it as a SIGGRAPH 2013 technical paper.
- Moved ICIP 2021 **Deep Snapshot HDR Reconstruction...** and ICIP 2022 **Two-Step Color-Polarization Demosaicking Network** to Miscellaneous DL, consistent with the stated conference grouping. Added the [TCPDNet code and data](https://github.com/ntvy95/TCPDNet).
- Removed duplicate arXiv rows for **Deep Snapshot HDR Reconstruction...** and **Polarimetric Spatio-Temporal Light Transport Probing**; retained their published entries.
- Updated preprint venues for **Polarization Guided Specular Reflection Separation** ([TIP 2021](https://arxiv.org/abs/2103.11652)), **Polarization-driven Semantic Segmentation...** ([Optics Express 2021](https://publikationen.bibliothek.kit.edu/1000135363)), **Polarimetric Imaging for Perception** ([BMVC 2023](https://proceedings.bmvc2023.org/566/)), and **Human Pose and Shape Estimation...** ([TMM](https://vision-and-learning-lab-ualberta.github.io/publication/shihao-et-al-tmm-2022/), volume 25, 2023; online-first 2022).
- Corrected the unrelated sensor link attached to **Polarimetric 3D Integral Imaging in Photon-Starved Conditions** to its [Optics Express paper](https://doi.org/10.1364/OE.23.006408). Corrected the 2016 low-light integral-imaging entry to its [own institutional record](https://diposit.ub.edu/items/3c92c477-4fef-4cb1-8add-fb750d65976d).
- Corrected the four-directional CMOS sensor year from 2015 to [IEDM 2016](https://ieee-iedm.org/wp-content/uploads/2026/05/2016-IEDM-Archive.pdf), and restored the complete **Polarized 3D: High-Quality Depth Sensing...** title.

**Event-Based Shape From Polarization** contains both a physical estimator and a learned estimator, so it is classified as DL. **All-Photon Polarimetric Time-of-Flight Imaging** optimizes physical reflectance/acquisition parameters without a deep network, so it is non-DL. General surveys are grouped under non-DL even when they discuss both families; reviews specifically about deep learning are grouped under DL.

Published extensions are distinct from duplicate preprints: the 2023 TPAMI **Polarimetric Multi-View Inverse Rendering** is retained separately from ECCV 2020. Likewise, the NeurIPS 2024 PolFusion paper and its 2026 TPAMI extension remain separate. SS-SfP is dated to its Pacific Graphics 2023 short-paper publication, rather than its 2024 arXiv upload.

## Added entries and sources

|Year|Venue|Group|Paper / source|
|:---:|---|---|---|
|1990|TPAMI|Miscellaneous (non-DL)|[Polarization-Based Material Classification from Specular Reflection](https://www.cs.jhu.edu/~wolff/)|
|1991|TPAMI|Miscellaneous (non-DL)|[Constraining Object Features Using a Polarization Reflectance Model](https://www.cs.jhu.edu/~wolff/)|
|1997|IJCV|Miscellaneous (non-DL)|[Separation of Reflection Components Using Color and Polarization](https://cave.cs.columbia.edu/old/publications/pdfs/Nayar_IJCV97.pdf)|
|1998|CVPR|Polarization Imaging (non-DL)|[Image Understanding from Polarization of Thermal Emission](https://www.cs.jhu.edu/~wolff/)|
|2001|CVPR|Polarization Imaging (non-DL)|[Instant Dehazing of Images Using Polarization](https://doi.org/10.1109/CVPR.2001.990493)|
|2001|CVPR|Polarization Imaging (non-DL)|[Reconstruction of Specular Surfaces Using Polarization Imaging](https://doi.org/10.1109/CVPR.2001.990468)|
|2003|Applied Optics|Miscellaneous (non-DL)|[Polarization-based Vision through Haze](https://webee.technion.ac.il/~yoav/publications/haze_osa.pdf)|
|2003|ICCV|Polarization Imaging (non-DL)|[Polarization-based Inverse Rendering from a Single View](https://doi.org/10.1109/ICCV.2003.1238455)|
|2003|ICCV|Polarization Imaging (non-DL)|[Polarization-based Transparent Surface Modeling from Two Views](https://lear.inrialpes.fr/people/triggs/events/iccv03/cdrom/iccv03/1381_miyazaki.pdf)|
|2004|TPAMI|Miscellaneous (non-DL)|[Separation of Diffuse and Specular Components of Surface Reflection by Use of Polarization and Statistical Analysis of Images](https://doi.org/10.1109/TPAMI.2004.1273960)|
|2005|ICCV|Polarization Imaging (non-DL)|[Multi-view Surface Reconstruction Using Polarization](https://pure.york.ac.uk/portal/en/publications/multi-view-surface-reconstruction-using-polarization/)|
|2006|CVPR|Polarization Imaging (non-DL)|[Blind Haze Separation](https://webee.technion.ac.il/people/cgm/Computer-Graphics-Multimedia/Publications/Papers/2006/2006_Blind_Haze_Separation.pdf)|
|2007|EGSR|Miscellaneous (non-DL)|[Rapid Acquisition of Specular and Diffuse Normal Maps from Polarized Spherical Gradient Illumination](https://www.cs.wm.edu/~ppeers/publications/Ma2007RAS/Ma_EGSR2007_lowres.pdf)|
|2007|TPAMI|Miscellaneous (non-DL)|[Shape Estimation Using Polarization and Shading from Two Views](https://doi.org/10.1109/TPAMI.2007.1099)|
|2008|CVIU|Miscellaneous (non-DL)|[Two-dimensional BRDF Estimation from Polarisation](https://doi.org/10.1016/j.cviu.2007.09.005)|
|2008|CVPR|Polarization Imaging (non-DL)|[On Controlling Light Transport in Poor Visibility Environments](https://graphics.cs.cmu.edu/projects/LightTransport/index_files/LightTransportInPoorVisibility.pdf)|
|2010|CVPR|Polarization Imaging (non-DL)|[Shape and Refractive Index Recovery from Single-View Polarisation Images](https://users.cecs.anu.edu.au/~arobkell/papers/cvpr10.pdf)|
|2013|CVPR|Polarization Imaging (non-DL)|[Video Enhancement of People Wearing Polarized Glasses: Darkening Reversal and Reflection Reduction](https://openaccess.thecvf.com/content_cvpr_2013/html/Ye_Video_Enhancement_of_2013_CVPR_paper.html)|
|2016|ECCV|Polarization Imaging (non-DL)|[Linear Depth Estimation from an Uncalibrated, Monocular Polarisation Image](https://doi.org/10.1007/978-3-319-46484-8_7)|
|2017|CVIU|Miscellaneous (non-DL)|[Polarisation Photometric Stereo](https://uwe-repository.worktribe.com/output/883604/polarisation-photometric-stereo)|
|2017|ICCV Workshops|Miscellaneous (non-DL)|[Shape-From-Polarisation: A Nonlinear Least Squares Approach](https://openaccess.thecvf.com/content_ICCV_2017_workshops/w43/html/Yu_Shape-From-Polarisation_A_Nonlinear_ICCV_2017_paper.html)|
|2018|CVPR|Polarization Imaging (non-DL)|[Self-Calibrating Polarising Radiometric Calibration](https://openaccess.thecvf.com/content_cvpr_2018/html/Teo_Self-Calibrating_Polarising_Radiometric_CVPR_2018_paper.html)|
|2020|ICIP|Miscellaneous (non-DL)|[Monochrome and Color Polarization Demosaicking Using Edge-Aware Residual Interpolation](https://arxiv.org/abs/2007.14292)|
|2021|ICCV|Polarization Imaging (non-DL)|[Polarimetric Helmholtz Stereopsis](https://openaccess.thecvf.com/content/ICCV2021/html/Ding_Polarimetric_Helmholtz_Stereopsis_ICCV_2021_paper.html)|
|2021|IEEE Sensors Journal|Miscellaneous (non-DL)|[Monochrome and Color Polarization Demosaicking Based on Intensity-Guided Residual Interpolation](https://ieeexplore.ieee.org/document/9583277)|
|2022|CVPR|Polarization Imaging (non-DL)|[All-Photon Polarimetric Time-of-Flight Imaging](https://openaccess.thecvf.com/content/CVPR2022/html/Baek_All-Photon_Polarimetric_Time-of-Flight_Imaging_CVPR_2022_paper.html)|
|2023|AAAI|Polarization Imaging (DL)|[Polarization-Aware Low-Light Image Enhancement](https://ojs.aaai.org/index.php/AAAI/article/view/25486)|
|2023|CVPR|Polarization Imaging (DL)|[Deep Polarization Reconstruction With PDAVIS Events](https://openaccess.thecvf.com/content/CVPR2023/html/Mei_Deep_Polarization_Reconstruction_With_PDAVIS_Events_CVPR_2023_paper.html)|
|2023|CVPR|Polarization Imaging (DL)|[Event-Based Shape From Polarization](https://openaccess.thecvf.com/content/CVPR2023/html/Muglikar_Event-Based_Shape_From_Polarization_CVPR_2023_paper.html)|
|2023|CVPR|Polarization Imaging (non-DL)|[Fresnel Microfacet BRDF: Unification of Polari-Radiometric Surface-Body Reflection](https://openaccess.thecvf.com/content/CVPR2023/html/Ichikawa_Fresnel_Microfacet_BRDF_Unification_of_Polari-Radiometric_Surface-Body_Reflection_CVPR_2023_paper.html)|
|2023|CVPR|Polarization Imaging (DL)|[Learning Accurate 3D Shape Based on Stereo Polarimetric Imaging](https://openaccess.thecvf.com/content/CVPR2023/html/Huang_Learning_Accurate_3D_Shape_Based_on_Stereo_Polarimetric_Imaging_CVPR_2023_paper.html)|
|2023|CVPR|Polarization Imaging (DL)|[pCON: Polarimetric Coordinate Networks for Neural Scene Representations](https://openaccess.thecvf.com/content/CVPR2023/html/Peters_pCON_Polarimetric_Coordinate_Networks_for_Neural_Scene_Representations_CVPR_2023_paper.html)|
|2023|Frontiers in Physics|Miscellaneous (non-DL)|[Polarization 3D Imaging Technology: A Review](https://www.frontiersin.org/journals/physics/articles/10.3389/fphy.2023.1198457/full)|
|2023|Optics & Laser Technology|Miscellaneous (DL)|[Polarimetric Image Denoising on Small Datasets Using Deep Transfer Learning](https://doi.org/10.1016/j.optlastec.2023.109632)|
|2023|Pacific Graphics Short Papers|Miscellaneous (DL)|[SS-SfP: Neural Inverse Rendering for Self Supervised Shape from (Mixed) Polarization](https://diglib.eg.org/items/18975fda-cbb5-403f-a41f-ea656a759531)|
|2023|Remote Sensing|Miscellaneous (DL)|[Polarimetric Imaging via Deep Learning: A Review](https://www.mdpi.com/2072-4292/15/6/1540)|
|2023|TPAMI|Miscellaneous (non-DL)|[Polarimetric Multi-View Inverse Rendering](https://doi.org/10.1109/TPAMI.2022.3232211)|
|2023|WACV|Polarization Imaging (non-DL)|[Separating Partially-Polarized Diffuse and Specular Reflection Components Under Unpolarized Light Sources](https://openaccess.thecvf.com/content/WACV2023/html/Kajiyama_Separating_Partially-Polarized_Diffuse_and_Specular_Reflection_Components_Under_Unpolarized_Light_WACV_2023_paper.html)|
|2024|Journal of Electronic Imaging|Miscellaneous (non-DL)|[Pola4All: Survey of Polarimetric Applications and an Open-Source Toolkit to Analyze Polarization](https://doi.org/10.1117/1.JEI.33.1.010901)|
|2024|Laser & Photonics Reviews|Miscellaneous (DL)|[Deep Learning Enabled Transmission of Full-Stokes Polarization Images through Complex Media](https://doi.org/10.1002/lpor.202400626)|
|2024|NeurIPS|Polarization Imaging (DL)|[Quality-Improved and Property-Preserved Polarimetric Imaging via Complementarily Fusing](https://proceedings.neurips.cc/paper_files/paper/2024/hash/f543648b4332a4d8b9e1b72c6b4e2e26-Abstract-Conference.html)|
|2024|Optics & Laser Technology|Miscellaneous (DL)|[Learning Based Polarization Image Fusion under an Alternative Paradigm](https://doi.org/10.1016/j.optlastec.2023.109969)|
|2024|Opto-Electronic Science|Miscellaneous (DL)|[Data-driven Polarimetric Imaging: A Review](https://doi.org/10.29026/oes.2024.230042)|
|2024|SIGGRAPH|Polarization Imaging (non-DL)|[Spin-Weighted Spherical Harmonics for Polarized Light Transport](https://vclab.kaist.ac.kr/siggraph2024/index.html)|
|2024|Sensors|Miscellaneous (non-DL)|[Passive Polarized Vision for Autonomous Vehicles: A Review](https://www.mdpi.com/1424-8220/24/11/3312)|
|2024|TGRS|Miscellaneous (DL)|[Polarized Prior Guided Fusion Network for Infrared Polarization Images](https://ieeexplore.ieee.org/document/10500824)|

## Remaining coverage limits

This is a curated expansion, not proof that every relevant paper has been found. Title screening misses papers whose titles omit polarization terminology. Pre-2013 conferences, workshops, journals, sensor hardware, biomedical imaging, and all arXiv submissions were not exhaustively enumerated. Optical computer vision and computational imaging remain the focus; dedicated PolSAR literature is outside this audit. Existing historical rows were corrected where an issue was confirmed, but their entire metadata and all old links were not revalidated.

The conference grouping follows the existing repository convention (including WACV and ICCP), rather than asserting a universal conference ranking. ICIP, BMVC, EGSR, Pacific Graphics short papers, workshops, journals, and unpublished preprints are in Miscellaneous.
