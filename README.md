# 3DReconstruction_Indoor-real-time
Real time reconstruction of 3D indoor scenes

Using the Orbbec Astra Mini point cloud camera, real-time depth is captured and converted into point cloud images. The point cloud is registered using the PCL library and CUDACP to obtain the transformation relationship between adjacent frames. The first frame is taken as the original frame, and subsequent frames are converted to the coordinate system based on the transformation relationship to achieve fusion and complete the goal of 3D scene reconstruction
