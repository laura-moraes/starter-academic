---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Classificação de Linfomas Utilizando uma Abordagem Baseada em Árvores De Decisão"
authors: ["Laura O. Moraes", "Carlos Eduardo Pedreira"]
date: 2016-03-13T18:45:20-03:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-07T18:45:20-03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "Dissertação (Mestrado em Engenharia de Sistemas e Computação) - COPPE, Universidade Federal do Rio de Janeiro (UFRJ), Rio de Janeiro"
publication_short: ""

abstract: "This work presents a methodology to support lymphoma diagnosis. A
decision tree approach is proposed to perform a lymphoma differential diagnosis
using flow cytometry data. Differential diagnosis is to select or eliminate
lymphomas among some possible predefined categories. Flow cytometers are
equipments used to diagnose lymphoma among other diseases. It is possible to
monitor thousands of cells and their parameters simultaneously. It generates
individualized information about each cell using patient's peripheral blood or
bone marrow sample. The proposed method builds the tree using in each node a
regularized logistic regression algorithm called Lasso. It analyzes multiple
combinations of attributes in each decision step in order to choose or
eliminate classes for the differential diagnosis. The tree approach was chosen
because the final decision is made by a human specialist and its representation
is easy to understand. A key project requirement is to avoid false negatives.
To accomplish this goal, two procedures were added while constructing the tree.
Their objective is to double check the outcome and add extra possible outcomes
to the diagnosis given to the decision maker. The parameters monitored in the
cytometer and used as attributes in the predictor model are actually monoclonal
antibodies with an associated high cost. Therefore, motivated by the antibodies
cost and also the result quality, another research in this dissertation is to
analyze if these antibodies can be used in a partial way. Cross-validation and
leave-one-out techniques and a test dataset containing observations not used in
training were used to validate the model. The results given by this approach
are compatible with those expected by the specialists."

# Summary. An optional shortened abstract.
summary: ""

tags: ["Classification", "Flow Cytometry", "Decision tree"]
categories: ["Classification", "Flow Cytometry", "Decision tree"]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://www.cos.ufrj.br/uploadfile/publicacao/2595.pdf"
url_code: "https://codeocean.com/capsule/3819686/tree/v1"
url_dataset:
url_poster:
url_project:
url_slides: "classificacao-de-linfomas-utilizando-uma-abordagem-baseada-em-arvores-de-decisao.pptx"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Esquemático de um citômetro"
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ["lasso-tree"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
