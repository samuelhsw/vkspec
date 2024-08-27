# Vulkan / D3D Specifications
It was a nightmare when I first looked at both specifications to figure out the "delta" based on my knowledge of GPU architecture/driver/compiler and what I've been educated by the developers. I intend to keep updating this going forward as I learned about new details in this space. I am sure there are even more corners to cover, so if you see something that should be added, corrected, etc. please pull requests.
|| Vulkan|D3D
|-|-|-
|Robustness| robustImageAccess (VK_EXT_image_robustness) 
|| robustBufferAccess                          
|VK_EXT_robustness2|3 new robustness features (___performance cost___)| supported              
|VK_EXT_pipeline_robustness|allow ISV to request robustness where needed on a per pipeline stage basis

