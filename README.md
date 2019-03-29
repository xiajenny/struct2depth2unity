# struct2depth2unity
Research project exploring using struct2depth tensorflow library to generate depth mapping for usage in Unity.

## Workflow for single frame
1. Run model on desired dataset -> output of rgbd image and numpy array (x,y,d) pixel to depth mapping
2. Generate point cloud, translate pixel depth mapping to real depth mapping (x,y,z) data (requires camera intrinsics) 
3. Create mesh using MeshLab
4. Import into Unity

## Next steps: visual odometry, combining data from multiple frames
