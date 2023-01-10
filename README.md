<table border="0">
 <!-- <tr>
    <td><b style="font-size:30px">Title</b></td>
    <td><b style="font-size:30px">Title 2</b></td>
 </tr> -->
 <tr>
    <td>
    
# nguyenluc99.github.io
Hey there, I am Luc, a computer science undergraduate of Hanoi University of Science and Technology.

</td>
    <td><img src="./nvl.jpeg" alt="alt text" title="image Title" 
    /></td>
 </tr>
</table>

## Current research:

My working interest is the intersection of Combinatorial Mathematics and Computer Science and Graph Theory, which focuses on many optimization problems.

I am working in Information Theory field. One of my research interest is about Constrained system. Currently I am currently working with two enumerating problems:

- Enumerate $(b,k)$ locally-constrained code using generating function. 

    - For example, given $b=3, k=4$, the generating function counting number of locally-constrained de Bruijn sequences of length $n$ is given by:
    $$ f(x) = \sum a_nx^n = \dfrac{2x^8+3x^7+4x^6+5x^5+5x^4+4x^3+3x^2+2x+1}{-x^7-2x^6-3x^5-3x^4-2x^3-x^2+1} $$
    - Implementation can be found at: https://github.com/nguyenluc99/GJ_LC_deBruijnCode

- Enumerate $(u,d,k)$ Dyck codewords in which the code starts and ends at height 0, up steps increase height by $u$, down steps decrease height by $d$, height is always bounded by $0$ and $k$.
    -   The generating function in case either $u=1, d=m$ or $u=m, d=1$ is:
    $$
        g_k(x) = \sum a_nx^n = \dfrac{p_k}{p_{k+1}} = \dfrac{\sum_{0 \leq u \leq k, m+1|u } \begin{pmatrix} k - \dfrac{um}{m+1} \\ \dfrac{u}{m+1} \end{pmatrix} (-1)^{\frac{u}{m+1}}\times{x^u}}{\sum_{0 \leq u \leq (k+1), m+1|u } \begin{pmatrix} k+1 - \dfrac{um}{m+1} \\ \dfrac{u}{m+1} \end{pmatrix} (-1)^{\frac{u}{m+1}}\times{x^u}}
    $$

Please be in touch: <br>
<a href="https://www.linkedin.com/in/lucnguyen-ict/">LinkedIn</a> and email: nguyenluc5699@gmail.com
