# Tunable optical absorption in undoped graphene sandwich

The propagation of the light is represented by the matrix equation, which is known as the transfer matrix method. In the transfer matrix method, the $E^{(+)}$ and $E^{(-)}$ are expressed in terms of $E''^{(+)}$ and $E''^{(-)}$. Thus, we obtain the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E^{(+)}\\
          E^{(-)}
  \end{bmatrix} = M_{0|n}P_nM_{n|n'}P_{n'}
  \begin{bmatrix}
          E^{''(+)}\\
          E^{''(-)}
  \end{bmatrix}
  ,
\end{align}$$

where $P_n$ and $M_{n|n'}$ are the propagation matrix of medium $n$ and matching matrix between medium $n$ and $n'$, respectively. The product of all $P_n$ and $M_{n|n'}$ is known as the transfer matrix of the structure. The $P_n$ and $M_{n|n'}$ are expressed as follows:

$$\begin{align}
  M
  &=
  \frac{1}{2} \begin{bmatrix}
  \left( 1 + \displaystyle\frac{n'}{n} \right) & \left( 1 - \displaystyle\frac{n'}{n} \right)\\
  \left( 1 - \displaystyle\frac{n'}{n} \right) & \left( 1 + \displaystyle\frac{n'}{n} \right)
  \end{bmatrix}
\end{align}$$

$$\begin{align}
P_n =
  \begin{bmatrix}
          - i & 0\\
          0   & i
  \end{bmatrix}\equiv P
\end{align}$$

In the mirror structures consisting of repeating unit layers of ABC and ABCD, respectively, each layer of the unit layers can take a different refractive index. The transfer matrix of the structure consists of the following matrix equations, with $x$ defining how many media are used in the unit layers:

$$\begin{align}
  J_1 &= M_{0|1} P ... M_{m-1|m} P, \notag\\
  J_2 &= M_{m|1} P ... M_{m-1|m} P, \notag\\
  J_3 &= P M_{m|m-1} ... P M_{1|m}, \notag\\
  J_4 &= P M_{m|m-1} ... P M_{1|0},
\end{align}$$

where $0$ denotes air.

The transfer matrices for the ABC unit layer are given as follows:
    
$$\begin{align}
  &J_{1 (3)} = \displaystyle\frac{i}{2}
  \begin{bmatrix}
          \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} + \displaystyle\alpha_{3} & - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} + \displaystyle\alpha_{3}\\
          \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} - \displaystyle\alpha_{3} & - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} - \displaystyle\alpha_{3}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{2 (3)} = \displaystyle\frac{i}{2}
  \begin{bmatrix}
          \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} + \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} & - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} + \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}}\\
          \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} & - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{3 (3)} = \displaystyle\frac{i}{2}
  \begin{bmatrix}
          \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} + \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} & \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}}\\
          - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} + \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}} & - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} - \displaystyle\frac{n_{C}}{\displaystyle\alpha_{3}}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{4 (3)} = \displaystyle\frac{i}{2}
  \begin{bmatrix}
          \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} + \displaystyle\frac{1}{\displaystyle\alpha_{3}} & \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} - \displaystyle\frac{1}{\displaystyle\alpha_{3}}\\
          - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} + \displaystyle\frac{1}{\displaystyle\alpha_{3}} & - \displaystyle\frac{\displaystyle\alpha_{3}}{n_{C}} - \displaystyle\frac{1}{\displaystyle\alpha_{3}}
  \end{bmatrix}.
\end{align}$$

where $\displaystyle\alpha_{3} = \displaystyle\frac{n_{A}n_{C}}{n_{B}}$.
Therefore, the propagation of light through such a structure of repeating ABC layers is represented by the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E_{0}^{(+)}\\
          E_{0}^{(-)}
  \end{bmatrix} = J_{1(3)}J_{2(3)}^{r-1}M_CJ_{3(3)}^{r-1}J_{4(3)}
  \begin{bmatrix}
          E_{N+1}^{(+)}\\
          0
  \end{bmatrix},
\end{align}$$

where the $M_C$ represents the matching matrix of the center layer, $E_{0}^{(+)}$, $E_{0}^{(-)}$ and $E_{N+1}^{(+)}$ are the incident, reflected and transmitted electric fields of the structure.
    
The transfer matrices for the ABCD unit layer are given as follows:

