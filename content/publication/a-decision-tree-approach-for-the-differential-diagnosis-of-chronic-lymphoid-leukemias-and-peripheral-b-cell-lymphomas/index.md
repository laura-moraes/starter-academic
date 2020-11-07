---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Decision Tree Approach for the Differential Diagnosis of Chronic Lymphoid Leukemias and Peripheral B Cell Lymphomas"
authors: ["Laura O. Moraes", "Carlos Eduardo Pedreira"]
date: 2019-06-13T17:22:27-03:00
doi: "10.1016/j.cmpb.2019.06.014"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-11-07T17:22:27-03:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computer Methods and Programs in Biomedicine, v. 178, p. 85-90"
publication_short: ""

abstract: "**Background and Objective**

Here we propose a decision-tree approach for the differential diagnosis of distinct WHO categories B-cell chronic lymphoproliferative disorders using flow cytometry data. Flow cytometry is the preferred method for the immunophenotypic characterization of leukemia and lymphoma, being able to process and register multiparametric data about tens of thousands of cells per second.
**Methods**

The proposed decision-tree is composed by logistic function nodes that branch throughout the tree into sets of (possible) distinct leukemia/lymphoma diagnoses. To avoid overfitting, regularization via the Lasso algorithm was used. The code can be run online at https://codeocean.com/2018/03/08/a-decision-tree-approach-for-the-differential-diagnosis-of-chronic-lymphoid-leukemias-and-peripheral-b-cell-lymphomas/ or downloaded from https://github.com/lauramoraes/bioinformatics-sourcecode to be executed in Matlab.
**Results**

The proposed approach was validated in diagnostic peripheral blood and bone marrow samples from 283 mature lymphoid leukemias/lymphomas patients. The proposed approach achieved 95% correctness in the cross-validation test phase (100% in-sample), 61% giving a single diagnosis and 34% (possible) multiple disease diagnoses. Similar results were obtained in an out-of-sample validation dataset. The generated tree reached the final diagnoses after up to seven decision nodes.
**Conclusions**

Here we propose a decision-tree approach for the differential diagnosis of mature lymphoid leukemias/lymphomas which proved to be accurate during out-of-sample validation. The full process is accomplished through seven binary transparent decision nodes."

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

url_pdf:
url_code: "https://codeocean.com/capsule/3819686/tree/v1"
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Relative weight importance of each of the individual markers (features) used to separate between distinct diagnostic categories of leukemia/lymphoma at each node of the decision-tree"
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
