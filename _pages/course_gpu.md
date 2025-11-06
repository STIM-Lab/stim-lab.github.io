---
title: "ECE 6340 - Parallel and Heterogeneous Computing"
layout: single
classes: wide
permalink: /course_gpu/
author_profile: false


topics:
  - name: Introduction to Parallel Programming
    material: |-
      [Course Introduction](https://www.dropbox.com/scl/fi/dw2d8pfspnv9rmymytr9s/01-introduction.pdf?rlkey=mdjl57gfsshuhcjy6w0xuce0s&st=gze8mp27&dl=1)  
      Discussion of course expectations and resources  
      [Processor-Level Parallelism](https://www.dropbox.com/scl/fi/ddzmxl38zbdxvmi8ncmsq/02-processor-level-parallelism.pdf?rlkey=hvpdvc3u4lq604rvi8nwtzny4&st=vtwre5u2&dl=1)  
      Limitations on automated parallelism  
      [**Homework 1**](https://www.dropbox.com/scl/fi/p3ovi6zu6x3cku6c3i4jw/hw01.pdf?rlkey=erytlrbxxu554zkxb7k1hwvax&st=y1ctmxjv&dl=0)  
      **Instruction-level dependencies and speedup**  
      [Software Development Platforms](https://www.dropbox.com/scl/fi/171to3nv2zxc0a6kzrepo/03-development-platforms.pdf?rlkey=btskljnvja6ikbt0126odmanp&st=ds5zultb&dl=1)  
      Useful platforms for building heterogeneous software  
      **Programming Assignment 1**: [GitHub UI Repository](https://github.com/STIM-Lab/helloworld)  
      **Validating your build platform**

  - name: Programming Assignment Introduction
    material: |-
      [A.1 Ray Tracing](https://www.dropbox.com/scl/fi/jca43fnogm9afb5v9mncy/03.A-ray-tracing.pdf?rlkey=zib1k9jv1xi3dokafjo9udv4g&st=mgna24ru&dl=1)  
      Ray tracing theory and implementation details  
      **Programming Assignment 2:** [Ray Tracing]()  
      **Ray tracing a sphere**

  - name: Profiling and Memory
    material: |-
      [CPU Profiling](https://www.dropbox.com/scl/fi/cj0xyy6dr72bdle5obuk8/04-profiling.pdf?rlkey=59a4fkjed74xht3td4dd4cd3b&st=mvquk3u4&dl=1)  
      Profiling tools, symbols, and optimization  
      [Memory](https://www.dropbox.com/scl/fi/8bg06mircolfhyb8ssptx/05-memory.pdf?rlkey=l401vhuxwuhct3t2d1oxs4y3w&st=q4p2xh2s&dl=1)  
      Memory instructions, caches, and processor designs  
      [Heat Equation](https://www.dropbox.com/scl/fi/tx2vj3xbtv346z3oub7zd/06-heat-equation.pdf?rlkey=ih0btbmgi55dzpqsm2ka39upb&st=0zmtn5x5&dl=1)  
      Case study in parallelizing partial differential equations

  - name: Multithreading
    material: |-
      [Multithreading in C++](https://www.dropbox.com/scl/fi/7ju4vue8zdzg4c7q94lfh/07-multithreading.pdf?rlkey=l207u1jbteplylqkb7ddc63ck&st=mjk7ssk3&dl=1)  
      Using C++ std::thread with callback functions  
      [A.2 Parallel Ray Tracing](https://www.dropbox.com/scl/fi/ocxu3citsp2hoi1eavsvs/07.A-parallel-ray-tracing.pdf?rlkey=9m0nim3547br73wuai49naedm&st=bec1yufs&dl=1)  
      Implementing a parallel path tracer using multithreading  
      **Programming Assignment 3:** [Ray Tracing](https://www.dropbox.com/scl/fi/61nsoesd3hrqyp9sw2ubv/raytrace_threads.pdf?rlkey=9bf84yoqr6cn8uipr7u3bm6id&st=b2w1meba&dl=1)  
      **Implement a multi-threaded version of the programming assignment**  
      [Thread Optimization](https://www.dropbox.com/scl/fi/4989l4ttg2ji5nxzvwp06/08-optimization.pdf?rlkey=l102hp9dm0s62tb72lw8v16kd&dl=1)  
      Discussion of how to optimize parallel applications

  - name: Graphics Processing Units
    material: |-
      [Graphics Processors](https://www.dropbox.com/scl/fi/9rev6yq7vxz2mvu2icoa0/09-GPUs.pdf?rlkey=8naz674ibshg9sqkhwrlk2ofk&dl=1)  
      Evolution and architecture of GPUs  
      [CUDA Application Programming Interface](https://www.dropbox.com/scl/fi/3m8gqlcla08ppcgbkw374/10-CUDA-API.pdf?rlkey=4diyawqwmhinj2fjtx7vfhf7k&dl=1)  
      API calls for querying devices and accessing global memory  
      [CUDA API Libraries](https://www.dropbox.com/scl/fi/gl0fq2jtexobhvnhzvxjh/11-CUDA-libraries.pdf?rlkey=vx64ty4eujzupfki2nkdrnfix&dl=1)  
      NVIDIA GPU implementations of common numerical libraries  
      [CUDA Threads and Kernels](https://www.dropbox.com/scl/fi/hthzzb4qgwgsfy98kxwip/12-CUDA-threads.pdf?rlkey=87vln2znern659ua3h1uj1jq8&dl=1)  
      CUDA language and how kernels are implemented and run on GPUs  
      [CUDA Thrust](https://www.dropbox.com/scl/fi/mcw9hgnmr5x8om8ektjjq/13-CUDA-Thrust.pdf?rlkey=934tx5abac0au0w5stwl271yc&dl=0)  
      Standard CUDA template library structures and functions  
      [CUDA Thread Scaling](https://www.dropbox.com/scl/fi/oz0tnwgu74qo6ykjrub8k/14-CUDA-thread-scaling.pdf?rlkey=uxxnalqvc7tn1aeb8vgq4z20n&dl=1)  
      Designing scalable programs and kernels

  
---

<img title="a title" alt="AMD Radeon RX 6000 die shot" src="/assets/images/courses/ece6360_header.jpg">


### Office Appointments
W324 Engineering Building 1
Online and In-Person appointments via [Calendly](https://calendly.com/mayerich/office)

### Syllabus
[Fall 2025](https://uh.simplesyllabus.com/doc/rff11tspw/Fall-2025-ECE-6360-19006-Parallel-Algorithms-for-GPUs-and-Heterogeneous-Systems?mode=view)


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