---
title: "Watch me, but don't touch me! contactless control flow monitoring via electromagnetic emanations"
authors:
- Yi Han
- admin
- Hua Liu
- Saman Zonouz
- Athina Petropulu

date: "2017-10-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2017 ACM SIGSAC conference on computer and communications security*
publication_short: In *CCS*

abstract: Trustworthy operation of industrial control systems depends on secure and real-time code execution on the embedded programmable logic controllers (PLCs). The controllers monitor and control the critical infrastructures, such as electric power grids and health-care platforms, and continuously report back the system status to human operators. We present Zeus, a contactless embedded controller security monitor to ensure its execution control low integrity. Zeus leverages the electromagnetic emission by the PLC circuitry during the execution of the controller programs. Zeus’s contactless execution tracking enables non-intrusive monitoring of security-critical controllers with tight real-time constraints. Those devices often cannot tolerate the cost and performance overhead that comes with additional traditional hardware or software monitoring modules. Furthermore, Zeus provides an air-gap between the monitor (trusted computing base) and the target (potentially compromised) PLC. This eliminates the possibility of the monitor infection by the same attack vectors. Zeus monitors for control low integrity of the PLC program execution. Zeus monitors the communications between the human-machine interface and the PLC, and captures the control logic binary uploads to the PLC. Zeus exercises its feasible execution paths, and ingerprints their emissions using an external electromagnetic sensor. Zeus trains a neural network for legitimate PLC executions, and uses it at runtime to identify the control low based on PLC’s electromagnetic emissions. We implemented Zeus on a commercial Allen Bradley PLC, which is widely used in industry, and evaluated it on real-world control program executions. Zeus was able to distinguish between diferent legitimate and malicious executions with 98.9% accuracy and with zero overhead on PLC execution by design.

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