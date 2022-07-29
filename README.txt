RoPS code
Copyright (c) 2013 Yulan Guo

* The code is used to extract RoPS features on point-clous and meshes.
* The code is provided by Yulan Guo (yulan.guo<AT>nudt.edu.au).

* Reference: Yulan Guo, Ferdous Sohel, Mohammed Bennamoun, Min Lu, Jianwei Wan. 
	     Rotational Projection Statistics for 3D Local Surface Description and Object Recognition. 
	     Internation Journal of Computer Vision. 2013, 105 (1), 63-86

* Description:
(1) demo_RoPS_Extraction_Mesh: This function extracts RoPS local features on a mesh (converted from an input point-cloud)
(2) demo_RoPS_Extraction_Pointcloud: This function extracts RoPS local features on an input point-cloud
(3) demo_RoPS_FeatureMatching_Mesh: This function performs feature matching on two input meshes to obtain feature correspondences

* Requirements:
(1) The files "check_face_vertex.m" and "compute_edges.m" are required. They are included in the toolbox_graph 
(http://www.mathworks.com.au/matlabcentral/fileexchange/5355-toolbox-graph)

* Feedback:
Any suggestions or comments are welcome.
