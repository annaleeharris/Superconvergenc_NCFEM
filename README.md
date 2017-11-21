# Superconvergence-NCFEM
This folder contains Matlab computer programs to approximate model second order elliptic problems using nonconforming finte element numerical methods and a paper explaining about NCFEM and superconvergence of NCFEM.

The folder contains the folloiwng files:

1. NCFEM and Superconvergence NCFEM document paper
2. NCFEM.m - Matlab computer program: computes a numerical approximation u_h.
3. super_NCFEM.m - Matlab computer program: applies L^2 projection to the existing numerical approximation u_h to enhance the accuracy of u_h and the computational time to calculate u_h.
4. exactu.m - Matlab computer program: contains model second order elliptic problems.  It is used to find the difference between the exact solution and the numerical approximation(It calculates the error between u and u_h.)
5. gradientu.m - Matlab computer programs: contains model gredients of u.  It is used to find the difference between the exact gradients of u and the numerical approximation gradients u_h (It calculates the error between gradients u and gradients u_h.)
6. rhs.m - Matlab computer program: contains f.
7. graph.m - Matlab computer program: plots the exact u so one can visually compare the exact solution and the numerical approximation by comparaing the plots.  

