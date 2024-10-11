---
tags:
  - Mathe
  - Matheaufgaben
  - Aufgaben
  - Hausaufgaben
  - Kugeln
  - Tangentialebene
  - Klasse_13
  - Klasse_13_1
---
## Buchseite 197:
### Aufgabe 4:
> Die Kugel $K_{1}:\begin{pmatrix}1\\7\\-2\end{pmatrix}^{2} =36$ und $K_{2}:\begin{pmatrix}7\\13\\1\end{pmatrix}^{2}=9$ berühren sich. Bestimmen Sie eine Gleichung der gemeinsamen Tangentialebene.

### Difinierung der Variablen:
$$
\begin{align}
	M_{1}&=(1|7|-2)\\
	r_{1}&=6\\
\\
	M_{2}&=(7|13|1)\\
	r_{1}&=3\\
\end{align}
$$


### Skizze:
![[TO BE ADDED]]

### Rechnung
$$
\begin{array}
	&\overrightarrow{M_{1}M_{2}}&=
		&\begin{pmatrix}
			7-1\\
			13-7\\
			1-(-2)
		\end{pmatrix}
	&=
		&\begin{pmatrix}
			6\\
			6\\
			3
		\end{pmatrix}\\
	&&\overrightarrow{t}&=\overrightarrow{OM_{1}}+\lambda\cdot\frac{\overrightarrow{M_{1}M_{2}}}{\left|\overrightarrow{M_{1}M_{2}}\right|}
\end{array}
$$
Da der Radius $R_{1}=6$ ist, bedeutet dies einen Abstand von $d=6$ zu der anderen Kugel.
$$
\begin{array}
	\overrightarrow{t}&=
			\begin{pmatrix}
				6\\
				6\\
				3
			\end{pmatrix}
		+\lambda\cdot
			\frac
			{
				\begin{pmatrix}
					6\\
					6\\
					3\\
				\end{pmatrix}
			}
			{
				\left|
					\begin{pmatrix}
						6\\
						6\\
						3\\
				\end{pmatrix}
				\right|
			}
\end{array}
$$