$$\begin{align}
  &J_{1 (4)} = \displaystyle\frac{1}{2}
  \begin{bmatrix}
          \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4}n_{D} & \displaystyle\frac{1}{\displaystyle\alpha_{4}} - \displaystyle\alpha_{4}n_{D}\\
          \displaystyle\frac{1}{\displaystyle\alpha_{4}} - \displaystyle\alpha_{4}n_{D} & \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4}n_{D}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{2 (4)} = \displaystyle\frac{1}{2}
  \begin{bmatrix}
          \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4} & \displaystyle\frac{1}{\displaystyle\alpha_{4}} - \displaystyle\alpha_{4}\\
          \displaystyle\frac{1}{\displaystyle\alpha_{4}} - \displaystyle\alpha_{4} & \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{3 (4)} = \displaystyle\frac{1}{2}
  \begin{bmatrix}
          \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4} & - \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4}\\
          - \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4} & \displaystyle\frac{1}{\displaystyle\alpha_{4}} + \displaystyle\alpha_{4}
  \end{bmatrix},
\end{align}$$

$$\begin{align}
  &J_{4 (4)} = \displaystyle\frac{1}{2}
  \begin{bmatrix}
          \displaystyle\frac{1}{\displaystyle\alpha_{4}n_{D}} + \displaystyle\alpha_{4} & - \displaystyle\frac{1}{\displaystyle\alpha_{4}n_{D}} + \displaystyle\alpha_{4}\\
          - \displaystyle\frac{1}{\displaystyle\alpha_{4}n_{D}} + \displaystyle\alpha_{4} & \displaystyle\frac{1}{\displaystyle\alpha_{4}n_{D}} + \displaystyle\alpha_{4}
  \end{bmatrix}.
\end{align}$$

where $\displaystyle\alpha_{4} = \displaystyle\frac{n_{A}n_{C}}{n_{B}n_{D}}$.
Therefore, the propagation of light through such a structure of repeating ABC layers is represented by the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E_{0}^{(+)}\\
          E_{0}^{(-)}
  \end{bmatrix} = J_{1(3)}J_{2(3)}^{r-1}M_CJ_{3(3)}^{r-1}J_{4(3)}
  \begin{bmatrix}
          E_{N+1}^{(+)}\\
          0
  \end{bmatrix},
\end{align}$$

where the $M_C$ represents the matching matrix of the center layer, $E_{0}^{(+)}$, $E_{0}^{(-)}$ and $E_{N+1}^{(+)}$ are defined similarly in the case of structure of repeating ABC layers.

In the presence of graphene, the propagation of light is represented by the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E_{0}^{(+)}\\
          E_{0}^{(-)}
  \end{bmatrix} = J_{1(3,4)}J_{2(3,4)}^{r-1}M_GJ_{3(3,4)}^{r-1}J_{4(3,4)}
  \begin{bmatrix}
          E_{N+1}^{(+)}\\
          0
  \end{bmatrix},
\end{align}$$

where the $M_G$ represents the matching matrix of the graphene layer, which is expressed as follows,

$$\begin{align}
  &M_{G} = \displaystyle\frac{1}{2}
  \begin{bmatrix}
          2 + \displaystyle\frac{Z_{0}}{n_{m}} \sigma & \displaystyle\frac{Z_{0}}{n_{m}} \sigma \\
          - \displaystyle\frac{Z_{0}}{n_{m}} \sigma & 2 - \displaystyle\frac{Z_{0}}{n_{m}} \sigma
  \end{bmatrix},
\end{align}$$

where $\sigma=e^2/4\hbar$ is the optical conductivity of undoped graphene, $n$ is refractive index of the material surrounding graphene, which is symbolized by the $m$ index. Here, we have $n=n_C$ and $n=n_D$ for the cases of ABC and ABCD structures, respectively.
In the case of no graphene, the electric field at the center of the structure $E_c=E_c^{(+)}+E_c^{(-)}$is given by the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E_{c}^{(+)}\\
          E_{c}^{(-)}
  \end{bmatrix} = \left( J_{1(3,4)}J_{2(3,4)}^{r-1} \right)^{-1}
  \begin{bmatrix}
          E_{0}^{(+)}\\
          E_{0}^{(-)}
  \end{bmatrix}.
\end{align}$$

On the other hand, in the presence of graphene, the electric field at the center of the structure is given by the following matrix equation,

$$\begin{align}
  \begin{bmatrix}
          E_{c}^{(+)}\\
          E_{c}^{(-)}
  \end{bmatrix} = \left( J_{1(3,4)}J_{2(3,4)}^{r-1} M_G\right)^{-1}
  \begin{bmatrix}
          E_{0}^{(+)}\\
          E_{0}^{(-)}
  \end{bmatrix}
\end{align}$$