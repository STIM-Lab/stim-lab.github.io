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
      <span class="material-divider"></span>
      [**Processor-Level Parallelism**](/assets/pdf/par/A-2-processor-level.pdf)  
      *Limitations on automated parallelism*  
      [HW 1](/assets/pdf/par/hw01.pdf): Instruction-level dependencies and speedup  
      <span class="material-divider"></span>
      [**Software Development Platforms**](/assets/pdf/par/A-3-development.pdf)  
      *Useful platforms for building heterogeneous software*  
      [PA 1](https://git.stimlab.dev/stim/pa1-parallel-mie): Validate your build platform with a parallel Mie simulation  

  - name: Profiling and Memory
    material: |-
      [**Memory**](/assets/pdf/par/B-1-memory.pdf)  
      *Memory instructions, caches, and processor designs*  
      [HW 2](/assets/pdf/par/homework/02-vocabulary.pdf): Paradigms and memory (vocabulary)  
      [HW 3](/assets/pdf/par/homework/03-caching.pdf): Cache planning
      <span class="material-divider"></span>
      [**CPU Profiling**](https://slides.com/stim-lab/pa-c-2-profiling)  
      [Profiling Demo](https://codeberg.org/stimlab/par-demo-specialfuncs): Debugging symbols, tracing, and sampling  
  
  - name: Parallel Problems
    material: |-
      **Ray Tracing**  
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
      **Heat Equation**  
      *Case study in parallelizing partial differential equations*  
      **Thread Optimization**  
      *Discussion of how to optimize parallel applications*  
      

  - name: Graphics Processing Units
    material: |-
      **Graphics Processors**  
      *Evolution and architecture of GPUs*  
      **CUDA Application Programming Interface**  
      *API calls for querying devices and accessing global memory*  
      **CUDA API Libraries**  
      *NVIDIA GPU implementations of common numerical libraries*  
      **CUDA Threads and Kernels**  
      *CUDA language and how kernels are implemented and run on GPUs*  
      **CUDA Thrust**  
      *Standard CUDA template library structures and functions*  
      **CUDA Thread Scaling**  
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