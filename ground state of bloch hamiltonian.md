$$\mathcal{H}_k = - \begin{pmatrix}  
(h-cosk) & -\gamma sink \ e^{i\phi} \\  
-\gamma sink \ e^{-i\phi} & -(h-cosk)   
\end{pmatrix} \implies \lambda_{\pm} = \pm \sqrt{(h-cosk)^2 + \gamma^2 sin^2k} \implies  - \begin{pmatrix}  
(h-cosk) +\lambda & -\gamma sink \ e^{i\phi} \\  
-\gamma sink \ e^{-i\phi} & -(h-cosk) +\lambda  
\end{pmatrix} \begin{pmatrix}  
a  \\  b \end{pmatrix}= \begin{pmatrix}  
0  \\  0 \end{pmatrix}$$

$$ A = -(h-cosk), B=-\gamma sink \ \ \ \ \implies  -\begin{pmatrix}  A +\lambda_- & B e^{i\phi} \\  
B e^{-i\phi} & -A +\lambda_-  
\end{pmatrix} \begin{pmatrix}  
a  \\  b \end{pmatrix}= \begin{pmatrix}  
0  \\  0 \end{pmatrix} \implies \begin{pmatrix}  A -\lambda_- & B e^{i\phi} & 0\\  
B e^{-i\phi} & -A -\lambda_-  &  0
\end{pmatrix} $$
$$\to \begin{pmatrix}  A -\lambda_- & B e^{i\phi} & 0\\  
B e^{-i\phi} & -(A +\lambda_-)  &  0
\end{pmatrix} \to \begin{pmatrix}  (A -\lambda_-)B e^{-i\phi} & B^2 & 0\\  
(A -\lambda_-)B e^{-i\phi} & -(A +\lambda_-)(A -\lambda_-)  &  0
\end{pmatrix} \to \begin{pmatrix}  (A -\lambda_-)B e^{-i\phi} & B^2 & 0\\  
0 & -A^2-B^2+\lambda_-^2 &  0
\end{pmatrix} \to  \begin{pmatrix}  (A -\lambda_-) & B e^{i\phi} & 0\\  
0 & 0 &  0
\end{pmatrix}$$
$$(A -\lambda_-)x + B e^{i\phi}y=0 \implies y = \frac{x(A -\lambda_-)}{B}e^{-i\phi} \implies |gs_k \rangle = x\begin{pmatrix}  1 \\  \frac{(A -\lambda_-)}{B}e^{-i\phi}  \end{pmatrix}$$

$$|gs \rangle_k = cos \frac{\theta_k}{2} \ |0 \rangle_k + sin\frac{\theta_k}{2} e^{-i\phi}\ |1 \rangle_k \implies tan\frac{\theta_k}{2}=\frac{(A -\lambda_-)}{B} \implies tan \theta_k = $$

```tikz
\begin{document}
\begin{tikzpicture}[scale=10]
    % Critical lines
    \draw[dashed,red] (-1,0) -- (-1,1);
    \draw[dashed,red] (1,0) -- (1,1);
    \draw[violet] (-1,0) -- (1,0);
    
    % Axes
    \draw[->] (-1.2,0) -- (1.2,0) node[right] {$\gamma$};
    \draw[->] (0,-0.1) -- (0,1.2) node[above] {$h$};
    
    % Labels
    \node[below] at (-1,0) {$-1$};
    \node[below] at (1,0) {$1$};
    \node[left] at (0,1) {$1$};
    
    % Phases
    \node[right,red] at (0.5,0.5) {Paramagnetic Phase};
    \node[left,red] at (-0.5,0.5) {Paramagnetic Phase};
    \node[right] at (0,0.5) {Ferromagnetic Phase};
\end{tikzpicture}
\end{document}
```

```tikz
\begin{document}
\begin{tikzpicture}[scale=4]
    % Critical lines
    \draw[dashed,red, ultra thick] (-1,-1) -- (-1,1);
    \draw[dashed,red, ultra thick] (1,-1) -- (1,1);
    \draw[line width=1.5pt, black] (-1,0) -- (1,0);
    
    % Axes
    \draw[->] (-1.2,0) -- (1.2,0) node[right] {$\gamma$};
    \draw[->] (0,-1.2) -- (0,1.2) node[above] {$h$};
    
    % Labels
    \node[below] at (-1.05,0.2) {$h=-1$};
    \node[below] at (1.2,0.2) {$h=1$};
    \node[left] at (0.1,-0.1) {$\gamma=0$};
    
    % Phases
    \node[right,red] at (1.2,0.5) {Paramagnetic Phase};
    \node[left,red] at (-1.2,0.5) {Paramagnetic Phase};
    \node[right, blue] at (-0.5, 0.5) {X-Ferromagnetic Phase};
    \node[left, blue] at (0.5, -0.5) {Y-Ferromagnetic Phase};
\end{tikzpicture}
\end{document}
```





$$\frac{1}{16} \frac{2 |h|^3 - 2 h^2 \sqrt{-1 + h^2 + \gamma^2} - 2 (-1 + \gamma^2) \sqrt{-1 + h^2 + \gamma^2} + |h| (-2 + \gamma^2 + \gamma^4)}{(-1 + \gamma^2)^2 (-1 + h^2 + \gamma^2)^{3/2}}$$
Given a real differential manifold $\mathcal{M}$ a collection of transition maps $\{ \phi_{\alpha}: U \subset \mathcal{M} \to V \subset \mathbb{R}^n \}$ exists that is locally homeomorphic\footnote{A continuous bijection} to open subsets of $\mathbb{R}^n$ for some $n$. Distances can be defined on it by endowing upon it a metric that smoothly assigns a second rank bilinear and symmetric tensor $g_p : T_p \mathcal{M} \times T_p \mathcal{M} \mapsto \mathbb{R}$ on the tangent space $T_p \mathcal{M}$ that satisfies all the conditions of an inner product.


