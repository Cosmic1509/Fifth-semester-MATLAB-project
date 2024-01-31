- With the progressing software we can see the everyday advancements in image processing applications which are expanding towards the various other operations. 
In the real-time world we can observe that 2D and 3D image processing is available and its implementation is in a wide range. 
Here, we will be using MATLAB software analogy to produce and evaluate 3D images. 

- Image processing in MATLAB is very keenly heard but image simulation of videos, easy debugging, recording of the process used, numerical accuracy, and code is effortless within it. 
MATLAB provides various tasks for image processing, there are functions written within MATLAB thus, leading to easy implementation and open to scrutiny, making it different from Photoshop. 
The image processing algorithms present under MATLAB are more advanced than many editing applications.

- The techniques that are being used are video reversal, 3D image restoration, slow motion video, rendered volumes, geometric transformations, image segmentation, and video segmentation. 
Our main objective is to process 3-Dimensional(3D) images with the most recent tools and provide an empirically based method using Three Dimensional Discrete Cosine Transform (3D- DCT) with MATLAB-based analytics. 
The results which will be decoded can have an accurate approach to 3D image processing.

**Methodology:**

- Here in our method we have proposed the three-dimensional discrete cosine transform (3D DCT) which has been used in many 3D applications such as video coding, geometric transformations, semantic segmentation of videos and compression. Many fast algorithms have been developed for the calculation of the 1D DCT. These algorithms are then used for the calculation of the 3D DCT using the row-column approach or through mapping it to 1-D and using other transforms.

- Volume rendering is the direct rendering of data sampled in three dimensions. By modeling each voxel (volume element) as both a source and attenuator of light, volume rendering allows the visualization of interior structure and its relations to exterior forms. There are two basic approaches to volume renderings: the object space approach and the image space approach.

- In the object space approach, the contributions of voxels, cells, or kernels are projected onto the image plane, whereas in the image space approach ray tracing to perform the source-attenuation integral is carried out for each pixel on the image plane. Accelerated methods have been proposed including fast algorithms that build additional data-structure prior to rendering under the assumption that there is sufficient memory to hold the data-structure. Multidimensional variants of the various DCT types follow straightforwardly from the one-dimensional definitions: they are simply a separable product (equivalently, a composition) of DCTs along each dimension

**Volume Rendering:**

- The volume Viewer in MATLAB is a combination of technologies used in computer graphics and scientific visualisation to build a 2D projection from a discretely sampled 3D data set is known as volume rendering it can be used to observe medical X-rays and models of the organs of the body in different contrasts and also can be useful for viewing a collection of 2D slice images from an MRI, CT or a Micro CT scanner for a 3D data set.
- I have used a CT Chest models and have observed it in Volume Viewer in MATLAB. The opacity and Image Intensity of the model can be altered by the graph on the right hand side. There are many tools in MATLAB to see the Models in certain contrasts for clear visualization and identification of any discrepancies. In Volume Viewer in the rendering editor panel, we can change the rendering style of the model which are – Volume Rendering, Maximum Intensity Rendering and Isotropic Rendering.
The Colour map of the model can also be changed for visualization of the model in different contrasts. There is free movement and rendering of the three dimensional models in MATLAB which makes it convenient for study of the abnormalities and organ.

![image](https://github.com/Cosmic1509/Fifth-semester-MATLAB-project/assets/82835887/a5709176-7210-4558-a0d4-0d8eccc98d0a)


**Volume rendering Schematic:**

- In my project I performed Volumetric Semantic Segmentation on a three dimensional model where Volume image segmentation is a manual or automatic procedure that can be used to section out large portions of the volume that one considers uninteresting before rendering, the amount of calculations that have to be made by ray casting or texture blending can be significantly reduced.
Here, I have identified a tumor in a human brain three dimensional model. In this tool the images of the model will be in the form of slices. There are a total of 155 slices in the 3-D brain model. In this model each and every slice shows an image of the brain in detail, all the 155 slices are continuous shots of the brain under a MRI scan. In this tool, we can paint out labels of the tumor and brain observed in the slices.
- Label 1 can be named as brain and Label 2 can be named as tumor, both can be drawn out accordingly with the pain tool.
Once we have identified the tumor and brain we can manually interpolate then and merge the two different labeled slice regions together and interpolate them. After interpolation the part from beginning slice to ending slice shows the tumor highlighted. With this we can identify the tumors in the brain and highlight them for further study.

![region 1 Manual interpolation](https://github.com/Cosmic1509/Fifth-semester-MATLAB-project/assets/82835887/5204e006-3fb3-4b6f-bc72-314a957b8bb8)


**SOFTWARE/HARDWARE USED:**
- MATLAB and Simulink 9.9.0
- Windows 10 laptop/computer with MATLAB
- Image processing toolbox within MATLAB

![image](https://github.com/Cosmic1509/Fifth-semester-MATLAB-project/assets/82835887/5e38d93b-787d-4e76-9287-854bc8b64461)





