## Buchseite 70:
##### Aufgabe 6:
> Die Punkte $A\left(-7\mid-5\mid2\right)$, $B\left(1\mid9\mid6\right)$, $C\left(5\mid-2\mid-1\right)$ und $D\left(-2\mid0\mid9\right)$ sind die Ecken einer dreiseitigen Pyramide. Berechnen Sie das Volumen der Pyramide.
###### Geg.:
$$
\begin{array}{}
	\vec{OA}=
		\begin{pmatrix}
			-7\\-5\\2
		\end{pmatrix}
		&
		\vec{OB}=
		\begin{pmatrix}
			1\\9\\6
		\end{pmatrix}\\
		\vec{OC}=
		\begin{pmatrix}
			5\\-2\\-1
		\end{pmatrix}
		&
		\vec{OD}=
		\begin{pmatrix}
			-2\\0\\9
		\end{pmatrix}
\end{array}
$$

---
###### Rechnung:
$$
\begin{align}
	\vec{AB}&=\vec{OB}-\vec{OA}\\
		&=\begin{pmatrix}1\\9\\6\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}1+7\\9+5\\6-2\end{pmatrix} \\
			&=\begin{pmatrix}8\\14\\4\end{pmatrix}\\\\
	\vec{AC}&=\vec{OC}-\vec{OA}\\
		&=\begin{pmatrix}5\\-2\\-1\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}5+7\\-2+5\\-1-2\end{pmatrix} \\
			&=\begin{pmatrix}12\\3\\-3\end{pmatrix}\\\\
	\vec{AD}&=\vec{OD}-\vec{OA}\\
		&=\begin{pmatrix}-2\\0\\9\end{pmatrix}-
			\begin{pmatrix}-7\\-5\\2\end{pmatrix}\\
		&=\begin{pmatrix}-2+7\\5\\9-2\end{pmatrix} \\
			&=\begin{pmatrix}5\\5\\7\end{pmatrix} \\
 \\
 V&=\frac{1}{6}\cdot\left|\left( \vec{AB}\times\vec{AC}\right) \cdot\vec{AD}\right|\\ &=\frac{1}{6}\cdot\left|\left( \begin{pmatrix} 8\\14\\4 \end{pmatrix}\times \begin{pmatrix} 12\\3\\-3 \end{pmatrix}\right)\cdot \begin{pmatrix} 5\\5\\7 \end{pmatrix}\right|\\ &=\frac{1}{6}\cdot\left| \begin{pmatrix} -54\\72\\-144 \end{pmatrix}\cdot \begin{pmatrix} 5\\5\\7 \end{pmatrix}\right|\\ &=\frac{1}{6}\cdot\left|-54\cdot5+72\cdot5-144\cdot7\right|\\ &=\frac{1}{6}\cdot\left|-918\right|\\ &=153~~\left[\text{LE}\right]^3 \end{align} $$ 

---
###### Antwort:
Die Pyramide besitzt ein Volumen von $153~~\left[\text{LE}\right]^{3}$.

---
