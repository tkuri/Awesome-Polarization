<!-- PROJECT LOGO -->
<p align="center">
  <h3 align="center">Polarization Imaging</h3>
</p>

A curated list of polarization imaging research in computer vision and computational imaging.

- **DL**: methods that use deep neural networks, including neural fields and pretrained networks, even when optimized per scene or used without retraining.
- **non-DL**: analytical methods and direct optimization without deep neural networks. Optimizing explicit Gaussian primitives or environment maps alone does not count as DL.
- **Miscellaneous**: journals, preprints, workshops, and conferences outside the main conference list. New conference entries follow the venue grouping already used here (CVPR, ICCV, ECCV, NeurIPS, AAAI, SIGGRAPH / SIGGRAPH ASIA, ICCP, and WACV).
- **Year / Pub**: the conference or journal publication year and venue; arXiv submission year when no publication venue is confirmed. A paper linked through arXiv may still have a confirmed conference venue. Blank Repo cells mean no official resource link was verified.

**Classification notes for new entries**: Thermal Polarimetric Multi-view Stereo uses an MLP surface representation; Poppy uses pretrained normal-estimation networks; PhyGaP uses pretrained segmentation for real captures. These are listed under DL. PolGS and PolarGuide-GSDR directly optimize explicit representations and are listed under non-DL.

2025 onward entries last checked: **2026-10-10**. This is a curated selection, not an exhaustive bibliography.

## Table of contents

