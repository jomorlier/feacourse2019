# feacourse 2020


****
LECTURES
****

## Q&A session 
4 videoconferences (ZOOM) planned on:

1. Monday 20th of april 2020 14H00-14H30 Kick Off (ZOOM, J. MORLIER) 
2. Tuesday 21th of april 2020 14H00-15H00 Q&A session and feedback on assignement 1/2* (ZOOM, J. MORLIER) 
3. Wednesday 22th of april 2020 13H30-14H00  Q&A session and feedback on assignement 2*/3 (ZOOM, J. MORLIER) 
4. Tuesday 28th of april 2020 11H00-12H00  Q&A session and feedback on assignement 4* (ZOOM, J. MORLIER) 

* marked --> upload a zip on LMS with all your files for assignement 2& 4

4 lectures [Linear FEA](https://github.com/jomorlier/feacourse2019/blob/master/ArchiveFEA.zip)
Please read it carrefully in autonomy. 

## AUDIO 

[Amanote's tutorial](https://www.youtube.com/watch?v=DvLyo9mtf3U)

[Course 1](https://github.com/jomorlier/feacourse/blob/master/Course1.md)

[Course 2](https://github.com/jomorlier/feacourse/blob/master/Course2.md)

[Course 3](https://github.com/jomorlier/feacourse/blob/master/Course3.md)

[Course 4](https://github.com/jomorlier/feacourse/blob/master/Course4.md)

Have a look to the course exercice in the 2 repo
AssignementC1toC2
AssignementC3toC4

The slides of the different courses are available on *SUPAERO's LMS* with supplementary materials (video, Nastran), assignements (matlab) & projects (matlab, nastran, abaqus).

****
TUTORIALS (MATLAB)
****

Full correction of Assignement C1 Axial Rod with distributed force
the full explanation of Matlab's implementation with symbolic computing
[Explanation](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/AxialRod/AxialBarFEM_explanation.html)


Matlab's implementation with 3 elements
[correction](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/AxialRod/AxialBarFEM_simplified2.html)

from a very nice reference https://en.wikiversity.org/wiki/Introduction_to_finite_elements/Axial_bar_finite_element_solution


## Warning
I'm using a lot symbolic computation but in the scope of the course:
you'll need to do Gauss integration (exact integration for polynoms) because of the shape functions are ofthen 3rd order polynomial...

Static Analysis SOL101 (NASTRAN) := Ku=f with K is a stiffness matrix, u vector of displacement, f vector of external force
you get u by : inv(K)*f


1st MATLAB tutorial on [Shape functions](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Shape_Functions/ShapeFunction.html)

Then How do we derive the K stiffness matrix for a rod?

2nd MATLAB tutorial on [2 nodes rod](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/K_derivation_Rod/K_derivation2_node.html)

A truss assembly by direct stiffness method ?
[6 bar truss example](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Truss/CorrectionTruss.html)

But How do we derive the K stiffness matrix for a beam?

3rd MATLAB tutorial on [2 nodes beam](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/K_derivation_Beam/K_derivation_beam.html)

And probably the most important thing ... how can I model distributed forces?

4th MATLAB tutorial on [Equivalent forces for beam element](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Equivalent_Nodal_force/Equivalent_Nodal_force.html)


From the course, an implementation with the explained [Example2](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse2018/blob/master/Correction_Example2/Correction_Example2_NoSYM.html)

Can you add the strain/stress postprocessing?

To check the same example using Symbolic computing for checking the slides [Example2](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Correction_Example2/Correction_Example2.html)

How can I assembly beam + bar ? [AssignementC2_2018](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/AssignementC2_2018/Assignement2_2018_correction.html)



## MORE ADVANCED MATERIALS (BONUS)

for people wondering about how linear elasticity of top88.m is working

Prof, can you help to us understand how to compute the stiffness matrix of 2D membrane?
Explictely ?  [Membrane2D_K](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Membrane2D_K/Elementarystiffrecmesh.html)

Prof, can you help us to understand the plate modeling and bending behaviour?
Thanks to my PhD S. Coniglio !  [Plate2D_Bending](http://htmlpreview.github.io/?https://github.com/jomorlier/feacourse/blob/master/Plate2D_Bending/plate_el.html)

****
REFERENCES
****

You can find in PC3A.pdf the content of the handwritten exercices on FEA.

https://v2.overleaf.com/project/5b92449b27c88a7311a508fd

You can also find a tutorial on Finite element + Nastran in IntroNastran.pdf

https://v2.overleaf.com/project/57fe421839536a6d421c2734

I strongly recommend to read and learn from this MIT's book

http://web.mit.edu/kjb/www/Books/FEP_2nd_Edition_4th_Printing.pdf


## RECAP

For SUPAERO's 3rd year, you can file an archive with french course on sizing, beam's theory, structural dynamics and plate computing.

Recap [Structural Mechanics](https://github.com/jomorlier/feacourse/blob/master/Recap_1A_2A_SUPAERO.zip)



