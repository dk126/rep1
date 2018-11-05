# rep1234
\documentclass{article}
\begin{document}
\author{Daria~Kulesza}
\title{Sciaga z LaTex}
\frenchspacing
\begin{document}
\maketitle{Pomoc matematyczna}
\section{Wyrazenia matematyczne}
\subsection{Litery alfabetu greckiego}
\alpha - \backslash alpha \\
\delta - \backslash delta \\
\epsilon - \backslash epsilon \\
\zeta - \backslash zeta \\
\eta - \backslash eta \\
\theta - \backslash theta \\
\iota - \backslash iota \\
\kappa - \backslash kappa \\
\lambda - \backslash lambda \\
\mu - \backslash mu \\
\nu - \backslash nu \\
\xi - \backslash xi\\
\pi - \backslash pi\\
\rho - \backslash rho\\
\sigma - \backslash sigma\\
\tau - \backslash tau\\
\upsilon - \backslash upsilon\\
\phi - \backslash phi\\
\chi - \backslash chi\\
\psi - \backslash psi\\
\omega - \backslash omega\\
\newpage
\subsection{Indeksy gorne, dolne i pierwiastki}
Indeks gorny: \\
$a^{m}$ - $a \hat {\ } \lbrace m \rbrace$ \\ \\
Indeks dolny: 
\\ a_n - a \_ n \\ \\
Indeks gorny i dolny: \\ 
$a^{m}_{n}$ -  $a \hat {\ } \lbrace m \rbrace \_ \lbrace n \rbrace$  \\ \\
Pierwiastek: \\ 
$\sqrt{2x}$ - $\backslash sqrt \lbrace 2x \rbrace \\ \sqrt[n]{2x} - \backslash sqrt \lbrack n \rbrack \lbrace 2x \rbrace $ \\ \\
\subsection{Ulamki pietrowe}
$1\frac{1}{2}$ {\ }:  $\$ 1 \backslash frac \lbrace 1 \rbrace \lbrace 2 \rbrace \$ $ \\ \\
$\frac{ x^{2} }{ k+1 }\quad$ : $\backslash frac \lbrace x \hat {\ } \lbrace 2 \rbrace \rbrace \lbrace k+1 \rbrace \backslash quad$ \\ \\
$x^{ \frac{2}{k+1} }\quad$ : $x \hat {\ } \lbrace \backslash frac \lbrace 2 \rbrace \lbrace k+1 \rbrace \rbrace \backslash quad \\ \\
x^{ 1/2 } {\ }: x \hat {\ } \lbrace 1 \backslash 2 \rbrace $
 \\