- [Polarization Imaging (non-DL)](#polarization-imaging-non-dl)
- [Polarization Imaging (DL)](#polarization-imaging-dl)
- [Miscellaneous (non-DL)](#miscellaneous-non-dl)
- [Miscellaneous (DL)](#miscellaneous-dl)

## Polarization Imaging (non-DL)
|Year|Pub|Paper|Application|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2010|SIGGRAPH ASIA|[Circularly Polarized Spherical Illumination Reflectometry](https://ict.usc.edu/pubs/Circularly%20Polarized%20Spherical%20Illumination%20Reflectometry.pdf)|Rendering||
|2011|SIGGRAPH ASIA|[Multiview Face Capture using Polarized Spherical Gradient Illumination](https://ict.usc.edu/pubs/Multiview%20Face%20Capture%20using%20Polarized%20Spherical%20Gradient%20Illumination.pdf)|Rendering / 3D Shape||
|2015|CVPR|[Shape and Light Directions From Shading and Polarization](https://openaccess.thecvf.com/content_cvpr_2015/html/Thanh_Shape_and_Light_2015_CVPR_paper.html)|Rendering / 3D Shape||
|2015|ICCV|[Polarized 3D: Depth Sensing with Polarization Cues](https://web.media.mit.edu/~achoo/polar3D/)|3D Shape||
|2017|CVPR|[Polarimetric Multi-View Stereo](https://zhpcui.github.io/projects/polarstereo/)|3D Shape||
|2017|ICCV|[A Lightweight Single-Camera Polarization Compass With Covariance Estimation](https://openaccess.thecvf.com/content_iccv_2017/html/Sturzl_A_Lightweight_Single-Camera_ICCV_2017_paper.html)|Compass||
|2017|ICCV|[Linear Differential Constraints for Photo-Polarimetric Height Estimation](https://openaccess.thecvf.com/content_iccv_2017/html/Tozza_Linear_Differential_Constraints_ICCV_2017_paper.html)|Rendering / 3D Shape||
|2017|SIGGRAPH ASIA|[Polarization imaging reflectometry in the wild](http://wp.doc.ic.ac.uk/rgi/project/polarization-imaging-reflectometry-in-the-wild/)|Rendering||
|2018|CVPR|[Polarimetric Dense Monocular SLAM](https://openaccess.thecvf.com/content_cvpr_2018/html/Yang_Polarimetric_Dense_Monocular_CVPR_2018_paper.html)|SLAM||
|2018|ECCV|[Polarimetric Three-View Geometry](https://openaccess.thecvf.com/content_ECCV_2018/html/Lixiong_Chen_Polarimetric_Three-View_Geometry_ECCV_2018_paper.html)|Camera Pose Estimation||
|2018|SIGGRAPH ASIA|[Simultaneous Acquisition of Polarimetric SVBRDF and Normals](http://vclab.kaist.ac.kr/siggraphasia2018p2/index.html)|Rendering / 3D Shape||
|2019|CVPR|[Polarimetric Camera Calibration Using an LCD Monitor](https://openaccess.thecvf.com/content_CVPR_2019/html/Wang_Polarimetric_Camera_Calibration_Using_an_LCD_Monitor_CVPR_2019_paper.html)|Calibration||
|2019|CVPR|[Depth from a polarisation + RGB stereo pair](https://openaccess.thecvf.com/content_CVPR_2019/html/Zhu_Depth_From_a_Polarisation__RGB_Stereo_Pair_CVPR_2019_paper.html)|3D Shape|[Code & Dataset](https://github.com/AmosZhu/CVPR2019)|
|2019|ICCV|[Polarimetric Relative Pose Estimation](https://www.microsoft.com/en-us/research/publication/polarimetric-relative-pose-estimation/)|Pose Estimation||
|2020|CVPR|[Polarized Non-Line-of-Sight Imaging](https://openaccess.thecvf.com/content_CVPR_2020/html/Tanaka_Polarized_Non-Line-of-Sight_Imaging_CVPR_2020_paper.html)|NLOS||
|2020|SIGGRAPH|[Image-Based Acquisition and Modeling of Polarimetric Reflectance](http://vclab.kaist.ac.kr/siggraph2020/index.html)|Rendering|[Dataset](http://vclab.kaist.ac.kr/siggraph2020/pbrdfdataset/kaistdataset.html)|
|2020|ECCV|[Full-Time Monocular Road Detection Using Zero-Distribution Prior of Angle of Polarization](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700460.pdf)|Road Detection||
|2020|ECCV|[Polarized Optical-Flow Gyroscope](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2559_ECCV_2020_paper.php)|Gyroscope||
|2020|ECCV|[Polarimetric Multi-View Inverse Rendering](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/4522_ECCV_2020_paper.php)|3D Shape||
|2021|CVPR|[Polarimetric Normal Stereo](https://openaccess.thecvf.com/content/CVPR2021/papers/Fukao_Polarimetric_Normal_Stereo_CVPR_2021_paper.pdf)|3D Shape||
|2021|CVPR|[Shape From Sky: Polarimetric Normal Recovery Under the Sky](https://openaccess.thecvf.com/content/CVPR2021/html/Ichikawa_Shape_From_Sky_Polarimetric_Normal_Recovery_Under_the_Sky_CVPR_2021_paper.html)|3D Shape||
|2021|SIGGRAPH ASIA|[Polarimetric Spatio-Temporal Light Transport Probing](https://arxiv.org/abs/2105.11609)|Transient Imaging||
|2022|CVPR|[Degree-of-Linear-Polarization-Based Color Constancy](https://openaccess.thecvf.com/content/CVPR2022/html/Ono_Degree-of-Linear-Polarization-Based_Color_Constancy_CVPR_2022_paper.html)|White Balance|[Code & Dataset](https://github.com/sony/dolp-colorconstancy)|
|2022|ICCP|[PS2F: Polarized Spiral Point Spread Function for Single-Shot 3D Sensing](https://arxiv.org/pdf/2207.00945.pdf)|Microscope||
|2022|SIGGRAPH|[Sparse Ellipsometry: Portable Acquisition of Polarimetric SVBRDF and Shape with Unstructured Flash Photography](https://vclab.kaist.ac.kr/siggraph2022p1/paper-acmtog-main-final.pdf)|Rendering / 3D Shape|[Code](https://github.com/KAIST-VCLAB/SparseEllipsometry)|
|2022|ECCV|[Perspective Phase Angle Model for Polarimetric 3D Reconstruction](https://arxiv.org/abs/2207.09629v2)|3D Shape|[Code](https://github.com/gcchen97/ppa4p3d)|
|2023|CVPR|[Polarimetric iToF: Measuring High-Fidelity Depth through Scattering Media](https://openaccess.thecvf.com/content/CVPR2023/papers/Jeon_Polarimetric_iToF_Measuring_High-Fidelity_Depth_Through_Scattering_Media_CVPR_2023_paper.pdf)|3D Shape||
|2023|CVPR|[High-Res Facial Appearance Capture from Polarized Smartphone Images](https://arxiv.org/pdf/2212.01160)|Rendering / 3D Shape||
|2024|WACV|[Polarimetric PatchMatch Multi-View Stereo](https://openaccess.thecvf.com/content/WACV2024/html/Zhao_Polarimetric_PatchMatch_Multi-View_Stereo_WACV_2024_paper.html)|3D Shape|[Code](http://www.ok.sc.e.titech.ac.jp/res/PolarPMS/)|
|2024|CVPR|[SPIDeRS: Structured Polarization for Invisible Depth and Reflectance Sensing](https://vision.ist.i.kyoto-u.ac.jp/research/spiders/)|3D Shape / Relighting||
|2024|CVPR|[Spectral and Polarization Vision:Spectro-polarimetric Real-world Dataset](https://eschoi.com/SPDataset/)|Dataset|[Dataset](https://huggingface.co/datasets/jyj7913/spectro-polarimetric)|
|2024|CVPR|[PolarMatte: Fully Computational Ground-Truth-Quality Alpha Matte Extraction for Images and Video using Polarized Screen Matting](https://openaccess.thecvf.com/content/CVPR2024/html/Enomoto_PolarMatte_Fully_Computational_Ground-Truth-Quality_Alpha_Matte_Extraction_for_Images_and_CVPR_2024_paper.html)|Matting||
|2025|WACV|[Polarization as Texture: Microscale 3D Shape from Polarized Light Focus](https://openaccess.thecvf.com/content/WACV2025/html/Matsumoto_Polarization_as_Texture_Microscale_3D_Shape_from_Polarized_Light_Focus_WACV_2025_paper.html)|3D Shape||
|2025|CVPR|[Event Ellipsometer: Event-based Mueller-Matrix Video Imaging](https://openaccess.thecvf.com/content/CVPR2025/html/Maeda_Event_Ellipsometer_Event-based_Mueller-Matrix_Video_Imaging_CVPR_2025_paper.html)|Mueller-Matrix Video Imaging||
|2025|CVPR|[Polarized Color Screen Matting](https://openaccess.thecvf.com/content/CVPR2025/html/Enomoto_Polarized_Color_Screen_Matting_CVPR_2025_paper.html)|Matting||
|2025|ICCV|[PolGS: Polarimetric Gaussian Splatting for Fast Reflective Surface Reconstruction](https://openaccess.thecvf.com/content/ICCV2025/html/Han_PolGS_Polarimetric_Gaussian_Splatting_for_Fast_Reflective_Surface_Reconstruction_ICCV_2025_paper.html)|Rendering / 3D Shape|[Code](https://github.com/PRIS-CV/PolGS)|
|2025|ICCP|[Shape from Polarization of Thermal Emission and Reflection](https://k2zm.github.io/SfPTER-ICCP2025/)|3D Shape|[Code & Dataset](https://github.com/k2zm/SfPTER-ICCP2025)|
|2025|SIGGRAPH ASIA|[Single-Shot Facial Capture using Polarized RGB Sinusoidal Illumination](https://spiral.imperial.ac.uk/entities/publication/9c343911-59e8-4d3c-99df-31d5c302b752)|Rendering / 3D Shape||
|2025|SIGGRAPH ASIA|[Frame-Free Representation of Polarized Light for Resolving Stokes Vector Singularities](https://vclab.kaist.ac.kr/siggraphasia2025p2/)|Polarimetric Representation / Rendering|[Code](https://github.com/KAIST-VCLAB/frame-free-polar-representation)|
|2025|SIGGRAPH ASIA|[Hyperspectral Polarimetric BRDFs of Real-world Materials](https://arxiv.org/abs/2509.13779)|Dataset / Rendering||
|2026|CVPR|[PolarGuide-GSDR: 3D Gaussian Splatting Driven by Polarization Priors and Deferred Reflection for Real-World Reflective Scenes](https://openaccess.thecvf.com/content/CVPR2026/html/Shan_PolarGuide-GSDR_3D_Gaussian_Splatting_Driven_by_Polarization_Priors_and_Deferred_CVPR_2026_paper.html)|Rendering / 3D Shape||
|2026|ECCV|[Differentiable Polarized Path Tracing](https://vcai.mpi-inf.mpg.de/projects/DPPT/)|Rendering / Inverse Rendering||

## Polarization Imaging (DL)
|Year|Pub|Paper|Application|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2019|NeurIPS|[Reflection Separation using a Pair of Unpolarized and Polarized Images](https://papers.nips.cc/paper/2019/file/d47bf0af618a3523a226ed7cada85ce3-Paper.pdf)|Reflection Removal|[Code & Dataset](https://github.com/YouweiLyu/reflection_separation_with_un-polarized_images)|
|2020|CVPR|[Polarized Reflection Removal With Perfect Alignment in the Wild](https://openaccess.thecvf.com/content_CVPR_2020/html/Lei_Polarized_Reflection_Removal_With_Perfect_Alignment_in_the_Wild_CVPR_2020_paper.html)|Reflection Removal|[Code & Dataset](https://github.com/ChenyangLEI/CVPR2020-Polarized-Reflection-Removal-with-Perfect-Alignment)|
|2020|CVPR|[Deep Polarization Cues for Transparent Object Segmentation](https://openaccess.thecvf.com/content_CVPR_2020/html/Kalra_Deep_Polarization_Cues_for_Transparent_Object_Segmentation_CVPR_2020_paper.html)|Transparent Segmentation||
|2020|ECCV|[Accurate Polarimetric BRDF for Real Polarization Scene Rendering](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3186_ECCV_2020_paper.php)|Rendering / 3D Shape||
|2020|ECCV|[Deep Shape from Polarization](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/4676_ECCV_2020_paper.php)|3D Shape|[Dataset](https://visual.ee.ucla.edu/deepsfp.htm)|
|2020|ECCV|[Reflection Separation via Multi-bounce Polarization State Tracing](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2055_ECCV_2020_paper.php)|Reflection Separation||
|2020|ECCV|[3D Human Shape Reconstruction from a Polarization Image](https://www.ecva.net/papers/eccv_2020/papers_ECCV/html/2136_ECCV_2020_paper.php)|3D Human Shape|[Code](https://github.com/JimmyZou/PolarHumanPoseShape) / [Dataset](https://jimmyzou.github.io/publication/2020-PHSPDataset)|
|2021|CVPR|[Deep Polarization Imaging for 3D shape and SVBRDF Acquisition](https://arxiv.org/abs/2105.02875v1)|Rendering / 3D Shape|[Code & Dataset](https://wp.doc.ic.ac.uk/rgi/project/deep-polarization-3d-imaging/)|
|2021|ICIP|[Deep Snapshot Hdr Reconstruction Based On The Polarization Camera](https://ieeexplore.ieee.org/document/9506314)|HDR||
|2022|CVPR|[Shape From Polarization for Complex Scenes in the Wild](https://openaccess.thecvf.com/content/CVPR2022/html/Lei_Shape_From_Polarization_for_Complex_Scenes_in_the_Wild_CVPR_2022_paper.html)|3D Shape|[Code & Dataset](https://chenyanglei.github.io/sfpwild/index.html)|
|2022|CVPR|[Glass Segmentation Using Intensity and Spectral Polarization Cues](https://openaccess.thecvf.com/content/CVPR2022/html/Mei_Glass_Segmentation_Using_Intensity_and_Spectral_Polarization_Cues_CVPR_2022_paper.html)|Glass Segmentation|[Code & Dataset](https://mhaiyang.github.io/CVPR2022_PGSNet/)|
|2022|CVPR|[Multimodal Material Segmentation](https://vision.ist.i.kyoto-u.ac.jp/research/mcubes/)|Material Segmentation|[Code & Dataset](https://github.com/kyotovision-public/multimodal-material-segmentation)|
|2022|ICIP|[Two-Step Color-Polarization Demosaicking Network](http://www.ok.sc.e.titech.ac.jp/res/PolarDem/TCPDNet.html)|Demosaicking||
|2022|ECCV|[PANDORA: Polarization-Aided Neural Decomposition Of Radiance](https://akshatdave.github.io/pandora/)|3D Shape|[Code](https://github.com/akshatdave/pandora) / [Dataset](https://drive.google.com/file/d/1FvOi_2wfSUnASHulQdBhHQcQCxOuJ8zz/view)|
|2022|ECCV|[Polarimetric Pose Prediction](https://daoyig.github.io/PPPNet/)|Pose Prediction|[Code](https://github.com/DaoyiG/polarimetric-pose-prediction) / [Dataset](https://www.campar.in.tum.de/public_datasets/2022_eccv_ruhkamp/README.html)|
|2023|WACV|[Simultaneous Acquisition of High Quality RGB Image and Polarization Information using a Sparse Polarization Sensor](https://arxiv.org/abs/2209.13106)|New Sensor Array|[Code & Dataset](https://github.com/sony/polar-densification)|
|2023|CVPR|[Polarized Color Image Denoising](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Polarized_Color_Image_Denoising_CVPR_2023_paper.html)|Denoising|[Code & Dataset](https://github.com/bandasyou/pcdenoise)|
|2023|ICCV|[DPS-Net: Deep Polarimetric Stereo Depth Estimation](https://openaccess.thecvf.com/content/ICCV2023/html/Tian_DPS-Net_Deep_Polarimetric_Stereo_Depth_Estimation_ICCV_2023_paper.html)|3D Shape||
|2023|ICCV|[Transparent Shape from a Single View Polarization Image](https://openaccess.thecvf.com/content/ICCV2023/html/Shao_Transparent_Shape_from_a_Single_View_Polarization_Image_ICCV_2023_paper.html)|3D Shape|[Code & Dataset](https://github.com/shaomq2187/TransSfP)|
|2023|ICCV|[Multi-view Spectral Polarization Propagation for Video Glass Segmentation](https://openaccess.thecvf.com/content/ICCV2023/html/Qiao_Multi-view_Spectral_Polarization_Propagation_for_Video_Glass_Segmentation_ICCV_2023_paper.html)|Transparent Segmentation||
|2023|SIGGRAPH ASIA|[Neural Spectro-polarimetric Fields](https://arxiv.org/abs/2306.12562)|View Synthesis|[Code & Dataset](https://github.com/youngchan-k/NeSpoF)|
|2024|CVPR|[Robust Depth Enhancement via Polarization Prompt Fusion Tuning](https://arxiv.org/abs/2404.04318)|3D Shape|[Code & Dataset](https://github.com/lastbasket/Polarization-Prompt-Fusion-Tuning)|
|2024|CVPR|[NeISF: Neural Incident Stokes Field for Geometry and Material Estimation](https://openaccess.thecvf.com/content/CVPR2024/html/Li_NeISF_Neural_Incident_Stokes_Field_for_Geometry_and_Material_Estimation_CVPR_2024_paper.html)|Rendering / 3D Shape|[Code & Dataset](https://github.com/sony/NeISF)|
|2024|CVPR|[Polarization Wavefront Lidar:Learning Large Scene Reconstruction from Polarized Wavefronts](https://light.princeton.edu/publication/pollidar/)|3D Shape|[Code](https://github.com/princeton-computational-imaging/PolLidar)|
|2024|CVPR|[Fooling Polarization-Based Vision using Locally Controllable Polarizing Projection](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Fooling_Polarization-Based_Vision_using_Locally_Controllable_Polarizing_Projection_CVPR_2024_paper.html)|Fooling||
|2024|CVPR|[NeRSP: Neural 3D Reconstruction for Reflective Objects with Sparse Polarized Images](https://yu-fei-han.github.io/NeRSP-project/)|3D Shape|[Code & Dataset](https://github.com/PRIS-CV/NeRSP)|
|2024|CVPR|[Learning to Remove Wrinkled Transparent Film with Polarized Prior](https://jqt.me/_FilmRemoval_/)|Film removal|[Code & Dataset](https://github.com/jqtangust/FilmRemoval)|
|2024|AAAI|[Exploiting Polarized Material Cues for Robust Car Detection](https://arxiv.org/abs/2401.02606)|Car detection|[Code & Dataset](https://github.com/wind1117/AAAI24-PCDNet)|
|2024|ECCV|[Deep Polarization Cues for Single-shot Shape and Subsurface Scattering Estimation](https://arxiv.org/abs/2407.08149)|Translucent 3D Shape|[Code & Dataset](https://github.com/ligoudaner377/polarized_inverse_scattering)|
|2024|ECCV|[PISR: Polarimetric Neural Implicit Surface Reconstruction for Textureless and Specular Objects](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/01284.pdf)|3D Shape|[Code](https://github.com/GCChen97/PISR)|
|2025|CVPR|[PolarFree: Polarization-based Reflection-Free Imaging](https://openaccess.thecvf.com/content/CVPR2025/html/Yao_PolarFree_Polarization-based_Reflection-Free_Imaging_CVPR_2025_paper.html)|Reflection removal|[Code & Dataset](https://github.com/mdyao/PolarFree)|
|2025|CVPR|[Glossy Object Reconstruction with Cost-effective Polarized Acquisition](https://openaccess.thecvf.com/content/CVPR2025/html/Wu_Glossy_Object_Reconstruction_with_Cost-effective_Polarized_Acquisition_CVPR_2025_paper.html)|Rendering / 3D Shape||
|2025|CVPR|[PIDSR: Complementary Polarized Image Demosaicing and Super-Resolution](https://openaccess.thecvf.com/content/CVPR2025/html/Zhou_PIDSR_Complementary_Polarized_Image_Demosaicing_and_Super-Resolution_CVPR_2025_paper.html)|Demosaicking / Super-Resolution|[Code & Dataset](https://github.com/PRIS-CV/PIDSR)|
|2025|CVPR|[NeISF++: Neural Incident Stokes Field for Polarized Inverse Rendering of Conductors and Dielectrics](https://openaccess.thecvf.com/content/CVPR2025/html/Li_NeISF_Neural_Incident_Stokes_Field_for_Polarized_Inverse_Rendering_of_CVPR_2025_paper.html)|Rendering / 3D Shape|[Code & Dataset](https://github.com/sony/NeISFpp)|
|2025|ICCV|[Polarimetric Neural Field via Unified Complex-Valued Wave Representation](https://openaccess.thecvf.com/content/ICCV2025/html/Zhou_Polarimetric_Neural_Field_via_Unified_Complex-Valued_Wave_Representation_ICCV_2025_paper.html)|Polarimetric Representation / Rendering|[Code](https://github.com/fourson/Polarimetric-Neural-Field-via-Unified-Complex-Valued-Wave-Representation)|
|2025|ICCV|[Benchmarking Burst Super-Resolution for Polarization Images: Noise Dataset and Analysis](https://openaccess.thecvf.com/content/ICCV2025/html/Hwang_Benchmarking_Burst_Super-Resolution_for_Polarization_Images_Noise_Dataset_and_Analysis_ICCV_2025_paper.html)|Dataset / Denoising / Super-Resolution|[Code & Dataset](https://github.com/KAIST-VCLAB/polarns)|
|2025|ICCV|[Thermal Polarimetric Multi-view Stereo](https://openaccess.thecvf.com/content/ICCV2025/html/Kushida_Thermal_Polarimetric_Multi-view_Stereo_ICCV_2025_paper.html)|3D Shape||
|2025|ICCV|[PolarAnything: Diffusion-based Polarimetric Image Synthesis](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_PolarAnything_Diffusion-based_Polarimetric_Image_Synthesis_ICCV_2025_paper.html)|Polarization Image Synthesis|[Code & Dataset](https://github.com/PRIS-CV/PolarAnything)|
|2025|AAAI|[High-Fidelity Polarimetric Implicit 3D Reconstruction with View-Dependent Physical Representation](https://ojs.aaai.org/index.php/AAAI/article/view/32710)|3D Shape||
|2025|NeurIPS|[RGB-to-Polarization Estimation: A New Task and Benchmark Study](https://proceedings.neurips.cc/paper_files/paper/2025/hash/30697d9ef8ce55de6ccc38e043a94142-Abstract-Datasets_and_Benchmarks_Track.html)|Benchmark / Polarization Estimation||
|2026|CVPR|[Polarization State Tracing for Reflection Removal and Color-Consistent Reconstruction](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Polarization_State_Tracing_for_Reflection_Removal_and_Color-Consistent_Reconstruction_CVPR_2026_paper.html)|Reflection Removal / Color Reconstruction||
|2026|CVPR|[ICTPolarReal: A Polarized Reflection and Material Dataset of Real World Objects](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_ICTPolarReal_A_Polarized_Reflection_and_Material_Dataset_of_Real_World_CVPR_2026_paper.html)|Dataset / Rendering / 3D Shape||
|2026|CVPR|[Global Underwater Geolocation from Time-Lapse Polarization Imagery](https://openaccess.thecvf.com/content/CVPR2026/html/Aghajanzadeh_Global_Underwater_Geolocation_from_Time-Lapse_Polarization_Imagery_CVPR_2026_paper.html)|Underwater Geolocation||
|2026|CVPR|[PhyGaP: Physically-Grounded Gaussians with Polarization Cues](https://openaccess.thecvf.com/content/CVPR2026/html/Wu_PhyGaP_Physically-Grounded_Gaussians_with_Polarization_Cues_CVPR_2026_paper.html)|Rendering / 3D Shape / Relighting|[Code](https://github.com/Kelvar00/PhyGaP)|
|2026|ECCV|[Poppy: Polarization-Based Plug-and-Play Guidance for Enhancing Surface Normal Estimation](https://irnkim.github.io/poppy/)|3D Shape / Normal Estimation|[Code](https://github.com/irnkim/poppy)|
|2026|ECCV|[Stokes-Informed Diffusion for Robust Linear Polarization Estimation](https://arxiv.org/abs/2607.21239)|Polarization Estimation|[Code](https://github.com/roydon-luo/GenPolar)|
|2026|ECCV|[PolarAPP: Beyond Polarization Demosaicking for Polarimetric Applications](https://arxiv.org/abs/2603.23071)|Demosaicking / Normal Estimation / Reflection Removal||
|2026|ECCV|[340 FPS Reflection-free Video from Spikes Modulated by a Rapidly Rotating Polarizer](https://pub-e7bc7e5ed67b401a8e9e587c3dee22b6.r2.dev/publications/2026/ECCV26_SpikeRR.pdf)|Reflection Removal / High-Speed Imaging||
|2026|ECCV|[Learning Spectral and Polarimetric Clues for One-to-Multimodal Novel View Synthesis](https://lttm.github.io/MultimodalStudio/pages/SPoILeR.html)|View Synthesis|[Code](https://github.com/LTTM/MultimodalStudio)|

## Miscellaneous (non-DL)
|Year|Pub|Paper|Obj|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2006|IEEE Transactions on Image Processing|[Recovery of surface orientation from diffuse polarization](https://ieeexplore.ieee.org/document/1632218)|3D Shape||
|2009|TPAMI|[Active Polarization Descattering](https://ieeexplore.ieee.org/document/4483798)|Descattering||
|2010|SCCG|[A standardised polarisation visualisation for images](https://dl.acm.org/doi/10.1145/1925059.1925070)|Visualization||
|2012|Optics Express|[Three-dimensional polarimetric computational integral imaging](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-20-14-15481&id=239071)|Integral Imaging||
|2013|SIGGRAPH|[A Reconfigurable Camera Add-On for High-Dynamic-Range, Multi-Spectral, Polarization, and Light-Field Imaging](https://hal.inria.fr/hal-00835898/document)|Reconfigurable Camera||
|2014|SPIE|[An overview of polarimetric sensing techniques and technology with applications to different research fields](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/9099/90990B/An-overview-of-polarimetric-sensing-techniques-and-technology-with-applications/10.1117/12.2053245.short)|Survey (General)||
|2015|Optics Express|[Polarimetric 3D integral imaging in photon-starved conditions](https://ieeexplore.ieee.org/document/7838378)|Integral Imaging||
|2015|IEDM|[Four-directional pixel-wise polarization CMOS image sensor using air-gap wire grid on 2.5-μm back-illuminated pixels](https://ieeexplore.ieee.org/document/7838378)|Sensor||
|2016|Arxiv|[Shape from Mixed Polarization](https://arxiv.org/abs/1605.02066)|3D Shape||
|2016|SPIE|[Estimation of the degree of polarization in low-light 3D integral imaging](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-23-5-6408&id=312580)|Integral Imaging||
|2017|International Journal of Computer Vision|[Depth Sensing Using Geometrically Constrained Polarization Normals](https://link.springer.com/article/10.1007/s11263-017-1025-7)|3D Shape||
|2018|The Science of Nature|[Polarisation vision: overcoming challenges of working with a property of light we barely see](https://link.springer.com/article/10.1007/s00114-018-1551-3)|Survey (General)||
|2018|Sensors (Basel)|[Survey of Demosaicking Methods for Polarization Filter Array Images](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6263621/)|Demosaicking||
|2018|JOSA|[Denoising imaging polarimetry by adapted BM3D method](https://www.osapublishing.org/josaa/fulltext.cfm?uri=josaa-35-4-690&id=385158)|Denoising||
|2019|Light: Science & Applications|[Nature-inspired chiral metasurfaces for circular polarization detection and full-Stokes polarimetric measurements](https://www.nature.com/articles/s41377-019-0184-4)|Sensor||
|2019|Light: Science & Applications|[Circularly and elliptically polarized light under water and the Umov effect](https://www.nature.com/articles/s41377-019-0143-0)|Theory||
|2019|Journal of Modern Optics|[Polarimetric imaging method for target enhancement in haze based on polarimetric retrieval](https://www.tandfonline.com/doi/abs/10.1080/09500340.2019.1610520?journalCode=tmop20)|Dehazing||
|2019|Optics Letters|[Three-dimensional polarimetric integral imaging under low illumination conditions](https://www.osapublishing.org/ol/abstract.cfm?uri=ol-44-13-3230)|Integral Imaging||
|2019|Bioinspiration & Biomimetics|[Noise creates polarization artefacts](https://iopscience.iop.org/article/10.1088/1748-3190/aa9e22)|Denoising||
|2019|VMV|[Polarization Demosaicking for Monochrome and Color Polarization Focal Plane Arrays](https://diglib.eg.org/handle/10.2312/vmv20191325)|Demosaicking||
|2019|IEEE Sensors Journal|[Polarized Light-Based Cancer Cell Detection Techniques: A Review](https://ieeexplore.ieee.org/document/8744376)|Cancer Cell Detection||
|2020|Arxiv|[Polarization Human Pose and Shape Dataset](https://jimmyzou.github.io/publication/2020-PHSPDataset)|Dataset|[Code](https://github.com/JimmyZou/PolarHumanPoseShape) / [Dataset](https://jimmyzou.github.io/publication/2020-PHSPDataset)|
|2020|Arxiv|[Observation of geometric phase for unpolarized and partially polarized light fields](https://arxiv.org/abs/2007.08114)|Theory||
|2020|TIP|[A New Polarization Image Demosaicking Algorithm by Exploiting Inter-Channel Correlations With Guided Filtering](https://ieeexplore.ieee.org/document/9107421)|Demosaicking||
|2021|Arxiv|[Polarimetric Monocular Dense Mapping Using Relative Deep Depth Prior](https://arxiv.org/abs/2102.05212v1)|3D Shape||
|2021|Arxiv|[Polarization Guided Specular Reflection Separation](https://arxiv.org/abs/2103.11652v1)|Reflection Separation||
|2021|Arxiv|[Polarimetric Spatio-Temporal Light Transport Probing](https://arxiv.org/abs/2105.11609)|Transient Imaging||
|2021|OSA|[Analysis of signal-to-noise ratio of angle of polarization and degree of polarization](https://www.osapublishing.org/osac/fulltext.cfm?uri=osac-4-5-1461&id=450463)|Theory||
|2021|Arxiv|[Next-generation perception system for automated defects detection in composite laminates via polarized computational imaging](https://arxiv.org/abs/2108.10819)|Defects Detection||
|2022|Applied Optics|[Calibration of a polarization image sensor and investigation of influencing factors](https://opg.optica.org/ao/fulltext.cfm?uri=ao-61-6-C37&id=462441)|Calibration||
|2025|IEEE Sensors Journal|[Universal Polarization Demosaicking Using Newton Polynomial and Residual Interpolation](https://doi.org/10.1109/JSEN.2025.3540412)|Demosaicking|[Code](https://github.com/ymingsu/UNRI)|
|2025|Optics & Laser Technology|[Adaptive DoFP polarization image demosaicking based on local gradient and channel correlation](https://doi.org/10.1016/j.optlastec.2025.112495)|Demosaicking||
|2025|Optics & Laser Technology|[Polarization imaging for visibility enhancement in low-light environments](https://doi.org/10.1016/j.optlastec.2025.113810)|Low-Light Enhancement||
|2026|Arxiv|[A Lensless Polarization Camera](https://arxiv.org/abs/2603.17156)|Lensless Imaging||

## Miscellaneous (DL)
|Year|Pub|Paper|Obj|Repo|
|:---:|:---:|:---:|:---:|:---:|
|2019|Monthly Notices of the Royal Astronomical Society|[Eliminating artefacts in polarimetric images using deep learning](https://academic.oup.com/mnras/article-abstract/491/4/5151/5645251?redirectedFrom=fulltext)|Removing Artifact||
|2020|Arxiv|[Face Anti-Spoofing by Learning Polarization Cues in a Real-World Scenario](https://arxiv.org/abs/2003.08024)|Face Anti-Spoofing||
|2020|Arxiv|[Polarimetric image augmentation](https://arxiv.org/abs/2005.11044)|Augmentation||
|2020|Optics Express|[Learning-based denoising for polarimetric images](https://www.osapublishing.org/oe/fulltext.cfm?uri=oe-28-11-16309&id=431808)|Denoising||
|2020|Arxiv|[Polarization-driven Semantic Segmentation via Efficient Attention-bridged Fusion](https://arxiv.org/abs/2011.13313)|Segmentation|[Code](https://github.com/Katexiang/EAFNet)|
|2021|Arxiv|[Deep Snapshot HDR Reconstruction Based on the Polarization Camera](https://arxiv.org/abs/2105.05824)|HDR||
|2021|Arxiv|[Human Pose and Shape Estimation from Single Polarization Images](https://arxiv.org/abs/2108.06834)|Pose Estimation||
|2022|CVIU|[Physically-admissible polarimetric data augmentation for road-scene analysis](https://www.sciencedirect.com/science/article/abs/pii/S1077314222000959)|Data Augmentation||
|2023|Arxiv|[Polarimetric Imaging for Perception](https://arxiv.org/abs/2305.14787)|Road Detection||
|2025|Optics & Laser Technology|[Demosaicking customized diffusion model for snapshot polarization imaging](https://doi.org/10.1016/j.optlastec.2025.112868)|Demosaicking||
|2025|Optics & Laser Technology|[PolMT: Denoising polarization images for measurement related application in low light environments](https://doi.org/10.1016/j.optlastec.2025.113606)|Denoising||
|2026|TPAMI|[Toward a Unified Complementary Fusion Framework for Robust Polarimetric Imaging](https://doi.org/10.1109/TPAMI.2026.3665927)|Denoising / Deblurring / Image Fusion|[Code](https://github.com/fourson/PolFusion_plus)|
|2026|TPAMI|[ZeroPIE: Zero-Reference Polarization-Aware Low-Light Enhancement via Physically Derived Illumination-Invariant Priors](https://doi.org/10.1109/TPAMI.2026.3721156)|Low-Light Enhancement|[Code](https://github.com/yangzhenshuo/ZeroPIE)|
|2026|Arxiv|[Guided Lensless Polarization Imaging](https://arxiv.org/abs/2603.27357)|Lensless Imaging||
|2026|Arxiv|[PolarVSR: A Unified Framework and Benchmark for Continuous Space-Time Polarization Video Reconstruction](https://arxiv.org/abs/2605.10275)|Dataset / Video Reconstruction / Super-Resolution||
|2026|ICIP|[CPDDNet: Color-Polarization Denoising and Demosaicking Network](https://arxiv.org/abs/2607.01100)|Denoising / Demosaicking||
|2026|Arxiv|[DensePol: Dense-Angle Polarization Dataset for Learning-Based Polarimetric Vision](https://arxiv.org/abs/2609.09359)|Dataset / Polarization Estimation||
