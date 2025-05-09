# SSA_CourseProject

# Computer Vision Service Architecture

This repository contains the Architectural Design Document (ADD) for the Computer Vision (CV) Service (Variation X3), targeting edge deployment on single-board computers. The project defines a flexible, configurable service to process RTSP streams and media files with computer vision pipelines.

## Repository Structure
fig/
	context_diagram.svg # System context diagram
	
	container_diagram.svg # C4 container view
	
	component_diagram.svg # Component breakdown inside the CV Service
	
	live_sequence.svg # Sequence diagram for live RTSP processing
	
	batch_sequence.svg # Sequence diagram for batch upload processing
	
	ota_sequence.svg # Sequence diagram for OTA update and rollback
	
	deployment_multi_sbc.svg # Deployment view with two SBC nodes
	
main.tex # LaTeX source for the Architectural Design Document

Course_Project_Draft_Computer_Vision_Service_X3.pdf

Course_Project_SSA.pdf # Submission artifact

deployment_diagram.svg # Original deployment diagram (single node)

README.md # This file

.gitattributes


## Building the Document
1. Ensure you have LaTeX installed (e.g., TeX Live).
2. From the repository root, run:
bash
pdflatex main.tex
3. The final PDF main.pdf will be generated.

## Contents
Executive Summary: High-level overview and business value.

Project Context: Stakeholders, environment, and use cases.

Assumptions & Architectural Drivers: Key constraints and quality scenarios.

Proposed Architecture: Styles, patterns, component catalog, and multiple views (static, dynamic, deployment).

Architectural Analysis: Mini-ATAM, risk matrix, traceability, and validation probes.

Appendices: Glossary, benchmark evidence, sample pipeline YAML and API snippets.

## Diagrams
All architecture diagrams are located in the fig/ directory as SVG assets. Update or regenerate them using PlantUML or your preferred tool, ensuring the filenames remain consistent with the LaTeX source.

## License
This document and accompanying diagrams are released under the MIT License. See LICENSE for details.