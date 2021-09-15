---
title: "Physics-Aware Security Monitoring against Structural Integrity Attacks in 3D Printers"
authors:
- admin
- Sizhuang Liang
- Saman Zonouz
- Raheem Beyah

date: "2021-06-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-06-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2021 51st Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)*
publication_short: In *DSN*

abstract: STereoLithography (STL) files describe the geometry of objects to be printed in additive manufacturing. Previous studies have shown that the STL files that describe functional objects can be attacked such that the objects appear normal during inspection, but fail during operation. Such attacks lead to damage to systems that use the objects and possibly loss of life. The detection of any defects caused due to the attacks nowadays is limited to the quality control process after the objects are manufactured.We present a Trusted Integrity Verifier (TIV) to detect such attacks on 3D printed objects in the early stage of the manufacturing process. These type of new attacks cannot be detected by traditional software security mechanisms since they only focus on the printers and do not consider the inputs (STL design files) to the printer. Early detection of attacks prevents from printing malicious objects resulting in saving time, resources and manufacturing efforts. TIV detects malicious STL files using multidisciplinary approaches unlike the traditional integrity verification techniques. TIV develops a void detection module based on computer vision techniques to identify the internal defects such as voids. Some of these features could be from the design and some could be due to the attack. To differentiate the malicious features from the design features, TIV develops safety verification module based on a numerical method. TIV’s safety verification module is used to differentiate the malicious features from the design features by calculating the load bearing mechanical stress on the objects. These mechanical stresses are compared to the safety operational conditions to determine if the printed object will break or fail during its normal operation.To illustrate TIV’s generality and scalability, we conducted a large-scale analysis on 16,000 real-world 3D print STL files. TIV verified the STL files successfully as either safe or malicious with high accuracy of 92% for object classification and 96.5% for void detection.


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