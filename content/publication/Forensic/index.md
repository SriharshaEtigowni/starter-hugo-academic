---
title: "Forensic Investigation of Industrial Control Systems Using Deterministic Replay"
authors:
- Gregory Walkup
- admin
- Dongyan Xu
- Vincent Urias
- Han W Lin

date: "2020-06-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2020 IEEE Conference on Communications and Network Security (CNS)*
publication_short: In *CNS*

abstract: From manufacturing plants to power grids, industrial control systems are increasingly controlled and networked digitally. While networking these systems together improves their efficiency and convenience to control, it also opens them up to attacks by malicious actors. When these attacks occur, forensic investigators should be able to determine what was compromised and which corrective actions need to be taken. In this paper, we propose a method to investigate attacks on industrial control systems by simulating the logged inputs of the system over time using a model constructed from the control programs. We detect any attacks that will lead to perturbations of the normal operation of the system by comparing the simulated output to the actual output. We also perform dependency tracing between the inputs and outputs of the system, so that attacks can be traced from the anomaly to their sources and vice-versa. Our method can greatly aid investigators in recovering the complete attack graph used by the attacker using only the input and output logs from an industrial control system. To evaluate our method, we constructed a hybrid testbed with a simulated version of the Simplified Tennessee Eastman process, using a hardware-inthe-loop Allen-Bradley Micrologix 1100 PLC. We were able to accurately detect all attack anomalies with a false positive rate of 0.3% or less.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Cyber-Physical Security


---