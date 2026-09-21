# Wind-blade inspection — cooperative robotics thesis

## Purpose

Explore a wind-turbine blade inspection system combining UAV transport with a wall-climbing ground robot for close surface access.

The cooperative thesis, *Wind Blade Inspection System with Unmanned Aerial Vehicle and Ground Robot*, names Badr Essefiany, Calin Constantin Clichici, Dongwook Lee and Wail Bougida as authors. The report describes the combined system and ground-robot prototype; authorship of each subsystem must not be inferred from team membership.

## Ground-robot work

Badr's reported contribution includes Fusion 360 mechanical design, 3D-printed parts, prototype assembly and programming. The report describes a ground-robot mechanism involving passive suction cups, a belt-driven mechanism, a swivel chassis and force sensing.

The source CAD, firmware and robot test logs are not included here. The full thesis has not been republished in this repository. This page provides project context without representing missing artifacts as available.

## New visual inspection extension

[Open the surface-anomaly baseline](https://github.com/BadrEss01/Computer_Vision/tree/main/projects/wall-blade-surface-defects).

The executable code stays in Computer_Vision as a single maintained implementation. This page is the project overview, avoiding duplicate copies.

The extension processes an input image through grayscale conversion, local background estimation, contrast thresholding, morphology and connected-component filtering. It outputs candidate regions and an annotated image.

This is new software maintenance work from September 2026. It was not part of the original thesis and is not integrated with the robot or validated on turbine-blade data. Contrast regions can represent shadows or dirt as well as defects.

## Evidence needed for the next stage

- Recover CAD and robot-control source with clear authorship.
- Establish a camera interface and acquisition conditions.
- Evaluate labelled surface images with false-positive analysis.
- Validate any hardware integration independently of image-only tests.

[Portfolio](../../README.md)
