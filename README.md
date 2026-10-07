<a href="https://guilhem0908.github.io"><img src="assets/banner.svg" width="100%" alt="Guilhem Carmouze, robotics engineering student: 3D Gaussian Splatting, 360° vision, robot navigation"></a>

Final-year robotics engineering student at **UPSSITECH** (University of Toulouse, *Systèmes Robotiques et Interactifs*). I work on **3D Gaussian Splatting, 360° vision and robot navigation**, and spent spring and summer 2026 as a research intern at **AIST** in Tsukuba, Japan.

**Looking for a 6-month end-of-studies internship from March 2027** in robotics, 3D vision or autonomous navigation.

[Portfolio](https://guilhem0908.github.io) · [CV](https://guilhem0908.github.io/cv/) · [LinkedIn](https://www.linkedin.com/in/guilhem-carmouze/) · [Email](mailto:l7guilhem@gmail.com)

## Research internship at AIST, Japan (April to August 2026)

**Creation of a 360° navigation dataset using 3D Gaussian Splatting**, Computer Vision Research Team, Artificial Intelligence Research Center. [Read the case study](https://guilhem0908.github.io/work/aist-360-navigation/).

<a href="https://github.com/guilhem0908/artifixer-360-pipeline"><img src="assets/aist-artifixer-360.jpg" width="100%" alt="The same 360° panorama twice: on the left the raw 3D Gaussian render, full of artefacts; on the right the repaired output"></a>

| Repository | What it does |
| :-- | :-- |
| **[artifixer-360-pipeline](https://github.com/guilhem0908/artifixer-360-pipeline)** | Plain pinhole video to repaired 360° video: a world-locked rig of 14 views, depth-aware multi-view diffusion consensus and geometry-locked distillation, built on NVIDIA ArtiFixer (+23,602 lines, 119 new tests). Temporal warp error 0.037 to 0.020 on the reference run; the full 154-frame run failed my own acceptance gates, and the repository documents why. |
| **[nav_3dgs_pano](https://github.com/guilhem0908/nav_3dgs_pano)** | Navigation and panoramic rendering inside a 3DGS scene (DISCOVERSE, MuJoCo): occupancy grid, A*, feathered cubemap-to-equirectangular stitching. |
| **[KachakaNavigation](https://github.com/guilhem0908/KachakaNavigation)** | ROS 2 Humble robot-side interface for a visual navigation model on the Kachaka robot: stale-frame checks, clamped velocity, dead-man timer. |

## Team projects

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/TLSe_Racing_Driverless"><img src="assets/tlse.jpg" width="100%" alt="Top-down view of a cone track with the car, its field-of-view sector and the driven line"></a>
<b>TLSe Racing, Formula Student driverless</b> (2025 to 2026)<br>
I built the 2D simulator and tooling: sensor model, track loader, viewer. Teammates wrote the planners.<br>
<a href="https://github.com/guilhem0908/TLSe_Racing_Driverless">TLSe_Racing_Driverless</a> · <a href="https://github.com/guilhem0908/PathPlanning">PathPlanning</a>
</td>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/PFR2"><img src="assets/fil-rouge.jpg" width="100%" alt="A small four-wheel robot next to its live LiDAR scan and the map built from it"></a>
<b>Projet Fil Rouge</b> (2024 to 2025)<br>
A real mobile robot built by a team of six. My part: the web Bluetooth HMI, the camera stream and the ball-centring control. Before that, a colour-ball detector in pure C, written with Alec Bossard.<br>
<a href="https://github.com/guilhem0908/PFR2">PFR2</a> (team repository) · <a href="https://github.com/guilhem0908/PFR">PFR</a>
</td>
</tr>
</table>

**Usine 4.0** (Industry 4.0 smart factory): final-year team project, in progress (2026 to 2027).

## Side projects

Personal studies from October 2026 that extend themes of my internship. They were built with AI assistance, and every number in their READMEs is reproduced by a script in the repository.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/microsplat"><img src="assets/microsplat.jpg" width="100%" alt="Target, render, error and projected ellipses of a small Gaussian-splat scene"></a>
<b><a href="https://github.com/guilhem0908/microsplat">microsplat</a></b><br>
3D Gaussian Splatting from scratch: a NumPy reference rasteriser, a differentiable PyTorch twin, and tests that pin every equation. 33.6 dB PSNR on held-out views of a ray-traced scene.
</td>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/amr-traffic-lab"><img src="assets/amr-traffic-lab.jpg" width="100%" alt="Two replays of a factory floor: robots gridlocked in a corridor on the left, flowing on the right"></a>
<b><a href="https://github.com/guilhem0908/amr-traffic-lab">amr-traffic-lab</a></b><br>
Usine 4.0 intralogistics: how many mobile robots can an aisle take before it jams? The reservation-based traffic manager never gridlocked in 600 simulated one-hour runs.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/erpkit"><img src="assets/erpkit.jpg" width="100%" alt="A pinhole camera footprint drawn on an equirectangular panorama, next to the extracted view"></a>
<b><a href="https://github.com/guilhem0908/erpkit">erpkit</a></b><br>
A tested geometry toolkit for 360° images. It measures what stitching costs: six 1024 px faces at 96° sample the sphere 1.41 times more coarsely than a 4096×2048 panorama.
</td>
<td width="50%" valign="top">
<a href="https://github.com/guilhem0908/gaussian-projection-bench"><img src="assets/gaussian-projection-bench.jpg" width="100%" alt="A projected Gaussian on an equirectangular image with two approximating ellipses and error maps"></a>
<b><a href="https://github.com/guilhem0908/gaussian-projection-bench">gaussian-projection-bench</a></b><br>
How wrong is the splat? EWA linearisation against the unscented transform through pinhole, fisheye and equirectangular cameras, measured against a Monte-Carlo reference.
</td>
</tr>
</table>

## Stack

- **3D vision:** `3D Gaussian Splatting` `COLMAP` `PyTorch` `OpenCV` `equirectangular geometry`
- **Robotics:** `ROS 2` `MuJoCo` `path planning` `Kachaka API`
- **Software:** `Python` `C / C++` `TypeScript` `Docker` `Linux` `HPC (PBS, Singularity)`