\subsection{Znaki calki oraz sumowania} 
$\int_{0}^{\frac{\pi}{2}}$ : $ \backslash int \_ \lbrace 0 \rbrace \hat {\ } \lbrace \backslash frac \lbrace \backslash pi \rbrace \lbrace 2 \rbrace \rbrace $ \\ \\
$\sum_{i=1}^{n} \quad$ : $\backslash sum \_ \lbrace i=1 \rbrace \hat {\ } \lbrace n \rbrace$ \\
\subsection{Nawiasy}
$
\lbrack {\ } \backslash lbrack \\
\rbrack {\ } \backslash rbrack \\
\lbrace {\ } \backslash lbrace \\
\rbrace {\ } \backslash rbrace \\
\langle {\ } \backslash langle \\
\rangle {\ } \backslash rangle \\
\backslash {\ } \backslash backslash \\
\left( \frac{1}{2} \right) {\ } \backslash left( \backslash frac \lbrace 1 \rbrace \lbrace 2 \rbrace \backslash right)$ - dostosowuje wielkosc nawiasow do wartosci
\newpage
\subsection{Macierze}
$$
\mathbf{X} =
\left( \begin{array}{ccc}
x_{11} & x_{12} & \ldots \\
x_{21} & x_{22} & \ldots \\
\vdots & \vdots & \ddots
\end{array} \right)
$$ \\
\backslash mathbf \lbrace X \rbrace = \backslash left( \backslash begin \lbrace array \rbrace \lbrace ccc \rbrace \\
x \_ \lbrace 11 \rbrace \& x \_ \lbrace 12 \rbrace \& \backslash ldots \backslash \backslash \\
x \_ \lbrace 21 \rbrace \& x \_ \lbrace 22 \rbrace \& \backslash ldots \backslash \backslash \\
\backslash vdots \& \backslash vdots \& \backslash ddots \\
\backslash end \lbrace array \rbrace \backslash right)
\subsection{Uklady rownan}
$$
y = \left\{ \begin{array}{ll}
a & \textrm{gdy $d>c$}\\
b+x & \textrm{gdy $d=c$}\\
l & \textrm{gdy $ d < c $}
\end{array} \right.
$$ \\
$y = \backslash left \backslash \lbrace \backslash begin \lbrace array \rbrace \lbrace ll \rbrace \\
a \& \backslash textrm \lbrace gdy \$ d>c \$ \rbrace \backslash \backslash \\
b+x \& \backslash textrm \lbrace gdy \$ d=c \$ \rbrace \backslash \backslash \\
1 \& \backslash textrm \lbrace gdy \$ d<c \$ \rbrace \\
\backslash end \lbrace array \rbrace \backslash right$
\section{Symbole matematyczne}
\begin{tabular}{|r|l|r|l|} \hline
$\leq$ & $\backslash leq$ & $\geq$ & $\backslash geq$ \\ 
$\sim$ & $\backslash sim$ & $\cdot$ & $\backslash cdot$\\
$\circ$ & $\backslash circ$ & $\bullet$ & $\backslash bullet$\\ 
$\to$ & $\backslash to$ & $\gets$ & $\backslash gets$ \\ 
$\downarrow$ & $\backslash downarrow$ & $\uparrow$ & $\backslash upurrow$\\
$\leftrightarrow$ & $\backslash leftrightarrow$ & $\updownarrow$ & $\backslash updownarrow$\\ 
$\diamondsuit$ & $\backslash diamondsuit$ & $\heartsuit$ & $\backslash heartsuit$ \\ 
$\clubsuit$ & $\backslash clubsuit$ & $\spadesuit$ & $\backslash spadsuit$\\\hline 
\end{tabular}
\section{Znaki specjalne} \\ \\
$\%  - \backslash \% \\
 \# - \backslash \# \\
 \$  - \backslash \$ \\
 \& - \backslash \& \\
 \_  - \backslash \_ \\$
\newpage
\section{Zmiana fontu} \\
Rodzaje fontow: \\ \\
$\backslash textrm \lbrace \dots \rbrace	- 	\textrm{kroj szeryfowy} \\
\backslash texttt \lbrace \dots \rbrace - \texttt{grotesk} \\
\backslash textup \lbrace \dots \rbrace - \textup{odmiana prosta} \\
\backslash textsl \lbrace \dots \rbrace - \textsl{odmiana pochyla} \\
\backslash emph \lbrace \dots \rbrace - \emph{wyroznienie} \\
\backslash textbf \lbrace \dots \rbrace - \textbf{pismo grube} \\
\backslash textit \lbrace \dots \rbrace - \textit{kursywa} \\
\backslash textsc \lbrace \dots \rbrace - \textsc{kapitaliki}\\ \\$
Wielkosci fontow: \\ \\
$\lbrace \backslash Huge \dots \rbrace$ - {\Huge największy} \\
$\lbrace \backslash huge \dots \rbrace$ - {\huge ogromny} \\
$\lbrace \backslash LARGE \dots \rbrace$ - {\LARGE bardzo duży}\\
$\lbrace \backslash Large \dots \rbrace$ - {\Large większy}\\
$\lbrace \backslash large \dots \rbrace$ - {\large duży}\\
$\lbrace \backslash normalsize \dots \rbrace$ - {\normalsize normalny}\\
$\lbrace \backslash small \dots \rbrace$ - {\small mały}\\
$\lbrace \backslash footnotesize \dots \rbrace$ - {\footnotesize mniejszy }\\
$\lbrace \backslash scriptsize \dots \rbrace$ - {\scriptsize bardzo mały}\\
$\lbrace \backslash tiny \dots \rbrace$ - {\tiny mikroskopijny}\\ \\
\section{Marginesy} \\ \\
Zmiana marginesów (w preambule): \\ \\
$\backslash addtolength \lbrace \backslash textwidth \rbrace \lbrace 3cm \rbrace\\
\backslash addtolength \lbrace \backslash hoffset \rbrace \lbrace -1.5cm \rbrace\\
\backslash addtolength \lbrace \backslash textheight \rbrace \lbrace 3cm \rbrace\\
\backslash addtolength \lbrace \backslash voffset \rbrace \lbrace -1.5cm \rbrace\\$\\
Powyższe polecenia modyfikują domyślny układ strony, poszerzając domyślną szerokość i długość szpalty o 3cm.
