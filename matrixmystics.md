---
layout: page
title: Oceanverse 
order: 5
permalink: /matrixmystics/
---

* TOC
{:toc}
# Module 1

**1**\. Plot the lines $$y=x$$, $$y=2x$$, $$y=10x$$.

**2**\. Observe that they all pass through the origin. Why?

**3**\. Plot $$y=2x+1$$. Why doesn't it pass through the origin?

**4**\. Plot $$y=ax+b$$, with $$a$$ and $b$ as parameters which you should be able to varry. What do youaa observe?

**5**\. Consider the following simultaneous equation:<br>

2x+3y=7 <br>
3x+4y=10 <br>

Do you see a 2x2 matrix here? What is the importance of seeing a matrix in this problem? Why study matrices in general?<br>

Do you observe that this problem can be retold as: <br>

$$ \left( \begin{matrix} 2 & 3 \\3 & 4 \\\end{matrix}\right) $$
$$\left(
\begin{matrix}
x\\
y\\
\end{matrix}
\right)$$
=$$\left(
\begin{matrix}
7\\
10\\
\end{matrix}
\right)$$

**6**\. Consider the function $$\phi : \mathbb{R}\rightarrow \mathbb{R}$$ defined by $$\phi (x,y)=(2x+3y,3x+4y)$$. What has this to do with the previous question?

**7**\. Is the function $$\phi$$ 1-1 and onto? is this function invertible? In the question above on matrices, we see that it is of the form $$Ax=b$$. Note that we can invert the matrix and find out the value for the variables x and y. This is one of the many applications of matrices.  

**8**\. Use geogebra to find the range of the above function $$\phi (x,y)=(2x+3y,3x+4y)$$.

**9**\. We will now see matrices as functions. Instead of $$\phi$$ we will write the matrix itself: <br>

$$\left( \begin{matrix} 2 & 3 \\3 & 4 \\\end{matrix}\right) : \mathbb{R} \rightarrow \mathbb{R}$$. What is the range of this matrix?

**10**\. Consider the function $$\left( \begin{matrix} 1 & 2 \\2 & 4 \\\end{matrix}\right) : \mathbb{R} \rightarrow \mathbb{R}$$. What is the range of this matrix? This function takes some elements of the domain to $$(0,0)$$. What are those elements? Plot this using Geogebra.



# Module 2

---
1. We encounter equations very often in our lives. Consider for example, the following situation at ___Baker's Cafe___. The manager has a very important estimate to make. Mostly, visitors at his cafe happen to be families and they are often comprised of Children and/or Adults. He observes that there are 3 adults and 1 child at a table and their bill turns out to be Rs.1200/-. There is yet another table with 2 children and 1 adult and their bill comes out to be Rs.1000/-. Can the manager estimate the consumption of a Child/Adult? This is popularly called the _Simultaneous Equations_ and we all remember from our school days, multiple ways in which these can be solved.<br>
$$ 3A + 1C = 1200 $$   
$$ 1A + 2C = 1000 $$

2. While we were taught the so called two variables and two unknowns, what if there were more equations than unknowns?<br>
$$ 3A + 1C = 1200 $$   
$$ 1A + 2C = 1000 $$    
$$ 1A + 1C =  900 $$


3. Note that the previous question can be modelled as a matrix:

   $$ 3A + 1C = 1200 $$   
   $$ 1A + 2C = 1000 $$    
   $$ 1A + 1C =  900 $$

   <u>Observe</u> this is same as :

   $$ \left( \begin{matrix} 3 & 1 \\1 & 2 \\1 & 1 \\\end{matrix}\right) $$
   $$\left(
   \begin{matrix}
   B\\
   C\\
   \end{matrix}
   \right)$$
   =
   $$
   \left(
	\begin{matrix}
	1200\\
	1000\\
	900\\
	\end{matrix}
   \right)
   $$

4. The best way to solve is, is to guess the values :-). Can you write a python code to guess the values?

5. How do you solve this mathematically? There are two nice ways of solving this:   
 - Model this as a question of inverting a rectangular matrix and find the solution. (Whoa! my teacher never taught me that!) 
 - Model this as a funtion of two variables and solve it using partial differentiation (Eeks!)

    
