---
title: "GANFIT: Generative Adversarial Network Fitting for High Fidelity 3D Face Reconstruction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- B Gecer
- S Ploumpis 
- I Kotsia
- S Zafeiriou

# Author notes (optional)
#author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2019-06-20"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-20"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer Vision and Pattern Recognition*
publication_short: In *CVPR*

summary: Proceedings of the IEEE *Conference on Computer Vision and Pattern Recognition (**CVPR**), 2019*

abstract: In the past few years, a lot of work has been done towards reconstructing the 3D facial structure from single images by capitalizing on the power of Deep Convolutional Neural Networks (DCNNs). In the most recent works, differentiable renderers were employed in order to learn the relationship between the facial identity features and the parameters of a 3D morphable model for shape and texture. The texture features either correspond to components of a linear texture space or are learned by auto-encoders directly from in-the-wild images. In all cases, the quality of the facial texture reconstruction of the state-of-the-art methods is still not capable of modeling textures in  high fidelity. In this paper, we take a radically different approach and harness the power of Generative Adversarial Networks (GANs) and DCNNs in order to reconstruct the facial texture and shape from single images. That is, we utilize GANs to train a very powerful generator of facial texture in UV space. Then, we revisit the original 3D Morphable Models (3DMMs) fitting approaches making use of non-linear optimization to find the optimal latent parameters that best reconstruct the test image but under a new perspective. We optimize the parameters with the supervision of pretrained deep identity features through our end-to-end differentiable framework. We demonstrate excellent results in photorealistic and identity preserving 3D face reconstructions and achieve for the first time, to the best of our knowledge, facial texture reconstruction with high-frequency details.

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
url_code: "https://github.com/barisgecer/ganfit"
url_pdf: "https://openaccess.thecvf.com/content_CVPR_2019/papers/Gecer_GANFIT_Generative_Adversarial_Network_Fitting_for_High_Fidelity_3D_Face_CVPR_2019_paper.pdf"
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
