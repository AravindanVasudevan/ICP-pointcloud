# ICP pointcloud

This project is an implementation of the Iterative Closest Point (ICP) algorithm using the open3d library in Python. The ICP algorithm is a widely used technique in computer vision and robotics for aligning two-point clouds by finding the best rigid transformation that aligns the points in one cloud to those in the other.

The image shows the 2 point cloud before ICP:

![Q2-b(a)](https://github.com/AravindanVasudevan/ICP-pointcloud/assets/57245944/ba7b91ef-1adb-4962-aa05-c56549b76720)

The implementation of this project uses the KDTree algorithm from the open3d library to efficiently find the nearest neighbors in the two-point clouds. The KDTree algorithm is a data structure that allows for fast nearest neighbor searches in high-dimensional spaces.

To use the ICP algorithm in this project, simply provide two-point clouds as inputs. The algorithm will iteratively refine the transformation between the two clouds until a satisfactory alignment is achieved. The resulting transformation matrix can be used to transform one point cloud onto the other.

The image below shows the 2 point cloud after ICP:

![Q2-a(a)](https://github.com/AravindanVasudevan/ICP-pointcloud/assets/57245944/7e3f6fde-7b87-418b-bacd-22dfb91d8885)
