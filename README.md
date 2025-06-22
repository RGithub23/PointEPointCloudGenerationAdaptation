
## Point-E - Point Cloud Generation Adaptation

This project is an adapatation of OpenAI's Point-E model for generating point clouds from images or text prompts. The notebook includes preprocessing, generation steps, and basic visualization.
For example if you prompt "Apple" you will get a 3D visual point cloud of an Apple!
Adaptation allows for centralized further plot looping through all the outputs and inspecting if the model interpreted the prompt/image well and organizing the XYZ coordinates and optional RGB colors for 3D plotting and further customizing the size, color scale, transparency and lighting. In addition to exporting as an obj to get a solid respresentation of the plot generated!

---

## Try it out in Google Colab as primarily built here!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RGithub23/PointE-PointCloud-Generation-Adaptation/blob/main/PointE-PointCloud-Generation-Adaptation.ipynb)


---

## Contents

- `PointEPointCloudGenerationAdaptation.ipynb`: Jupyter notebook

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
