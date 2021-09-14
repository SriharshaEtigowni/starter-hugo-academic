---
title: "Cyber-air-gapped detection of controller attacks through physical interdependencies"
authors:
- admin
- Mehmet Cintuglu
- Maryam Kazerooni
- Shamina Hossain
- Pengfei Sun
- Katherine Davis
- Osama Mohammed
- Saman Zonouz

date: "2017-10-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2017 IEEE International Conference on Smart Grid Communications (SmartGridComm)*
publication_short: In *SmartGridComm*

abstract: Trustworthy operation of the power grid critical infrastructures requires real-time intrusion detection systems to identify compromised and malfunctioning controller devices. The past three decades of direct application of the traditional purely cyber security solutions against these infrastructures has proved insufficient in practice due to emerging sophisticated malicious attacks against power grid control systems. In this paper, we propose PhiDS, a physics-aware intrusion detection system to identify compromised controllers through continuous observation of remote power system sensor measurements. Real-time remote sensor data analysis enables PhiDS to determine the power system state trajectory and infer the control commands issued by the distributed controllers on the plant. Given the power system safety requirements, PhiDS monitors the data stream and identifies the controllers that issue control commands that violates the safety of the power system. PhiDS does not require any cyber communication with the (potentially compromised) controller devices, and hence provides an air-gap between the the security monitor and the target device. Consequently, if the controller is infected, the adversary cannot compromise and corrupt the monitor’s reports. The will ensure that the monitor will always remain away from the adversaries’ access and hence provide trustworthy reports. We implemented and evaluated PhiDS on a real-world power system test-bed, where the programmable logic controllers are targets for and attacked by the remote network adversaries. PhiDS was able to identify all the infected controllers efficiently without any cyber link to the controllers. PhiDS’s outcomes were instead purely based on the power system measurements from sensors that are deployed adjacent to the controllers.

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