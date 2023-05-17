---
title: "Neural Mesh Simplification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- RA Potamias
- S Ploumpis 
- S Zafeiriou

# Author notes (optional)
#author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-06-24"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-06-24"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

summary: To appear in Proceedings of the IEEE *Conference on Computer Vision and Pattern Recognition (**CVPR**), 2022*

abstract: Despite the advent in rendering, editing and preprocessing methods of 3D meshes, their real-time execution remains still infeasible for large-scale meshes. To ease and accelerate such processes, mesh simplification methods have been introduced with the aim to reduce the mesh resolution while preserving its appearance. In this work we attempt to tackle the novel task of learnable and differentiable mesh simplification. Compared to traditional simplification approaches that collapse edges in a greedy iterative manner, we propose a fast and scalable method that simplifies a given mesh in one-pass. The proposed method unfolds in three steps. Initially, a subset of the input vertices is sampled using a sophisticated extension of random sampling. Then, we train a sparse attention network to propose candidate triangles based on the edge connectivity of the sampled vertices. Finally, a classification network estimates the probability that a candidate triangle will be included in the final mesh. The fast, lightweight and differentiable properties of the proposed method makes it possible to be plugged in every learnable pipeline without introducing a significant overhead. We evaluate both the sampled vertices and the generated triangles under several appearance error measures and compare its performance against several state-of-the-art baselines. Furthermore, we showcase that the running performance can be up to 10x faster than traditional methods. 

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
#url_code: "https://github.com/steliosploumpis/3D_human_tongue_reconstruction"
url_pdf: "https://openaccess.thecvf.com/content/CVPR2022/papers/Potamias_Neural_Mesh_Simplification_CVPR_2022_paper.pdf"
#url_dataset: "https://github.com/steliosploumpis/3D_human_tongue_reconstruction#public-release-tongue-dataset"
#url_slides: ""
#url_video: "https://www.youtube.com/watch?v=fNlMGWm7bbk&t=4700s"

# url_pdf: 'https://openaccess.thecvf.com/content_CVPR_2019/papers/Ploumpis_Combining_3D_Morphable_Models_A_Large_Scale_Face-And-Head_Model_CVPR_2019_paper.pdf'
# url_code: 'https://github.com/steliosploumpis/Universal_Head_3DMM'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: 'https://www.youtube.com/watch?feature=player_embedded&v=fNlMGWm7bbk&t=4700s'

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ""
#   preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - example

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---
