---
title: "Towards a better gold standard: Denoising and modelling continuous emotion annotations based on feature agglomeration and outlier regularisation"
authors:
- admin
- Phil Lopes, Thierry Pun, Guillaume Chanel
date: "2018-10-15"
doi: "https://doi.org/10.1145/3266302.3266307"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-10-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2018 on Audio/Visual Emotion Challenge and Workshop*
publication_short: In *ACMMM*

abstract: Emotions are often perceived by humans through a series of multimodal cues, such as verbal expressions, facial expressions and gestures. In order to recognise emotions automatically, reliable emotional labels are required to learn a mapping from human expressions to corresponding emotions. Dimensional emotion models have become popular and have been widely applied for annotating emotions continuously in the time domain. However, the statistical relationship between emotional dimensions is rarely studied. This paper provides a solution to automatic emotion recognition for the Audio/Visual Emotion Challenge (AVEC) 2018. The objective is to find a robust way to detect emotions using more reliable emotion annotations in the valence and arousal dimensions.
The two main contributions of this paper are: 1) the proposal of a new approach capable of generating more dependable emotional ratings for both arousal and valence from multiple annotators by extracting consistent annotation features; 2) the exploration of the valence and arousal distribution using outlier detection methods, which shows a specific oblique elliptic shape. With the learned distribution, we are able to detect the prediction outliers based on their local density deviations and correct them towards the learned distribution. The proposed method performance is evaluated on the RECOLA database containing audio, video and physiological recordings. Our results show that a moving average filter is sufficient to remove the incidental errors in annotations. The unsupervised dimensionality reduction approaches could be used to determine a gold standard annotations from multiple annotations. Compared with the baseline model of AVEC 2018, our approach improved the arousal and valence prediction of concordance correlation coefficient significantly to respectively 0.821 and 0.589.

# Summary. An optional shortened abstract.
summary:


url:
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
url_dataset: 'https://diuf.unifr.ch/main/diva/recola/news.html'
# url_poster: '#'
url_project: 'https://sites.google.com/view/avec2018#h.p_scd-pNRIZ5mp'
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#focal_point: ""
#preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

