# Executable Environment for OSF Project [42nyv](https://osf.io/42nyv/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Young Infants' Attentional Preference for Social Interactions

**Project Description:**
> In this study we show that 9.5- to 11-month-old infants (n = 20), but not 7- to 8.5- month-olds (n = 20), look longer at videos showing two adults interacting with one another when simultaneously presented with a scene showing the same agents acting individually. Moreover, older infants showed higher social engagement during free play with their parent.  

Note: In the published study (https://doi.org/10.1111/cdev.13636), we refer to this project as “Experiment 1”. This OSF project is directly linked to the OSF project "Follow-up Study: Young infants' attentional preference for social interactions" (https://osf.io/s4uy7/). The supplemental information document contains information regarding both studies (referring to the two studies as "Experiment 1" and "Experiment 2"). In the follow-up OSF project, we provide data and scripts for additional analyses over a merged sample (combining the original sample from this project with the sample collected for the follow-up study). 

**Original OSF Page:** [https://osf.io/42nyv/](https://osf.io/42nyv/)

---

**Important Note:** The contents of the `42nyv_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_42nyv/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_42nyv/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `42nyv_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-42nyv:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-42nyv
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.
