-  **Chinese Remainder Theorem:**    Let $A$ be a ring and $\mathfrak{a}_1$,...,$\mathfrak{a}_n$ ideal of $A$.
   $$
   \phi : A\rightarrow\prod\limits_{i=1}^n A/\mathfrak{a}_i
   $$

   -  If $\mathfrak{a_i}$, $\mathfrak{a_j}$ are *coprime* whenever $i\neq j$, then $\Pi \mathfrak{a}_i=\cap \mathfrak{a}_i$.

   -  $\phi$ is surjective $\iff$ $\mathfrak{a_i}$, $\mathfrak{a_j}$ are *coprime* whenever $i\neq j$.

   -  $\phi$ is injective $\iff$ $\cap\mathfrak{a}_i=(0)$.

   -  **Proof:** 

      -  Induction on $n$. Let $\mathfrak{b}=\prod\limits_{i=1}^{n-1} \mathfrak{a}_i=\bigcap\limits_{i=1}^{n-1} \mathfrak{a}_i$. Since $\mathfrak{a}_i+\mathfrak{a_n}=(1)$, we have equations $x_i+y_i=1$. 
         $$
         \prod\limits_{i=1}^{n-1} x_i=\prod\limits_{i=1}^{n-1} (1-y_i)\equiv 1 (mod\ \mathfrak{a_n})
         $$
         Therefore $\mathfrak{b}+\mathfrak{a_n}=(1)$. $\blacksquare$ 

      -  

        - $\Rightarrow:$ Choose $x$ s.t. $\phi(x)=e_i$. Then $1=(1-x)+x\in\mathfrak{a}_i+\mathfrak{a}_j$.
        - $\Leftarrow:$ $\prod\limits_{i=1}^{n-1} x_i=\prod\limits_{i=1}^{n-1} (1-y_i)\equiv e_n$.