$$ds^2 = E \ du^2 + F \ du dv + G \ dv^2, \ \ g = det[g_{ij}],  \ \ K = \frac{M_1 - M_2}{g^2}, \ \ \ \text{where:} \ \ \ M_1 = \begin{vmatrix} -\frac{1}{2}E_{vv}+F_{uv}-\frac{1}{2}G_{uu} & \frac{1}{2}E_u & -\frac{1}{2}E_v \\ F_v-\frac{1}{2}G_u & E & F \\ \frac{1}{2}G_v & F & G \\ \end{vmatrix}, \ \ \& \ \ M_2 = \begin{vmatrix} 0 & \frac{1}{2}E_v & \frac{1}{2}G_u \\ \frac{1}{2}E_v & E & F \\ \frac{1}{2}G_u & F & G \\ \end{vmatrix}$$
For orthogonal parameterization of the curved surface, i.e. for $F=0$ we have: $$K=-\frac{1}{\sqrt{EG}}[\frac{\partial}{\partial u }(\frac{1}{\sqrt{E}}\frac{\partial \sqrt{G}}{\partial u }) + \frac{\partial}{\partial v }(\frac{1}{\sqrt{G}}\frac{\partial \sqrt{E}}{\partial v })]= -\frac{1}{2 \sqrt{g}}[\partial_u(\frac{G_u}{\sqrt{g}})_u + \partial_v(\frac{E_v}{\sqrt{g}})], \ \ \ \ \ $$

$$\Gamma^1_{22} = \frac{1}{2}g^{1m}(2 \ \partial_2 g_{2m} - \partial_m g_{22})=\frac{1}{2}\{ g^{11}(2 \ \partial_2 g_{21} - \partial_1 g_{22})+g^{12}(2 \ \partial_2 g_{22} - \partial_2 g_{22}) \}=\frac{1}{2}\{ g^{11}(2 \ \partial_v F - \partial_v G)+g^{12} \partial_v G \}=\frac{1}{2}\{2 g^{11} \partial_v F+(g^{12} -g^{11}) \partial_vG  \}$$

$$K = \frac{R_{1212}}{g}, \  \& \ R = g^{ab}R^c_{acb} \ \ \ \text{with:} \ \ R_{abcd} = g_{ak} \Big( \partial_c \Gamma^k_{db} - \partial_d \Gamma^k_{cb} + \Gamma^k_{ce} \Gamma^e_{db} - \Gamma^k_{de} \Gamma^e_{cb} \Big) \ \ and \ \  \Gamma^a_{bc} = \frac{1}{2} g^{ad} \big( \partial_c g_{bd} + \partial_b g_{bc} - \partial_d g_{bc} \big)

$$
$$\text{Ric}_{bd} = K \ g_{bd}.$$$$\frac{i \gamma^2 }{4 \pi \left(-1 + \gamma \right)^{2} \left(1 + \gamma \right)^{2}}  \oint_{\mathcal{C}} dz\frac{z \left(z^2 - 1 \right)^2}{\left((z - z_1^+) (z - z_1^-) (z - z^+_2) (z - z^-_2) \right)^2}
$$

$$\frac{i \gamma^2}{16 \pi (1 - \gamma) (1 + \gamma) }  \oint_{\mathcal{C}} dz \frac{(z^2 - 1)^2}{z \left((z - z_1^+) (z - z_1^-) (z - z^+_2) (z - z^-_2) \right)}
$$

$$\frac{i}{16 \pi \left(-1 + \gamma \right)^{2} \left(1 + \gamma \right)^{2}} \oint_{\mathcal{C}} dz  \frac{ (z^2 + 1 - 2hz)^2 (z^2 - 1)^2}{z \left((z - z_1^+) (z - z_1^-) (z - z^+_2) (z - z^-_2) \right)^2}
$$

$$\frac{i \gamma}{8 \pi(-1 + \gamma)^2 (1 + \gamma)^2} \oint_{\mathcal{C}} dz  \frac{(z^2 + 1 - 2 h z) \cdot (z^2 - 1)^2}{ \left((z - z_1^+) (z - z_1^-) (z - z^+_2) (z - z^-_2) \right)^2}

$$
$$g_{hh}(\gamma=1) = \begin{cases}
    \frac{1}{16 (1-h^2) } & \text{if }|h| < 1 \\
    \frac{1}{16 h^2(h^2-1) } & \text{if } |h| > 1
\end{cases} \  \ \ \  \ \ \ \ \ \ \& \ \ \ \ \ \  \ \ \ 
g_{\phi \phi}(\gamma=1) = \begin{cases}
    \frac{1}{16  } & \text{if }|h| < 1 \\
    \frac{1}{16 h^2} & \text{if } |h| > 1
\end{cases}
$$

$$\Bigg|_{c}^{d}

$$
$$ -8 \ \frac{( \ 1+ \ | \ \gamma \ | \ )}{ \ | \ \gamma \ | }
$$

$$8 \ \left( 1+\frac{|h|}{\sqrt{h^2+\gamma^2-1}} \right)$$
$$1+(\partial_h f(h, \gamma))^2 = E, \partial_h f(h, \gamma)\partial_{\gamma} f(h, \gamma)=F, 1+(\partial_{\gamma} f(h, \gamma))^2=G$$
