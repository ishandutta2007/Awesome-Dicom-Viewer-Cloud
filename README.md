# Awesome-Dicom-Viewer-Cloud

## Top DICOM Viewer Cloud Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cloud-Based Medical Imaging, Zero-Footprint Viewing & PACS Integration*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud DICOM Viewing**. These tools enable radiologists, clinicians, and researchers to access, view, and share medical imaging studies (CT, MRI, PET, X-ray) from any device without installing heavyweight desktop software.



**Examples** include PostDICOM, Medicai, Ambra Health, MedDream, RadiAnt Cloud, MicroDicom Cloud, Visage Imaging, OsiriX Cloud, Horos Cloud, and Philips IntelliSpace (the category leaders).



**Open-source emphasis**: DICOM is an open standard, and the open-source ecosystem is exceptionally strong. **OHIF Viewer**, **Weasis**, **Orthanc**, and **Horos** form the backbone of self-hosted medical imaging worldwide . This section is heavily expanded with active projects for zero-footprint viewing, PACS servers, and clinical research workflows.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[PostDICOM](https://www.postdicom.com/)**  

  Cloud-based DICOM viewer and PACS with instant access, sharing capabilities, and integrations for healthcare providers.



- **[Medicai](https://medicai.io/)**  

  Collaborative medical imaging platform for clinics and hospitals with cloud PACS, DICOM viewer, and telemedicine features.



- **[Ambra Health](https://ambrahealth.com/)**  

  Cloud medical image management platform (now part of Intelerad) providing DICOM viewing, sharing, and PACS integration.



- **[MedDream](https://www.meddream.com/)**  

  Zero-footprint DICOM viewer with web-based access, supporting multiple modalities and PACS connectivity.



- **[RadiAnt Cloud](https://www.radiantviewer.com/)**  

  Cloud offering from the RadiAnt DICOM Viewer team, providing accessible medical image viewing.



- **[MicroDicom Cloud](https://www.microdicom.com/)**  

  Cloud extension of the popular MicroDicom viewer, enabling web-based access to DICOM studies.



- **[Visage Imaging](https://visageimaging.com/)**  

  Enterprise imaging platform with cloud-based diagnostic viewer and advanced visualization capabilities.



- **[OsiriX Cloud](https://www.osirix-viewer.com/)**  

  Cloud services around the OsiriX ecosystem for macOS-based medical imaging.



- **[Horos Cloud](https://horosproject.org/)**  

  Cloud plugin and services for the Horos open-source DICOM viewer, enabling cloud-based image access and storage .



- **[Philips IntelliSpace](https://www.philips.com/healthcare)**  

  Enterprise imaging and informatics platform with cloud viewing and advanced clinical applications.



## Open-Source GitHub Projects



- **[OHIF Viewer](https://github.com/OHIF/Viewers)**  

  The leading open-source zero-footprint DICOM viewer with 4,300+ stars, actively maintained by the Open Health Imaging Foundation . Extensible platform supporting multiple data sources (DICOMweb, DICOM JSON), oncology-specific tools, segmentation, and measurement. Integrates with **Orthanc**, **DCM4CHEE**, and **Google Cloud Healthcare API** . **The de facto standard for web-based medical imaging** .



- **[Weasis](https://github.com/nroduit/Weasis)**  

  Web-based DICOM viewer for advanced medical imaging and seamless PACS integration, with 1,300+ stars . Cross-platform desktop and web deployment, supporting MPR, volume rendering, and DICOM network protocols. Integrates with Google Cloud Healthcare API .



- **[Orthanc](https://github.com/jodogne/Orthanc)**  

  Lightweight, open-source DICOM server for medical imaging informatics, born at University Hospital of Liège in 2012 . Single executable with embedded SQLite, RESTful API, and rich plugin system. Used as ancillary DICOM server in clinical environments, full PACS in low-resource hospitals, and AI data curation pipelines. Plugins provide built-in web viewers including **OHIF**, **VolView**, and **3D Surface** .



- **[Horos](https://github.com/horosproject/horos)**  

  Free, open-source DICOM viewer for macOS with 1M+ users globally . Fully featured with 3D surface rendering, PET/CT fusion, SUV measurement, and OsiriX migration assistant . **HorosCloud Plugin** enables cloud-based image access and storage . Sponsored by Purview for nearly a decade .



- **[dcm4chee-arc-light](https://github.com/dcm4che/dcm4chee-arc-light)**  

  Open-source clinical DICOM archive (PACS) implementing DICOM standard with storage, retrieval, and workflow services. Docker deployment available. Integrates with OHIF and Google Cloud Healthcare API .



- **[DWV (DICOM Web Viewer)](https://github.com/ivmartel/dwv)**  

  Open-source zero-footprint medical image library with 1,800+ stars, supporting DICOM, and multiple image formats . Lightweight JavaScript implementation for web-based viewing.



- **[Cornerstone.js](https://github.com/cornerstonejs/cornerstone)**  

  JavaScript libraries for building web-based medical imaging applications, forming the foundation for OHIF Viewer and many other DICOM web tools .



- **[dcmjs](https://github.com/dcmjs-org/dcmjs)**  

  JavaScript implementation of DICOM manipulation with 350+ stars, providing parsing, encoding, and DICOMweb client capabilities .



- **[Voxenra](https://github.com/l5769389/voxenra)**  

  Cross-platform DICOM workstation for CT, MR, and PET/CT with MPR, 3D volume rendering, fusion, segmentation, and DICOM SEG/SR export . macOS and Windows support with dark/light themes.



- **[MedImager](https://github.com/1985312383/MedImager)**  

  Modern, cross-platform open-source DICOM viewer and medical image analysis tool with Python 3.11+ and PySide6 . Features study workspace, cross-series reading, MPR, and DICOMDIR support.



- **[VisorDicom](https://github.com/Zargantana/VisorDicom)**  

  Open-source Angular-native DICOM viewer (Angular 18) running in production, Apache 2.0 licensed . Web-based with responsive interface and compression format support.



### Additional Strong Open-Source Options



- **dicom-toolkit** — Simple DICOM toolkit based on fo-dicom .

- **dcmbrowser** — Lightweight DICOM file browser and preview manager .

- **dicom-viewer** — Simple Go-based cross-platform DICOM viewer .

- **u-dicom-viewer** — Simple web browser DICOM viewer for any device .

- **3DimViewer** — Lightweight multiplatform 3D viewer for volumetric DICOM data with MPR views .

- **SightViewer** — DICOM viewer with negatoscope, MPR, and volume rendering, connects directly to PACS .



**Frameworks for building custom cloud DICOM solutions**: Combine **OHIF Viewer** for zero-footprint web viewing with **Orthanc** or **DCM4CHEE** as the backend PACS server . Deploy **Horos** with **HorosCloud Plugin** for macOS-based clinical workflows . Use **Weasis** for desktop-integrated viewing with direct PACS connectivity . For research and AI pipelines, **Orthanc**'s plugin architecture and RESTful API enable custom anonymization, routing, and analysis workflows . Note that true enterprise cloud DICOM platforms with managed SLAs, multi-region availability, and HIPAA compliance certifications remain primarily commercial territory; open-source stacks provide strong viewing, storage, and integration foundations that require infrastructure management and security hardening for clinical deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- DICOM viewers and PACS handle protected health information (PHI) and must comply with HIPAA, GDPR, and applicable medical device regulations. Self-hosted solutions require proper security hardening, encryption at rest and in transit, and audit logging.

- Cloud DICOM platforms may be regulated as medical devices in some jurisdictions. Validate regulatory status before clinical use.

- The open-source ecosystem provides strong viewing, storage, and integration foundations, but managed SLAs, multi-region availability, and compliance certifications remain primarily commercial offerings.



---



**Made for radiologists, clinical IT teams, medical imaging researchers, and healthcare developers.**  

Let's make cloud DICOM viewing more open, transparent, and accessible.
