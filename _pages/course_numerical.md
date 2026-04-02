---
title: "ECE 3340 - Numerical Methods for Electrical Engineers"
layout: single
classes: wide
permalink: /course_numerical/
author_profile: false

topics:
  - name: Introduction
    material: |-
      [A.1 Introduction](https://slides.com/stim-lab/ece3340-a-1-introduction)  
      [A.2 Math Fundamentals](https://slides.com/stim-lab/ece3340-a-2-math/edit)  
      Homework 1: [PDF](/assets/pdf/nm_hw01.pdf)  
      [A.3 Programming Digital Systems](https://slides.com/stim-lab/ece3340-a-3-programming)  
      Homework 2: [PDF](/assets/pdf/nm_hw02.pdf)  
      Programming 1: [PDF](/assets/pdf/programming1.pdf)

  - name: Measurements
    material: |-
      [B.1 Measuring Algorithms](https://slides.com/stim-lab/ece3340-b-1-complexity)  
      Homework 3: [PDF](/assets/pdf/nm_hw03.pdf)  
      [B.2 Measuring Error](https://slides.com/stim-lab/ece3340-b-2-error)  
      Homework 4: [PDF](/assets/pdf/nm_hw04.pdf)

  - name: Numbers and Precision
    material: |-
      [C.1 Numbers in Digital Systems](https://slides.com/stim-lab/ece3340-c-1-numbers)  
      Homework 5: [PDF](/assets/pdf/nm_hw05.pdf)  
      [C.2 Catastrophic Cancellation](https://slides.com/stim-lab/ece3340-c-1-cancellation)  
      C.3 Improving Precision  
      C.4 Taylor Series  
      Homework 6 [PDF](/assets/pdf/nm_hw06.pdf)

  - name: Solving Equations
    material: |-
      [D.1 Bracketing Methods](https://slides.com/stim-lab/ece3340-d-1-bracketing)  
      [D.2 Householder Methods](https://slides.com/stim-lab/ece3340-d-2-householders-methods)  
      Homework 7: [PDF](/assets/pdf/nm_hw07.pdf)

  - name: Solving Linear Systems
    material: |-
      [E.1 Linear Systems](https://slides.com/stim-lab/ece3340-e-1-linear-systems)  
      [E.2 Direct Solutions](https://slides.com/stim-lab/ece3340-e2-direct-solutions)  
      Homework 8: [PDF](/assets/pdf/nm_hw08.pdf)  
      [E.3 Matrix Properties](https://slides.com/stim-lab/ece3340-e3-matrix-properties)  
      Homework 9: [PDF](/assets/pdf/nm_hw09.pdf)
  - name: Regression and Optimization
    material: |-
      [F.1 Interpolation](https://slides.com/stim-lab/ece3340-f1-interpolation)  
      F.2 Linear Least Squares  
      F.3 Nonlinear Least Squares  
      F.4 Optimization 
  - name: Calculus
    material: |-
      [G.1 Differentiation](https://slides.com/stim-lab/ece3340-g1-differentiation)  
      G.2 Integration  
      Homework 10: [PDF](/assets/pdf/nm_hw10.pdf)  
      G.3 Differential Equations  
      Homework 11: [PDF](/assets/pdf/nm_hw11.pdf)  
      G.4 The Kessel Run (Mathematics)  
      G.5 The Kessel Run (Implementation)  
      Programming Assignment: [GitHub](https://github.com/STIM-Lab/kesselrun_template)

  - name: Random Numbers
    material: |-
      H.1 Pseudorandom Numbers  
      H.2 Cryptography and CSPRNGs  
      Homework 12: [PDF](/assets/pdf/nm_hw12.pdf)

   
---

<img title="a title" alt="Alt text" src="/assets/images/courses/ece3340_header.jpg">


### Office Appointments
W324 Engineering Building 1
Online and In-Person appointments via [Calendly](https://calendly.com/mayerich/office)

### Syllabus
Most recent: [Spring 2026](https://uh.simplesyllabus.com/doc/ten62swkv/Spring-2026-ECE-3340-12405-Numerical-Methods-for-Electrical-and-Computer-Engineers?mode=view)

### Textbook 
*Numerical Methods in Practice: An Engineer's Guide to Numerical Computing Using C/C++ and Python*, David Mayerich [[PDF](/assets/pdf/book_numerical.pdf)]

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
