---
title: "ECE 3340 - Numerical Methods for Electrical Engineers"
layout: single
classes: wide
permalink: /course_numerical/
author_profile: false

topics:
  - name: Introduction
    material: |-
      [Introduction](https://slides.com/stim-lab/ece3340-00-0-introduction)

  - name: 1 - Mathematics Review
    material: |-
      [1.1 Math Fundamentals](https://slides.com/stim-lab/ece3340-01-01-math)  
      Homework 1: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 2 - Coding Review
    material: |-
      [1.2 Programming Digital Systems](https://slides.com/stim-lab/ece3340-01-02-programming)  
      Homework 2: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 3 - Discrete Math
    material: |-
      [2.1 Measuring Algorithms](https://slides.com/stim-lab/ece3340-02-01-complexity)  
      Homework 3: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 4 - Numerical Error
    material: |-
      [2.2 Measuring Error](https://slides.com/stim-lab/ece3340-02-02-error)  
      Homework 4: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 5 - Numbers in Digital Systems
    material: |-
      [3.1 Numbers in Digital Systems](https://slides.com/stim-lab/ece3340-03-01-numbers)  
      Homework 5: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 6 - Precision Loss
    material: |-
      6.1 Catastrophic Cancellation  
      6.2 Improving Precision  
      6.3 Taylor Series  
      Homework 6 [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 7 - Solving Equations
    material: |-
      7.1 Bracketing Methods  
      7.2 Householder Methods  
      Homework 7: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 8 - Solving Linear Systems
    material: |-
      8.1 Linear Systems  
      8.2 Stable Solutions
      Homework 8: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 9 - Advanced Matrix Operations
    material: |-
      9.1 LU Decomposition  
      9.2 Matrix Properties  
      Homework 9: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 10 - Calculus
    material: |-
      10.1 Differentiation  
      10.2 Integration  
      Homework 10: [PDF](/assets/pdf/nm_hw01.pdf)

  - name: 11 - Solving Differential Equations
    material: |-
      11.1 Differential Equations  
      11.2 The Kessel Run (Mathematics)  
      11.3 The Kessel Run (Implementation)  
      Homework 11: [PDF](/assets/pdf/nm_hw01.pdf)  
      Programming Assignment: [GitHub](https://github.com/STIM-Lab/kesselrun_template)

  - name: 12 - Random Numbers
    material: |-
      12.1 Probability and LCGs 
      12.2 Cryptography and CSPRNGs  
      Homework 12: [PDF](https://www.dropbox.com/scl/fi/l8od07k6h6mdo9111w1wv/hw12.pdf?rlkey=1pb1yzcx757v2ts1mdreouixu&dl=1)

  - name: 13 - Regression and Optimization
    material: |-
      13.1 Interpolation  
      13.2 Linear Least Squares  
      13.3 Nonlinear Least Squares  
      13.4 Optimization  
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