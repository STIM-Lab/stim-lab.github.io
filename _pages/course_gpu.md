---
title: "ECE 6340 - Parallel and Heterogeneous Computing"
layout: single
classes: wide
permalink: /course_gpu/
author_profile: false


topics:
  - name: Intro to Parallel Computing
    material: |-
      [**Course Introduction**](/assets/pdf/par/A-1-intro.pdf)  
      *Discussion of course expectations and resources*  
      [**Processor-Level Parallelism**](/assets/pdf/par/A-2-processor-level.pdf)  
      *Limitations on automated parallelism*  
      [**Homework 1**](/assets/pdf/par/hw01.pdf)  
      *Instruction-level dependencies and speedup*  
      [**Software Development Platforms**](/assets/pdf/par/A-3-development.pdf)  
      *Useful platforms for building heterogeneous software*  
      **Programming Assignment 1**: [Parallel Mie Simulation](https://git.stimlab.dev/stim/pa1-parallel-mie)  
      *Validating your build platform*

  - name: Profiling and Memory
    material: |-
      [**Memory**](/assets/pdf/par/B-1-memory.pdf)  
      *Memory instructions, caches, and processor designs*  
      [**CPU Profiling**](https://slides.com/stim-lab/parallel-b-02-profiling)  
      Profiling tools, symbols, and optimization  
  
  - name: Parallel Problems
    material: |-
      [**Ray Tracing**](/assets/pdf/par/C-1-raytracing  
      **Fluid Dynamics**  
      **N-Body Simulations**  
      **Programming Assignment 2:**  
      Module A - Ray Tracing  
      Module B - Fluid Dynamics  
      Module C - N-Body Problems  

  - name: Multithreading
    material: |-
      **C++ Multithreading**  
      *Using C++ std::thread with callback functions*  
      **Multithreading Strategies**  
      *Strategies for basic parallelization in ray tracing, fluid dynamics, and n-body simulations*  
      **Programming Assignment 3:**  
      Module A - Ray Tracing  
      Module B - Fluid Dynamics  
      Module C - N-Body Problems  
      [**Heat Equation**](/assets/pdf/par/D-3-heat-eq.pdf)  
      *Case study in parallelizing partial differential equations*  
      [**Thread Optimization**](/assets/pdf/par/D-4-optimization.pdf)  
      *Discussion of how to optimize parallel applications*  
      

  - name: Graphics Processing Units
    material: |-
      [**Graphics Processors**](/assets/pdf/par/E-1-gpus.pdf)  
      *Evolution and architecture of GPUs*  
      [**CUDA Application Programming Interface**](/assets/pdf/par/E-2-cuda.pdf)  
      *API calls for querying devices and accessing global memory*  
      [**CUDA API Libraries**](/assets/pdf/par/E-3-cuda-libs.pdf)  
      *NVIDIA GPU implementations of common numerical libraries*  
      [**CUDA Threads and Kernels**](/assets/pdf/par/E-4-cuda-threads.pdf)  
      *CUDA language and how kernels are implemented and run on GPUs*  
      [**CUDA Thrust**](/assets/pdf/par/E-5-thrust.pdf)  
      *Standard CUDA template library structures and functions*  
      [**CUDA Thread Scaling**](/assets/pdf/par/E-6-scaling.pdf)  
      *Designing scalable programs and kernels*

  
---

<img title="a title" alt="AMD Radeon RX 6000 die shot" src="/assets/images/courses/ece6360_header.jpg">


### Office Appointments
W324 Engineering Building 1
Online and In-Person appointments via [Calendly](https://calendly.com/mayerich/office)

### Syllabus
[Fall 2026](https://uh.simplesyllabus.com/doc/qa553f8tr/Fall-2026-ECE-6360-18162-Parallel-Algorithms-for-GPUs-and-Heterogeneous-Systems?mode=view)


## Course Outline and Lectures

<head>
<table>
	<thead>
		<tr class="header">
		<th>Topic</th>
		<th>Lectures and Coursework</th>
		</tr>
	</thead>
	<tbody>
	{% for t in page.topics %}
		<tr>
			<td markdown="span"><b>{{t.name}}</b></td>
			<td markdown="span">{{t.material}}</td>
		</tr>
	{% endfor %}
	</tbody>
</table>
</head>