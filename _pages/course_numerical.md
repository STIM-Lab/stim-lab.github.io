---
title: "ECE 3340 - Numerical Methods for Electrical Engineers"
layout: single
classes: wide
permalink: /course_numerical/
author_profile: false

topics:
  - name: Introduction
    material: |-
      [A.1 Introduction](https://slides.com/stim-lab/ece3340-00-0-introduction)  
      [A.2 Math Fundamentals](https://slides.com/stim-lab/ece3340-01-01-math)  
      Homework 1: [PDF](/assets/pdf/nm_hw01.pdf)  
      [A.3 Programming Digital Systems](https://slides.com/stim-lab/ece3340-01-02-programming)  
      Homework 2: [PDF](/assets/pdf/nm_hw02.pdf)

  - name: Measurements
    material: |-
      [B.1 Measuring Algorithms](https://slides.com/stim-lab/ece3340-02-01-complexity)  
      Homework 3: [PDF](/assets/pdf/nm_hw03.pdf)  
      [B.2 Measuring Error](https://slides.com/stim-lab/ece3340-02-02-error)  
      Homework 4: [PDF](/assets/pdf/nm_hw04.pdf)

  - name: Numbers and Precision
    material: |-
      [C.1 Numbers in Digital Systems](https://slides.com/stim-lab/ece3340-03-01-numbers)  
      Homework 5: [PDF](/assets/pdf/nm_hw05.pdf)  
      C.2 Catastrophic Cancellation  
      C.3 Improving Precision  
      C.4 Taylor Series  
      Homework 6 [PDF](/assets/pdf/nm_hw06.pdf)

  - name: Solving Equations
    material: |-
      D.1 Bracketing Methods  
      D.2 Householder Methods  
      Homework 7: [PDF](/assets/pdf/nm_hw07.pdf)

  - name: Solving Linear Systems
    material: |-
      E.1 Linear Systems  
      E.2 Stable Solutions
      Homework 8: [PDF](/assets/pdf/nm_hw08.pdf)

  - name: Advanced Matrix Operations
    material: |-
      F.1 LU Decomposition  
      F.2 Matrix Properties  
      Homework 9: [PDF](/assets/pdf/nm_hw09.pdf)

  - name: Calculus
    material: |-
      G.1 Differentiation  
      G.2 Integration  
      Homework 10: [PDF](/assets/pdf/nm_hw10.pdf)

  - name: Solving Differential Equations
    material: |-
      H.1 Differential Equations  
      H.2 The Kessel Run (Mathematics)  
      H.3 The Kessel Run (Implementation)  
      Homework 11: [PDF](/assets/pdf/nm_hw11.pdf)  
      Programming Assignment: [GitHub](https://github.com/STIM-Lab/kesselrun_template)

  - name: Random Numbers
    material: |-
      I.1 Probability and LCGs 
      I.2 Cryptography and CSPRNGs  
      Homework 12: [PDF](/assets/pdf/nm_hw12.pdf)

  - name: Regression and Optimization
    material: |-
      J.1 Interpolation  
      J.2 Linear Least Squares  
      J.3 Nonlinear Least Squares  
      J.4 Optimization  
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