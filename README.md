
## Point-E - Point Cloud Generation Adaptation

--- 
This project is an adapatation of OpenAI's open source Point-E model for generating point clouds from images or text prompts. The notebook includes preprocessing, generation steps, and basic visualization.
For example if you prompt "An Apple" you will get a 3D visual point cloud interpretation of an Apple!
The Adaptation allows for centralized further plot looping through all the outputs and inspecting if the model interpreted the prompt/image well and organizing the XYZ coordinates and optional RGB colors for 3D plotting and further customizing the size, color scale, transparency and lighting. In addition to exporting as an obj to get a solid respresentation of the plot generated! 

---

## Try it out in Google Colab as primarily built here!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/RGithub23/PointEPointCloudGenerationAdaptation/blob/main/PointE_PointCloud_Generation_Adaptation.ipynb)



---

## Contents

- `PointE_PointCloud_Generation_Adaptation.ipynb`: Jupyter notebook

---

## Features

- Prompt your own Object you want generated
- Generate and visualize 3D point clouds
- Customize sampling parameters
- OBJ export support

---

## Requirements

This Colab notebook automatically installs all necessary dependencies, including:
torch
open3d
plotly
point-e @ git+https://github.com/openai/point-e.git


---

## 📝 License

MIT License or your preferred license.
Attribution to OpenAI for access to their open source model. 
