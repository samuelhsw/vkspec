# Vulkan / D3D Specifications
As a contributor to the Vulkan specification, it was a nightmare when I first looked at both specifications to figure out the "delta" based on my knowledge of GPU architecture/driver/compiler and what I've been educated by the developers. If you feel the same pain and then I hope this document might be a cure. 
|| Vulkan|D3D
|-|-|-
|Robustness| robustImageAccess (VK_EXT_image_robustness) 
|| robustBufferAccess                          
|VK_EXT_robustness2|3 new robustness features (___performance cost___)| supported              
|VK_EXT_pipeline_robustness|allow ISV to request robustness where needed on a per pipeline stage basis

