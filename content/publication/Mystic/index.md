---
title: "Physical Logic Bombs in 3D Printersvia Emerging 4D Techniques"
authors:
- Tuan Le
- admin
- Sizhuang Liang
- Xirui Peng
- Jerry Qi
- Mehdi Javanmard
- Saman Zonouz
- Raheem Beyah

date: "2021-12-03T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 34nd annual conference on computer security applications*
publication_short: In *ACSAC*

abstract: Rapid prototyping makes additive manufacturing (or 3D printing)useful in critical application domains such as aerospace, automotive, and medical. The rapid expansion of these applications should prompt the examination of the underlying security of 3D printed objects. In this paper, we present Mystiqe, a novel class of stealthy attacks on printed objects that leverage the fourth dimension of emerging 4D printing technology to introduce embedded logic bombs through manufacturing process manipulation. Mystiqe enables visually benign objects to behave maliciously upon the activation of the logic bomb during operation. It leverages the manufacturing process to embed a physical logic bomb that can be triggered with specifc stimuli to change the physical and mechanical properties of the printed objects. These changes in properties can potentially cause catastrophic operational failures when the objects are used in critical applications such as drones, prosthesis,or medical applications. We successfully evaluated Mystiqe on several 3D printing case studies and showed that Mystiqe can evade prior countermeasures. To address this, we propose two mitigation strategies to defend against Mystiqe. The first solution focuses on detecting the change of materials such as filament diameters and composition before printing. A dielectric sensor circuit is designed to quantify filament diameters and concentration composition changes. The dielectric sensor can detect a change of 0.1mm in filament diameters and a change of 10% in concentration composition. The second solution attempts to detect 4D attacks by examining the printed object using imaging techniques. To be specifc, we performed data-driven classiication on high resolution CT images of printed objects. This detection has an accuracy of 94.6% in identifying 4D attacks in a single printing layer.


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