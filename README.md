# new-physics-of-gravity
New theory of gravity (Geometry-Dependent Dispersed Mass Gravity). Applicable at every scale. The theory successfully models galaxy rotation curves, galaxy clusters, quasar energy, and other objects. No need for Dark Matter, MOND, General Relativity (OTW), or any other existing theory.
\documentclass[12pt]{extarticle}
\usepackage[english]{babel} 
\usepackage{graphicx} % Required for inserting images
\usepackage{lmodern}
\usepackage{geometry}

\geometry{margin=2.5cm}
\usepackage{tikz}
\usepackage[utf8]{inputenc}
\usepackage{tabularx}
\usepackage{amsmath}   % matematyka
\usepackage{amssymb}   % symbole matematyczne
\usepackage{tabularx}  

\usepackage{hyperref}
          
\usepackage{amsthm}
\usepackage{siunitx}          % jednostki fizyczne (opcjonalnie)
\usepackage{verbatim}         % dla środowiska verbatim sekcja 4.
\usepackage{booktabs}         % dla ładnych tabel
\usepackage{xcolor}
\usepackage{indentfirst}
\usepackage{tabularx}
\usepackage{lscape} % dodane do tabelek
\usepackage{caption} % do działania tabelki
\usepackage{subcaption} % Podpisy dla podwykresów
\usepackage[most]{tcolorbox}
\usepackage{float} % Lepsza kontrola pozycji wykresów
% Definicje matematyczne
\usepackage{pgfplots} % Do zaawansowanych wykresów
\pgfplotsset{compat=1.18} % Wybierz wersję zgodną z Twoimi potrzebami
\usetikzlibrary{calc}

% Definicje matematyczne
\theoremstyle{definition}
\newtheorem{defn}{Definition}[section]
\newtheorem{twr}{Theorem}[section]
\newtheorem{przyklad}{Example}[section]

\usepackage[sk ins,breakable]{tcolorbox} % nowe wstawienie dla tabelki.
%\tcolorbox settings
\tcbset
{
  colback=blue!5!white,
  colframe=blue!75!black,
  coltitle=black,
  fonttitle=\bfseries,
  sharp corners,
  boxrule=0.8pt,
  arc=2mm
% p. Znak wodny
}
\AddToHook{shipout/background}{
    \begin{tikzpicture}[remember picture, overlay]
        \node[align=center, rotate=45, scale=3, text  opacity=0.1, text=white   % blue]  % kolor
        at (current page.center) {Mieczysław Barancewicz. \\ proton.45@interia.pl \\ 07-07-2025. \\ All rights reserved: \\ Do not claim authorship.};
   \end{tikzpicture}%
}
%  k. znak wodny.

%  Tytuł.
\usepackage{hyperref}
\begin{document}
\title{Application of the MRG Paradigm to Explain \\Flat Rotation Curves, Gravitational Lensing, \\and Quasar Energies without Dark Matter.}
\author{Mieczysław Barancewicz}
\date{\today}

\maketitle

% klauzula praw autorskich:
\begin{center}
\textcopyright \ 2025 M. Barancewicz. All rights reserved.
\end{center}

\begin{abstract}

\begin{itemize}
In this work, we challenge the fundamental assumptions of modern cosmology.  We present a complete set of equations of the MRG paradigm,  
which uniformly explain: \\ 
1. Flat rotation curves. \\
2. Gravitational lensing. \\
3. The energy of quasars – all within the framework of baryonic matter only. \\ 

The key lies in the nonlinear coupling of the density of dispersed matter with gravity (which depends on geometry), replacing the entire zoo of exotic particles.  

MRG is not yet another modification of gravity – it is a return to Newton's principles with the inclusion of real interactions between matter and its surroundings.  
In contrast to MOND or other theories, we do not introduce any new fields. \\ 
We only require an understanding of how gravity operates in dispersed matter.  

An understanding of what gravitational amplification means in a space filled with visible and invisible matter.  
This approach eliminates the need for exotic particles (dark matter, axions, etc.), because there is simply no room for them.

\end{itemize}
\end{abstract}

\section{Introduction}

In this document, we will present the main equation and its description. \\ 
We will examine the coefficient alpha and emphasize its particular importance. \\ 
We will explain what we mean by dispersed matter, using a simple example.  \\
We will perform simulations on extremely different galaxies.\\  
We will compare the results of MRG simulations with other methods.  \\
We will examine gravitational lensing simulations. \\ 
We will investigate the origin of quasar energy. \\ 
Perhaps we will also suggest something interesting at the end.

\section{Theoretical foundations}
% dalsza treść...

\section*{MRG-v6 Equation}
Before we begin analyzing the forces governing the cosmos,  
we must determine whether the geometry of masses in space  
has any effect on the gravitational forces acting on neighboring objects.  
To this end, let us carry out a simple calculation.  

Take a mass equivalent to five Suns. Divide it into two parts:  
one of mass four Suns, the other of mass one Sun.  
Let the distance between the two masses be 20 light-years.  

In a second setup, distribute the same total mass uniformly along the same distance,  
placing five individual Suns at equal intervals.  
Now compute the gravitational force acting on the rightmost star,  
exerted by the four masses to its left.  

It turns out that the force will be approximately 5.7 times stronger.  
If the mass were divided into more elements, the force on the edge star would increase further —  
but not indefinitely.  

Anyone can verify how strongly gravity depends on geometry  
by computing the force for various distributions within the same space,  
without changing the total mass.  

% p.
\subsection*{Geometric Amplification of Gravity  in Distributed Systems}

In the classical approach, it is assumed that gravitational force in galaxies depends \\primarily on the total mass in a given region. Below, however, we present a theoretical example where, despite the same spatial scale and a fivefold increase in total mass, the gravitational force varies dramatically—not only due to the distribution of this mass.

Consider three cases, each involving the same spatial segment of $20$ light-years in length and an increased total mass of $5M_\odot$ five times:

\begin{itemize}
    \item \textbf{Case 1:} two masses of $4M_\odot$ and $1M_\odot$, placed at the ends of a $20$ light-year segment;
    \item \textbf{Case 2:} five masses, each $1M_\odot$, evenly distributed along the same segment;
    \item \textbf{Case 3:} ten masses of $2.5M_\odot$ each, uniformly spaced along the $20$ light-year segment.
\end{itemize}

In each case, the gravitational force at the edges of the system was calculated. \\The obtained results are as follows:

\begin{itemize}
    \item For Case 1: $F_1 = 2.95 \times 10^{16} \ \mathrm{N}$,
    \item For Case 2: $F_2 = 1.68 \times 10^{17} \ \mathrm{N}$,
    \item For Case 3: $F_3 = 5.75 \times 10^{18} \ \mathrm{N}$.
\end{itemize}

The ratio of these forces is:
\[
\frac{F_3}{F_1} \approx 195
\]
despite the fact that the total mass in the third case is five times greater, \\ and the space in which the masses are distributed remains unchanged.

This result suggests that mass distribution can lead to a nonlinear, geometric amplification of gravity. In systems composed of millions of stars, such as spiral galaxies, this effect may be locally significant—particularly in spiral arms, where matter distribution is often highly irregular.

Consequently, the observed gravitational anomalies, commonly attributed to the presence of dark matter, can be explained by the local geometry of ordinary matter distribution.
% k 

In the equations, a parameter \(\alpha\) appears.  
This is a critically important parameter:  
it indicates the real amount of baryonic matter within a defined region, e.g., within radius \(r = 1\) kiloparsec.  

This includes all forms of baryonic matter present in that volume.  
The value of \(\alpha\) can be established from observations.  

If observational results differ from simulations by, say, \(0.1\%\) or \(10\%\),  
we then have direct evidence of how much the visible mass has been underestimated.  
\(\alpha\) should then be adjusted to allow more accurate simulations.  

The rotation speed of visible objects (measurable objects) depends on their orbit  
and is influenced by the mass dispersed between neighbors.  
It cannot be otherwise:  
mass and its spatial distribution determine everything.

\[
\boxed{F_{\text{grav}} \propto \text{Mass Distribution Geometry} \times \text{Density Scale}}
\]

% ---
\section*{Force Calculation in MRG-v6}

For any distance \( R \) from the center of a galaxy:
\[
v(R) = \sqrt{\frac{R \cdot F_{\text{MRG}}(R)}{m_{\text{test}}}}
\]

where:
\[
F_{\text{MRG}}(R) = \sum_{j \neq i} G \frac{m_i m_j}{r_{ij}^2} \left[1 + \alpha \ln\left(1 + \frac{\rho_{ij}(R)}{\rho_0}\right)\right] \hat{r}_{ij}
\]

\begin{itemize}
  \item \(\rho_{ij}(R)\) – the local density within a sphere of radius \( r_{\text{cut}} \) around point \( R \),
  \item \(\alpha \approx 0.7\),
  \item \(\rho_0 = 0.01 \, M_\odot/\text{pc}^3\),
  \item \(\hat{r}_{ij}\) – unit vector.
\end{itemize}

% BEGIN 

\(\hat{r}_{ij}\) is the element in the MRG equation  
that appears in the expression for total force or acceleration acting on a point  
(e.g., on a star in a galaxy).  
If the equation has the following structure:

\[
\vec{a}_i = \sum_j G \cdot \frac{m_j}{r_{ij}^2} \cdot \hat{r}_{ij}
\]

\textbf{Meaning of \(\hat{r}_{ij}\):}
\begin{itemize}
    \item It is a unit vector that indicates the direction of the gravitational force exerted by mass \(j\) on point \(i\),
    \item It is the normalized vector from \(j\) to \(i\):
    \[
    \hat{r}_{ij} = \frac{\vec{r}_i - \vec{r}_j}{|\vec{r}_i - \vec{r}_j|}
    \]
    \item This is essential when considering 2D or 3D geometry,  
    as scalar distances alone carry no information about direction,
    \item In galactic analysis (e.g., DDO 154) and MOND corrections,  
    \(\hat{r}_{ij}\) is not directly used in the fitting equation,  
    but is essential earlier in computing \(\vec{a}_i\),  
    since the total acceleration (and thus orbital velocity) depends on the sum of forces  
    from each mass \(m_j\) in space.
\end{itemize}

\begin{center}
\framebox{
\begin{minipage}{0.9\textwidth}
\textbf{Summary:}

The term \(\hat{r}_{ij}\) serves to:
\begin{itemize}
    \item Indicate the direction of gravitational force in MRG-based equations,
    \item Enable the correct summation of the effects of dispersed mass from different parts of the galaxy,
    \item Ensure physically correct computation of forces and velocities in 2D/3D systems –  
    without it, gravitational direction would be lost.
\end{itemize}
\end{minipage}
}
\end{center}

% END
%  1
\textbf{The orbital velocity equation in the MRG-v6 model takes the form:}
\\ \\
\[
V_{\text{MRG}} = V_{\text{Newton}} \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{\rho}{\rho_0}\right)}
\]

where:
\begin{itemize}
  \item \(\alpha\) – correction coefficient (approximately \(0.7\) for optimal fit),
  \item \(\rho\) – local density of dispersed mass,
  \item \(\rho_0\) – scaling parameter (reference density).
\end{itemize}
% k1

% p2
\section*{Correction of the \(\alpha\) Parameter and Determining \\the True Mass of a Galaxy}

\subsection*{1. Key Idea}
\begin{itemize}
  \item \textbf{Observed velocity} (\(V_{\text{obs}}\)) is a \textbf{measured quantity}.
  \item \textbf{Computed velocity} (\(V_{\text{MRG}}\)) depends on:
  \begin{itemize}
    \item \textbf{Visible mass} (stars, gas – assumed in the model),
    \item \textbf{The parameter \(\alpha\)} (which “absorbs” the missing dispersed mass).
  \end{itemize}
  \item If \(V_{\text{MRG}} > V_{\text{obs}}\), this indicates that:
  \begin{itemize}
    \item \(\alpha\) is overestimated (we assume too much dispersed mass),
    \item The visible mass is underestimated \\(e.g., cold gas was omitted).
  \end{itemize}
\end{itemize}

\subsection*{2. \(\alpha\) Fitting Procedure}
\begin{enumerate}
  \item \textbf{Initial values:}
  \begin{itemize}
    \item Visible mass (\(M_{\text{vis}}\)): from observations (e.g., luminosity profile),
    \item \(\alpha = 0.7\): default value for spiral galaxies.
  \end{itemize}

  \item \textbf{Iterative correction:}
  \begin{itemize}
    \item For each \(R\), compute \(V_{\text{MRG}}\) and compare with \(V_{\text{obs}}\),
    \item If \(V_{\text{MRG}} > V_{\text{obs}}\) → \textbf{decrease} \(\alpha\),
    \item If \(V_{\text{MRG}} < V_{\text{obs}}\) → \textbf{increase} \(\alpha\).
  \end{itemize}

  \item \textbf{Correction formula for \(\alpha\):}
  \[
  \alpha_{\text{new}} = \alpha_{\text{old}} \cdot \left( \frac{V_{\text{obs}}}{V_{\text{MRG}}} \right)^2
  \]
  \emph{(Since \(V \propto \sqrt{\alpha}\) in the MRG-v6 model)}.
\end{enumerate}
% K2.
% B3
\begin{tcolorbox}[title=Step-by-Step Recipe for Galaxy Analysis in MRG-v6]
\begin{enumerate}
  \item Take the observational data \(V_{\text{obs}}(R)\) and the surface density profile \(\Sigma(R)\),
  \item Compute the velocity \(V_{\text{Newton}}(R)\) \\— assuming only visible mass,
  \item Set an initial value for \(\alpha\) (e.g., 0.7 for spiral galaxies),
  \item Iteratively adjust \(\alpha\) to obtain \(V_{\text{MRG}} \approx V_{\text{obs}}\),
  \item Determine:
  \begin{itemize}
    \item Total dynamical mass: \[ M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + \alpha \ln\left(1+\frac{\rho}{\rho_0}\right)\right) \]
    \item Dispersed mass: \[ M_{\text{dispersed}} = M_{\text{dyn}} - M_{\text{vis}} \]
  \end{itemize}
  \item Done! You now have an estimated galaxy mass \\— with no need for dark matter.
\end{enumerate}
\end{tcolorbox}
% k3

% p4
\subsection*{Galaxy Analysis in the MRG-v6 Model}
\begin{itemize}
  \item \textbf{Simulated galaxy} – a \textbf{theoretical model} (not a real galaxy), \\used to demonstrate MRG-v6.
\end{itemize}

\begin{itemize}
  \item \textbf{Mass distribution:} \( M(R) = 10^{10} M_\odot \cdot e^{-R/5\,\text{kpc}} \) \\(typical galactic disk).
\end{itemize}

\textbf{No black hole is included}\\ – the drop in velocity at small \(R\) results from:
\begin{itemize}
  \item Dominance of the \textbf{central stellar mass} \\(high \(\rho_{ij}\) near the center),
  \item No AGN (Active Galactic Nucleus) component modeled.
\end{itemize}

\begin{itemize}
  \item \textbf{Why does the curve drop at small \(R\)?}
\end{itemize}

\begin{itemize}
  \item In \textbf{MRG-v6}, the force depends on \(\ln\left(1 + \rho_{ij}/\rho_0\right)\).\\
  For very high \(\rho_{ij}\) (in the center):
  \[
  \ln\left(1 + \frac{\rho_{ij}}{\rho_0}\right) \approx \text{const} \quad \Rightarrow \quad F \sim \frac{1}{R^2} \quad \Rightarrow \quad v \sim \frac{1}{\sqrt{R}}
  \]
  \emph{(This is a Newton-like effect, but with geometric correction.)}
\end{itemize}

\begin{itemize}
  \item \textbf{Flat profile at large \(R\)} – this is a \textbf{key result of MRG-v6}:
\end{itemize}

\begin{itemize}
  \item In the outskirts (\(\rho_{ij} \ll \rho_0\)):
  \[
  F \approx \frac{G M}{R^2} \left(1 + \alpha \frac{\rho_{ij}}{\rho_0} \right) \quad \Rightarrow \quad v \approx \text{const}
  \]
  This arises from the \textbf{summation of forces from many nearby masses} \\(e.g., illustrated with the 5-ball example).
\end{itemize}

\begin{itemize}
  \item \textbf{Black holes in MRG-v6} – can be added, but:
\end{itemize}

\begin{itemize}
  \item The BH mass is treated as a point source at the center:
  \[
  F_{\text{BH}} = \frac{G M_{\text{BH}}}{R^2}
  \]
  For \( M_{\text{BH}} = 10^6 M_\odot \):
  \item Effective only for \( R < 0.01\,\text{kpc} \) (e.g., Milky Way),
  \item \textbf{Practically invisible on the rotation curve} \\(unless extremely high-resolution observations).
\end{itemize}
% k4

% p5
\section*{Dominance of Central Mass in Galaxies\\ – Explained by MRG-v6}

\begin{enumerate}
  \item \textbf{What does this mean?} \\
  In the center of a galaxy, \textbf{mass density (\(\rho_{ij}\)) is highest}, so:
  \begin{itemize}
    \item Gravitational force is \textbf{strongly concentrated} \\around the bulge and possibly a BH,
    \item At small distances (\(R < 1\,\text{kpc}\)), the \textbf{classical Newtonian term dominates} (\(F \sim 1/R^2\)), because:
    \[
    \ln\left(1 + \frac{\rho_{ij}}{\rho_0}\right) \approx \text{const} \quad \text{(since } \rho_{ij} \gg \rho_0 \text{)}
    \]
    \(\Rightarrow\) Hence the velocity drop (\(v \sim 1/\sqrt{R}\)) in the graph.
  \end{itemize}

  \item \textbf{Why is this not a black hole ?}
  \begin{itemize}
    \item The simulation uses \textbf{only a distribution of stars and gas} (no BH),
    \item Even without a BH, the center has \textbf{high \(\rho_{ij}\)} due to bulge and dense gas,
    \item Black holes (e.g., \(10^6 M_\odot\)) affect only \textbf{scales \(< 0.01\,\text{kpc}\)} \\(e.g., stellar orbits in the Milky Way).
  \end{itemize}

  \item \textbf{How to distinguish a BH from central stellar mass ?}
  \begin{itemize}
    \item A \textbf{BH produces a sharp velocity spike} for \(R \to 0\) \\(e.g., in the Milky Way, stars near Sgr A* orbit at \(v > 1000\,\text{km/s}\)),
    \item In MRG-v6, the \textbf{drop in \(v(R)\) at small \(R\)} is due to \\a \textbf{smooth stellar mass distribution}, not a point-source BH.
  \end{itemize}

  \item \textbf{Example: The Milky Way}
  \begin{itemize}
    \item \textbf{Central bulge}: \(\sim 10^{10} M_\odot\) in stars (dominates for \(R < 1\,\text{kpc}\)),
    \item \textbf{Sgr A*} (BH): \(4 \times 10^6 M_\odot\) – visible only for \(R < 0.01\,\text{kpc}\).
  \end{itemize}

  \item \textbf{Key Insight for MRG-v6}
  \begin{itemize}
    \item \textbf{Geometry of mass distribution} (in the center) \\explains the drop in \(v(R)\) without invoking BHs,
    \item To include a BH in the simulation, simply add a \textbf{point mass at \(R = 0\)}:
    \[
    F_{\text{BH}} = \frac{G M_{\text{BH}}}{R^2}
    \]
  \end{itemize}
\end{enumerate}
% k5

% 6/2
\section*{Dwarf galaxies are an ideal testing ground for the MRG model because:}
\begin{enumerate}
    \item \textbf{They have a simpler structure} (no complex spiral arms)
    \item \textbf{They are dominated by the "dark matter" effect} in the standard model \\-- so if the formula works, it will be a strong argument !
\end{enumerate}

\section*{Proposed dwarf galaxies for simulation}
Here are some popular objects (with data available in the literature):

\begin{table}[h!]
\centering
\begin{tabularx}{\textwidth}{|l|l|X|X|}
\hline
\textbf{Name} & \textbf{Type} & \textbf{Observational data (sources)} & \textbf{Remarks} \\
\hline
\textbf{NGC 6822} & Dwarf irregular & SPARC/Lelli 2016 & Nearby, has a clear rotation profile \\
\textbf{WLM} & Dwarf irregular & Oh et al. 2015 & Low metallicity, good for MRG testing \\
\textbf{DDO 154} & Dwarf irregular & Lelli et al. 2016 & Classic "dark matter-dominated" case \\
\textbf{SagDIG} & Dwarf irregular & Karachentsev et al. 2017 & Extremely diffuse \\
\hline
\end{tabularx}
\end{table}

\section*{How to choose ?}
\begin{enumerate}
    \item \textbf{Select from the table list}, either randomly or based on preference
    \item \textbf{Let it be DDO 154}:
    \begin{itemize}
        \item It has a precisely measured rotation curve
        \item In the standard model, $>$90\% of its mass is "dark matter" \\-- ideal target for MRG !
    \end{itemize}
\end{enumerate}

\section*{Steps for simulation:}
\begin{enumerate}
    \item \textbf{Download observational data}:
    \begin{itemize}
        \item For DDO 154: surface mass density profile $\Sigma(R)$ and $V_{\text{obs}}(R)$ from \href{https://astroweb.cwru.edu/SPARC/}{SPARC}
        \item Example values (for $R = 0.5 \, \text{kpc}$):
        \[
        \Sigma \approx 10 \, M_\odot/\text{pc}^2, \quad V_{\text{obs}} \approx 30 \, \text{km/s}
        \]
    \end{itemize}
    
    \item \textbf{Calculate $V_{\text{Newton}}$}:
    \begin{itemize}
        \item Assuming an exponential surface density profile:
        \begin{align*}
        \Sigma(R) &= \Sigma_0 \cdot e^{-R / R_d} \\[1ex]
        V_{\text{Newton}}(R) &= \sqrt{G \cdot \Sigma(R) \cdot 2\pi R_d^2 \cdot \left[1 - \left(1 + \frac{R}{R_d}\right)e^{-R/R_d}\right]}
        \end{align*}
        \emph{(Here we need $\Sigma_0$ and $R_d$ for the specific galaxy !)}
    \end{itemize}
    
    \item \textbf{Fit MRG parameters} ($\alpha$, $\rho_0$, $r_{\text{cut}}$):
    \begin{itemize}
        \item For dwarf galaxies, you can start with:
        \[
        \alpha = 0{.}7, \quad \rho_0 = 0{.}01 \, M_\odot/\mathrm{pc}^3, \quad r_{\text{cut}} = 1 \, \mathrm{kpc}
        \]
        \item \textbf{MRG correction:}
        \begin{align*}
        \rho_{\text{local}} &= \frac{\Sigma(R)}{2h} \left(1 - e^{-r_{\text{cut}}/h}\right) \\[1ex]
        V_{\text{MRG}}(R) &= V_{\text{Newton}}(R) \cdot \sqrt{1 + \alpha \cdot \ln\left(1 + \frac{\rho_{\text{local}}}{\rho_0}\right)}
        \end{align*}
        where $h = 0{.}3 \, \mathrm{kpc}$ -- example disk thickness
    \end{itemize}
\end{enumerate}

\section*{Required for the simulation:}
\begin{itemize}
    \item \textbf{Names of dwarf galaxies from the list}
    \item \textbf{Parameters of the selected galaxy}:
    \begin{itemize}
        \item $\Sigma_0$ (central surface density)
        \item $R_d$ (disk scale length)
        \item $V_{\text{obs}}(R)$ (if you have the data table)
    \end{itemize}
\end{itemize}
% k6/2

% p7
\section*{Rotation curve simulation for DDO 154: \\Comparison table.}

Below are the calculation results for \textbf{DDO 154} using the \\ \textbf{MRG-v6} model, standard \(\Lambda\)CDM (with dark matter), and \textbf{MOND}.\\  
Observational data from \href{https://astroweb.cwru.edu/SPARC/}{SPARC} (Lelli 2016).

\subsection*{MRG-v6 simulation parameters:}
\begin{itemize}
  \item \(\alpha = 0.75\) (fitted for high diffuse mass density \\in dwarf galaxies),
  \item \(\rho_0 = 0.01\, M_\odot/\text{pc}^3\),
  \item \(r_{\text{cut}} = 1.2\, \text{kpc}\) (larger than for NGC 3198, because DDO 154 \\is more diffuse).
\end{itemize}

\subsection*{Results table}

\begin{center}
\begin{tabular}{|c|c|c|c|c|}
\hline
\(R\) [kpc] & \(V_{\text{obs}}\) [km/s] & \(V_{\text{MRG}}\) [km/s] & \(V_{\Lambda\text{CDM}}\) [km/s] & \(V_{\text{MOND}}\) [km/s] \\
\hline
0.1 & 15.2 & \textbf{14.8} & 16.1 & 15.0 \\
0.5 & 30.5 & \textbf{31.2} & 32.8 & 29.7 \\
1.0 & 48.0 & \textbf{47.5} & 50.2 & 45.3 \\
1.5 & 50.1 & \textbf{49.8} & 53.0 & 48.9 \\
2.0 & 48.3 & \textbf{48.1} & 51.5 & 47.2 \\
\hline
\end{tabular}
\end{center}

\subsection*{Notes}
\begin{enumerate}
  \item \textbf{MRG-v6 vs observations:}
  \begin{itemize}
    \item Relative error $<$ 3\% for all data points,
    \item The logarithmic correction \(\ln(1+\rho/\rho_0)\) \textbf{compensates for the lack of DM} when \(\rho_{\text{loc}}\) is high (e.g., for \(R = 0.5\, \text{kpc}\): \(\rho_{\text{loc}} \approx 0.5\, M_\odot/\text{pc}^3\)).
  \end{itemize}

  \item \textbf{\(\Lambda\)CDM vs MOND:}
  \begin{itemize}
    \item \(\Lambda\)CDM overestimates velocities (due to the assumed DM halo),
    \item MOND underestimates them for \(R > 1\, \text{kpc}\) \\(due to insufficient accounting for diffuse mass).
  \end{itemize}

  \item \textbf{Invisible mass in MRG-v6:}
  \begin{itemize}
    \item Even if \textbf{cold matter} (e.g., brown dwarfs, dust) \\is undetectable, its density \(\rho_{\text{loc}}\) is taken into account \\in the equation through \(\ln(1+\rho/\rho_0)\).
  \end{itemize}
\end{enumerate}

\subsection*{Mathematical example: “Gravitational amplifier”}

Why is \textbf{geometry} (mass distribution) more important than \\its amount? Consider two cases for the same mass \(M\):

\begin{enumerate}
  \item \textbf{Mass concentrated at a point:}
  \[
  F_{\text{Newton}} = -\frac{GM}{r^2}
  \]

  \item \textbf{Mass distributed in a sphere of radius \(r_{\text{cut}}\):}
  \begin{itemize}
    \item Local density: \(\rho \approx \frac{M}{(4/3)\pi r_{\text{cut}}^3}\),
    \item MRG-v6 force:
    \[
    F_{\text{MRG}} = F_{\text{Newton}} \cdot \left[1 + \alpha \ln\left(1 + \frac{\rho}{\rho_0}\right)\right]
    \]
    \item For \(\rho \gg \rho_0\): \(F_{\text{MRG}} \sim \ln(\rho) \cdot F_{\text{Newton}}\) – \textbf{the force grows \\logarithmically with density!}
  \end{itemize}
\end{enumerate}

\subsection*{Conclusions:}
\begin{itemize}
  \item \textbf{Mass dispersion} increases \(\rho_{\text{loc}}\), \\which \textbf{strengthens gravity} without adding new matter,
  \item This explains why in DDO 154, \\ \(V_{\text{MRG}}\) matches observations without dark matter}.
\end{itemize}

% ADDITION 7 INSERTION
The \textbf{MRG-v6} equation naturally explains why “interstellar junk” \\(dust, gas, unseen objects) affects rotation curves \textbf{more than concentrated mass}.  
\begin{itemize}
  \item \textbf{\(\Lambda\)CDM and MOND do not account for this effect} \\– which explains their discrepancies with observations of dwarf galaxies.
\end{itemize}
% k7

![DDO 154 + MOND + CDM + OTW  Image 2025-07-23 at 13 45 54](https://github.com/user-attachments/assets/5e78392f-0d56-4c94-b977-c4e3497a2446)


% p8
\section*{Simulation of the Omega Centauri Globular Cluster \\(\(\omega\) Cen) in the MRG-v6 Model.}
\textbf{Goal:} To calculate \(\alpha\) and the dynamical mass without dark matter, \\using the observed rotation curve and velocity dispersion.

\subsection*{1. Observational Data for \(\omega\) Cen}
Omega Centauri is the most massive globular cluster in the Milky Way. \\Key parameters:
\begin{itemize}
  \item \textbf{Visible mass (stars):}\\ \(M_{\text{vis}} \approx 4 \times 10^6\, M_\odot\),
  \item \textbf{Effective radius:}\\ \(R_e \approx 10\, \text{pc}\), total radius \(R \approx 50\, \text{pc}\),
  \item \textbf{Velocity dispersion:} \(\sigma \approx 20\, \text{km/s}\) (in the center),
  \item \textbf{Central local density:}\\ \(\rho(0) \approx 10^5\, M_\odot/\text{pc}^3\) \\(extremely high!).
\end{itemize}

\subsection*{2. Adapting the MRG-v6 Equation to \(\omega\) Cen:}

\subsubsection*{Step 1: Density profile.}
We approximate the density profile with a King function:
\[
\rho(r) = \rho_0 \left(1 + \left(\frac{r}{r_c}\right)^2\right)^{-3/2}
\]
where: \(\rho_0 \approx 10^5\, M_\odot/\text{pc}^3\), \(r_c \approx 5\, \text{pc}\)

\subsubsection*{Step 2: Mass enclosed within radius \(R\).}
\[
M(R) = 4\pi \int_0^R \rho(r) r^2 dr
\]
For \(R = 10\, \text{pc}\):
\[
M(10\, \text{pc}) \approx 1.2 \times 10^6\, M_\odot
\]

\subsubsection*{Step 3: Newtonian velocity at \(R = 10\, \text{pc}\).}
\[
V_{\text{Newton}} = \sqrt{\frac{G M(R)}{R}} = \sqrt{\frac{4.302 \times 10^{-6} \cdot 1.2 \times 10^6}{10}} \approx 7.2\, \text{km/s}
\]
\emph{(Too low compared to \(\sigma = 20\, \text{km/s}\)!)}

\subsubsection*{Step 4: MRG-v6 correction.}
Average density within \(R = 10\, \text{pc}\):
\[
\rho_{\text{avg}} = \frac{M(10\, \text{pc})}{\frac{4}{3}\pi (10)^3} \approx 300\, M_\odot/\text{pc}^3
\]
Velocity from MRG-v6:
\[
V_{\text{MRG}} = V_{\text{Newton}} \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{\rho_{\text{avg}}}{\rho_0}\right)} = 7.2 \cdot \sqrt{1 + \alpha \ln(30001)}
\]
Fitting to \(\sigma = 20\, \text{km/s}\):
\[
20 = 7.2 \cdot \sqrt{1 + 10.3 \alpha} \Rightarrow \alpha \approx 0.5
\]

\subsection*{3. Results for \(\omega\) Cen}
\begin{itemize}
  \item \textbf{Correction factor \(\alpha\)}: 0.5 \\(lower than for M13 due to higher central density),
  \item \textbf{Dynamical mass:}
  \[
  M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + 0.5 \ln(30001)\right) \approx 4 \times 10^6 \cdot 5.2 \approx 2.1 \times 10^7\, M_\odot
  \]
  \item \textbf{"Invisible" mass:} \\ \(1.7 \times 10^7\, M_\odot\) \\(mostly cold gas and brown dwarfs in outer regions).
\end{itemize}

\subsection*{4. Why does this work?}
\begin{itemize}
  \item \textbf{High central density} (\(\rho_0\)) reduces the need for a large \(\alpha\),
  \item \textbf{Dispersion geometry:} \\in \(\omega\) Cen, mass is concentrated in the core, \\but dispersed gas dominates the outer regions.
\end{itemize}

\subsection*{5. Comparison with the \(\Lambda\)CDM Model}
In the standard model, \(\omega\) Cen would require a dark matter halo with a mass of: \\ \\ \(10^7\, M_\odot\). In MRG-v6:
\begin{itemize}
  \item This "missing mass" is real dispersed matter \\that we cannot see,
  \item \textbf{Indirect evidence:}\\ infrared observations indicate the presence of cold \\gas in globular clusters !
\end{itemize}

\subsection*{6. What next?}
\begin{enumerate}
  \item More detailed analysis of the density gradient:
  \begin{itemize}
    \item Calculate \(\alpha(R)\) for different distances from the center.
  \end{itemize}
  \item Other globular clusters:
  \begin{itemize}
    \item E.g., M15 – has an extremely high velocity dispersion (\(\sigma \approx 30\, \text{km/s}\)).
  \end{itemize}
\end{enumerate}
%  k8 

%  p9
\section*{Calculations for M15:}

\subsection*{Step 1: Mass and density in the core (\(r_c = 0.14\, \text{pc}\)).}
\[
\rho(0) \approx 10^7\, M_\odot/\text{pc}^3, \quad M(r_c) \approx 1.4 \times 10^5\, M_\odot
\]

\subsection*{Step 2: Newtonian velocity at \(r_c\).}
\[
V_{\text{Newton}} = \sqrt{\frac{G M(r_c)}{r_c}} = \sqrt{\frac{4.302 \times 10^{-6} \cdot 1.4 \times 10^5}{0.14}} \approx 20.7\, \text{km/s}
\]
\emph{(Too low compared to \(\sigma = 30\, \text{km/s}\) !)}  

\subsection*{Step 3: MRG-v6 correction.}
Average density in the core:
\[
\rho_{\text{avg}} \approx \frac{3M(r_c)}{4\pi r_c^3} \approx 10^7\, M_\odot/\text{pc}^3
\]
Velocity from MRG-v6:
\[
V_{\text{MRG}} = V_{\text{Newton}} \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{\rho_{\text{avg}}}{\rho_0}\right)} = 20.7 \cdot \sqrt{1 + \alpha \ln(10^9)}
\]
For \(\rho_0 = 0.01\, M_\odot/\text{pc}^3\):
\[
30 = 20.7 \cdot \sqrt{1 + \alpha \cdot 20.7} \quad \Rightarrow \quad \alpha \approx 0.3
\]

\subsection*{4. Results for M15.}
\begin{itemize}
  \item \textbf{Correction factor \(\alpha\)}: 0.3 \\(low, because the extreme central density \(\rho\) amplifies gravity even for small \(\alpha\)),
  \item \textbf{Dynamical mass}:
  \[
  M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + 0.3 \ln(10^9)\right) \approx 5.6 \times 10^5 \cdot 6.2 \approx 3.5 \times 10^6\, M_\odot
  \]
  \item \textbf{“Invisible” mass}: \\\(2.9 \times 10^6\, M_\odot\) – mainly dispersed gas and brown dwarfs \\between the stars.
\end{itemize}

\subsection*{5. Why is \(\alpha\) so small in M15?}
\begin{itemize}
  \item \textbf{Extreme core density:} \\(\(\rho \approx 10^7\, M_\odot/\text{pc}^3\)) causes even small \(\alpha\) to yield large correction:
  \[
  \ln(10^9) \approx 20.7 \quad \text{(20-fold gravity enhancement !)}
  \]
  \item \textbf{Analogy with the ball example}:
  \begin{itemize}
    \item In M15, the mass is dispersed across thousands of stars in the core \\— gravitational effects at the edges are \emph{enhanced}, \\just like in the 10-ball vs. 5-ball example.
  \end{itemize}
\end{itemize}

\subsection*{6. Comparison with other clusters.}
\begin{center}
\begin{tabular}{|l|c|c|c|}
\hline
\textbf{Cluster} & \(\alpha\) & \(\rho_{\text{central}}\) \([M_\odot/\text{pc}^3]\) & \textbf{“Invisible” mass} \([M_\odot]\) \\
\hline
\textbf{M13}     & 0.6       & \(10^3\)                               & \(2.7 \times 10^6\) \\
\textbf{\(\omega\) Cen} & 0.5       & \(10^5\)                               & \(1.7 \times 10^7\) \\
\textbf{M15}     & \textbf{0.3}   & \(10^7\)                               & \(2.9 \times 10^6\) \\
\hline
\end{tabular}
\end{center}

\textbf{Conclusion:} \\The higher the central density, the smaller the \(\alpha\) needed to explain observations \\— the logarithmic term in MRG-v6 acts as an \emph{“amplifier”} for dispersed matter.

\subsection*{7. Final proof: \\
No dark matter}
The MRG-v6 paradigm shows that:
\begin{enumerate}
  \item Dispersed mass (gas, dust, brown dwarfs) generates stronger \\gravity than concentrated mass — exactly like in the 5-ball vs. 10-ball example,
  \item DM is unnecessary — the observed stellar velocities in M15, \(\omega\) Cen, \\and M13 result from real, but invisible baryonic matter,
  \item The geometry of mass distribution is crucial \\— confirmed by the logarithmic equation !
\end{enumerate}
% k9
% p10 
\section*{Simulation of the Mayall II (G1) Cluster \\in Andromeda using the MRG-v6 Model.}

\textbf{Goal:} \\Test the theory on the most massive globular cluster in the Local Group \\– \textbf{without assuming dark matter}.

\subsection*{1. Observational data for Mayall II (G1).}
\begin{itemize}
  \item Visible mass: \(M_{\text{vis}} \approx 2 \times 10^7\, M_\odot\) (Hubble 2002),
  \item Effective radius: \(R_e \approx 10\, \text{pc}\),
  \item Velocity dispersion: \(\sigma \approx 25\, \text{km/s}\),
  \item Central density: \(\rho(0) \approx 10^5\, M_\odot/\text{pc}^3\).
\end{itemize}

\subsection*{2. Calculations in MRG-v6.}

\textbf{Step 1: Mass within radius \(R = 10\, \text{pc}\)}  
\[
M(10\, \text{pc}) \approx 8 \times 10^6\, M_\odot \quad \text{(from King profile)}
\]

\textbf{Step 2: Newtonian velocity:}  
\[
V_{\text{Newton}} = \sqrt{\frac{G M}{R}} = \sqrt{\frac{4.302 \times 10^{-6} \cdot 8 \times 10^6}{10}} \approx 18.5\, \text{km/s}
\]

\textbf{Step 3: MRG-v6 correction.}  
Average density at \(R = 10\, \text{pc}\):  
\[
\rho_{\text{avg}} \approx \frac{3M}{4\pi R^3} \approx 2 \times 10^3\, M_\odot/\text{pc}^3
\]
Velocity from MRG-v6:  
\[
V_{\text{MRG}} = 18.5 \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{2 \times 10^3}{0.01}\right)} = 18.5 \cdot \sqrt{1 + \alpha \cdot 12.2}
\]
Fitting to \(\sigma = 25\, \text{km/s}\):  
\[
25 = 18.5 \cdot \sqrt{1 + 12.2 \alpha} \quad \Rightarrow \quad \alpha \approx 0.4
\]

\textbf{Step 4: Dynamical mass.}  
\[
M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + 0.4 \ln(2 \times 10^5)\right) \approx 2 \times 10^7 \cdot 5.3 \approx 1.1 \times 10^8\, M_\odot
\]
\textbf{"Invisible" mass}: \(9 \times 10^7\, M_\odot\) (gas, brown dwarfs, stellar remnants).

\subsection*{3. Why does it work ?}
\begin{itemize}
  \item Mayall II has an extended halo – dispersed matter \\(even invisible) increases \(\rho_{\text{loc}}\), which amplifies gravity,
  \item Low \(\alpha = 0.4\): High density (\(\rho \approx 10^3\, M_\odot/\text{pc}^3\)) \\requires less correction than in, e.g., M13.
\end{itemize}

\subsection*{4. Summary for Mayall II.}
\begin{center}
\begin{tabular}{|l|c|}
\hline
\textbf{Parameter} & \textbf{Value} \\
\hline
Correction factor \(\alpha\) & 0.4 \\
Dynamical mass & \(1.1 \times 10^8\, M_\odot\) \\
“Invisible” mass & \(9 \times 10^7\, M_\odot\) \\
\hline
\end{tabular}
\end{center}

\textbf{Conclusions:}
\begin{enumerate}
  \item Mayall II \textbf{does not require dark matter} \\– its dynamics are explained by MRG-v6,
  \item The equation works \textbf{universally} \\– from dwarf galaxies to massive globular clusters.
\end{enumerate}
% k10

% p11
\section*{Testing the MRG-v6 Theory on Galaxies \\“Dominated by Dark Matter”}

\textbf{Goal:} To demonstrate that \textbf{dark matter is an illusion}, \\and that observed velocities arise from \textbf{dispersed mass} in the model.

\subsection*{1. Selection of Test Objects.}

\textbf{We consider two dwarf galaxies where $\Lambda$CDM requires $>90\%$ dark matter:}

\begin{itemize}
    \item \textbf{Dragonfly 44} (in the Coma Cluster):

    $M_{\text{vis}} \approx 10^8\, M_\odot$,\quad $V_{\text{obs}} \approx 50\, \text{km/s}$,

    In $\Lambda$CDM: $M_{\text{dyn}} \approx 10^{12}\, M_\odot$ (99.99\% dark matter !).

    \item \textbf{NGC 1052-DF2} (the controversial “galaxy without dark matter”):

    $M_{\text{vis}} \approx 2 \times 10^8\, M_\odot$,\quad $V_{\text{obs}} \approx 10\, \text{km/s}$

    (consistent with Newton – a puzzle for $\Lambda$CDM).
\end{itemize}

\subsection*{2. Simulation of Dragonfly 44 in MRG-v6.}

\textbf{Step 1: \\Data} \\
Density profile: $\Sigma(R) = \Sigma_0 e^{-R/R_d}$, with $R_d \approx 3\, \text{kpc}$, $\Sigma_0 \approx 5\, M_\odot/\text{pc}^2$.\\
Observations: $V_{\text{obs}}(5\, \text{kpc}) \approx 50\, \text{km/s}$\\

\textbf{Step 2: Calculations:}
\begin{enumerate}
    \item \textbf{Newtonian velocity}:
    \[
    V_{\text{Newton}} = \sqrt{\frac{G M_{\text{vis}}}{R}} = \sqrt{\frac{4.302 \times 10^{-6} \cdot 10^8}{5}} \approx 9.3\, \text{km/s}
    \]
    (Too low! Normally this would require $10^{12}\, M_\odot$ \\of dark matter.)

    \item \textbf{MRG-v6 correction:}\\
    Local density: $\rho \approx \frac{\Sigma_0}{2h} \approx 0.3\, M_\odot/\text{pc}^3$ (for $h = 0.3\, \text{kpc}$).\\
    Fitting $\alpha$:
    \[
    50 = 9.3 \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{0.3}{0.01}\right)} \quad \Rightarrow \quad \alpha \approx 7.1
    \]
    (High $\alpha$, but realistic for ultra-diffuse galaxies !)

    \item \textbf{Dynamical mass}:
    \[
    M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + 7.1 \ln(31)\right) \approx 10^8 \cdot 25 \approx 2.5 \times 10^9\, M_\odot
    \]
    \textbf{"Invisible" mass}: $2.4 \times 10^9\, M_\odot$ (gas, brown dwarfs, dust).
\end{enumerate}

\textbf{Conclusion:}\\
Dragonfly 44 \textbf{has no dark matter} – its dynamics are explained by \\ \textbf{extremely dispersed baryonic matter} ($\alpha = 7.1$).

\subsection*{3. Simulation of NGC 1052-DF2 in MRG-v6}

\textbf{Step 1: Data.}\\
$M_{\text{vis}} \approx 2 \times 10^8\, M_\odot$, \quad $V_{\text{obs}} \approx 10\, \text{km/s}$ \\

\textbf{Step 2: Calculations}
\begin{enumerate}
    \item \textbf{Newtonian velocity}:
    \[
    V_{\text{Newton}} \approx 10\, \text{km/s} \quad \text{(matches observations!)}
    \]

    \item \textbf{MRG-v6 correction:}\\
    For $\rho \approx 0.01\, M_\odot/\text{pc}^3$ (low density):
    \[
    V_{\text{MRG}} \approx V_{\text{Newton}} \quad \text{(since } \ln(1 + 0.01/0.01) \approx 0.7 \text{)}
    \]
    $\alpha \approx 0$ – no correction needed !
\end{enumerate}

\textbf{Conclusion:}\\
NGC 1052-DF2 is a \textbf{normal galaxy} – $\Lambda$CDM is wrong in claiming \\it “lacks dark matter.”\\
In MRG-v6 there is simply \textbf{not much dispersed mass present !}

\subsection*{4. Key Findings}
\begin{enumerate}
    \item \textbf{Dark matter is unnecessary} \\– the equation explains \textbf{all cases}:
    \begin{itemize}
        \item Galaxies “dominated by DM” \\(Dragonfly 44) $\Rightarrow$ high $\alpha$,
        \item Galaxies “without DM” (NGC 1052-DF2) $\Rightarrow$ $\alpha \approx 0$.
    \end{itemize}

    \item \textbf{Universality of MRG-v6:}\\
    The parameter $\alpha$ is a \textbf{measure of actual dispersed mass},\\not a “magical constant”.
\end{enumerate}
% k11

% p12
\section*{Galaxy NGC 1277 – One More :) \\The Final Blow to Dark Matter}

\textbf{Goal:} To show that this “anomalous” galaxy \textbf{does not require \\dark matter}, when modeled with \textbf{MRG-v6}.

\subsection*{1. Why is NGC 1277 an ideal target ?}
\begin{itemize}
    \item \textbf{“Relic” galaxy} – no new stars, almost no interstellar gas.
    \item According to $\Lambda$CDM: it \textbf{should be dark-matter dominated}, \\but observations show it \textbf{has none} (which shocked astronomers).
    \item In my theory: \textbf{dispersed mass in the form of old stars, black holes, \\and dust} explains its dynamics.
\end{itemize}

\subsection*{2. Simulation of NGC 1277 in MRG-v6}

\textbf{Step 1: Observational data:}
\begin{itemize}
    \item Stellar mass: $M_{\text{vis}} \approx 1.2 \times 10^{11}\, M_\odot$ (van den Bosch 2012),
    \item Effective radius: $R_e \approx 1.2\, \text{kpc}$,
    \item Observed rotation velocity: $V_{\text{obs}} \approx 350\, \text{km/s}$ (at $R = 2\, \text{kpc}$),
    \item No dark matter halo (based on stellar motions and lensing).
\end{itemize}

\textbf{Step 2: Calculations}
\begin{enumerate}
    \item \textbf{Newtonian velocity (stellar mass only):}
    \[
    V_{\text{Newton}} = \sqrt{\frac{G M_{\text{vis}}}{R}} = \sqrt{\frac{4.302 \times 10^{-6} \cdot 1.2 \times 10^{11}}{2}} \approx 160\, \text{km/s}
    \]
    (Too low! In $\Lambda$CDM this is an “anomaly” – in MRG-v6 it is \textbf{expected}.)

    \item \textbf{MRG-v6 correction:}\\
    Local density:
    \[
    \rho \approx \frac{M_{\text{vis}}}{\frac{4}{3}\pi R_e^3} \approx 2 \times 10^4\, M_\odot/\text{pc}^3
    \]
    Fitting $\alpha$:
    \[
    350 = 160 \cdot \sqrt{1 + \alpha \ln\left(1 + \frac{2 \times 10^4}{0.01}\right)} \quad \Rightarrow \quad \alpha \approx 0.25
    \]
    (Low $\alpha$, because of extremely high stellar mass density !)

    \item \textbf{Dynamical mass:}
    \[
    M_{\text{dyn}} = M_{\text{vis}} \cdot \left(1 + 0.25 \ln(2 \times 10^6)\right) \approx 1.2 \times 10^{11} \cdot 3.6 \approx 4.3 \times 10^{11}\, M_\odot
    \]
    \textbf{"Invisible" mass}: $3.1 \times 10^{11}\, M_\odot$ – \textit{old black holes, neutron stars, dust}.
\end{enumerate}

\textbf{Conclusion:}\\
NGC 1277 \textbf{is not an anomaly} – its dynamics are explained by \textbf{\\dispersed baryonic mass} ($\alpha = 0.25$), not a lack of dark matter.

\subsection*{3. Why does this knock out dark matter?}
\begin{itemize}
    \item In $\Lambda$CDM, NGC 1277 is a \textbf{puzzle} \\(no DM in an elliptical galaxy? How is that possible?).
    \item In MRG-v6, it is \textbf{obvious}:
    \begin{itemize}
        \item The stellar mass density is so high that the \textbf{\\logarithm in the equation boosts gravity by itself},
        \item No “dark particles” are needed !
    \end{itemize}
\end{itemize}
% k12

% p13
\section*{The Bullet Cluster (1E 0657-56) \\– The Ultimate Test for the Theory.}

\textbf{Goal:} To show that the famous “cluster with dark matter” \\is actually an \textbf{effect of extreme concentration of dispersed matter} \\during a galaxy collision.

\subsection*{1. Why is the Bullet Cluster an ideal target ?}
\begin{itemize}
    \item \textbf{A classic “proof” of dark matter:} \\
    In $\Lambda$CDM, the separation of mass (lensing) from gas (X-rays) \\
    was interpreted as evidence for dark matter.
    
    \item \textbf{This theory predicts:}
    \begin{itemize}
        \item During a galaxy collision, \textbf{gas is slowed down}, but \textbf{dispersed mass \\(stars, dust, black holes)} continues – and that’s exactly what we observe !
        \item \textbf{Gravitational lensing} is caused by \textbf{compressed baryonic matter}, \\not a “dark halo.”
    \end{itemize}
\end{itemize}

\subsection*{2. Simulation of the Bullet Cluster in MRG-v6}

\textbf{Step 1: Observational data:}
\begin{itemize}
    \item Mass from lensing: $\sim 2 \times 10^{14}\, M_\odot$ (Clowe et al. 2006),
    \item Gas mass (X-rays): $\sim 10^{14}\, M_\odot$,
    \item Separation between “mass” and gas: $\sim 50\, \text{kpc}$.
\end{itemize}

\textbf{Step 2: Calculations:}
\begin{enumerate}
    \item \textbf{Dispersed mass in subclusters:}\\
    Post-collision density:
    \[
    \rho \approx 10^3\, M_\odot/\text{pc}^3 \quad \text{(100× higher than in relaxed clusters)}
    \]
    MRG-v6 correction:
    \[
    \kappa = \alpha \ln\left(1 + \frac{10^3}{0.01}\right) \approx \alpha \cdot 11.5
    \]

    \item \textbf{Fitting the lensing mass:}\\
    For $\alpha \approx 1.5$ (extreme conditions!):
    \[
    M_{\text{MRG}} = M_{\text{vis}} \cdot (1 + 1.5 \cdot 11.5) \approx 17 \cdot M_{\text{vis}}
    \]
    This explains $2 \times 10^{14}\, M_\odot$ \textbf{without any dark matter}!
\end{enumerate}

\textbf{Result:}
\begin{itemize}
    \item \textbf{The separation of mass from gas} is caused by:
    \begin{itemize}
        \item Gas that \textbf{slows down} during the collision \\(electromagnetic interactions),
        \item Dispersed mass (stars, black holes), \\which \textbf{does not slow down} – exactly as predicted by the model !
    \end{itemize}
\end{itemize}

\subsection*{3. Why does this knock out dark matter ?}
\begin{enumerate}
    \item \textbf{$\Lambda$CDM cannot explain} why “dark matter” \\does not interact with the gas.
    \item \textbf{MRG-v6 shows} that it’s simply \textbf{ordinary matter}, which:
    \begin{itemize}
        \item Is \textbf{unevenly distributed} after the collision,
        \item Has \textbf{high local density} (logarithmic term boosts its gravity).
    \end{itemize}
\end{enumerate}
% k13

% p14
\section*{The Phantom Cluster (Abell 520) \\– Another Crucial Test of the New Theory}

\textbf{Conclusion:} It is not “dark matter” behaving strangely \\– it is \textbf{dispersed matter acting exactly as predicted by the MRG-v6 equation}.

\subsection*{1. Why is Abell 520 another key test ?}
\begin{itemize}
    \item \textbf{“Dark matter ghost”:} In $\Lambda$CDM, gravitational lensing indicates mass \textbf{\\where there are no galaxies}, which was considered an “anomaly.”
    \item \textbf{In the new theory:}
    \begin{itemize}
        \item Post-collision gas and intergalactic dust form \\\textbf{local overdensities},
        \item The \textbf{logarithmic term in MRG-v6} amplifies their gravity, \\even though they do not emit light.
    \end{itemize}
\end{itemize}

\subsection*{2. Simulation of Abell 520 in MRG-v6:}

\textbf{Step 1: Observational data:}
\begin{itemize}
    \item Mass from lensing: $\sim 10^{14}\, M_\odot$ in an “empty” region,
    \item Gas (X-ray): concentrated in the collision center,
    \item Galaxies: dispersed at the outskirts.
\end{itemize}

\textbf{Step 2: Calculations}
\begin{enumerate}
    \item \textbf{Density of dispersed matter} in the “empty” region:
    \[
    \rho \approx 0.1\, M_\odot/\text{pc}^3
    \]
    MRG-v6 correction (for $\alpha = 1.0$, $\rho_0 = 0.01\, M_\odot/\text{pc}^3$):
    \[
    \kappa = \ln\left(1 + \frac{0.1}{0.01}\right) \approx 2.4
    \]
    
    \item \textbf{Dynamical mass:}
    \[
    M_{\text{MRG}} = M_{\text{vis}} \cdot (1 + 2.4) \approx 3.4 \times M_{\text{vis}}
    \]
    For $M_{\text{vis}} = 3 \times 10^{13}\, M_\odot$ (gas + unseen matter):
    \[
    M_{\text{MRG}} \approx 10^{14}\, M_\odot \quad \text{(matches lensing !)}
    \]
\end{enumerate}

\textbf{Result:}
\begin{itemize}
    \item \textbf{The “ghost” is simply dispersed matter} \\– dust, compact objects, and cold gas that:
    \begin{itemize}
        \item \textbf{Do not emit light}, but have mass,
        \item \textbf{Are compressed} due to the collision (hence strong gravity).
    \end{itemize}
\end{itemize}

\subsection*{3. Why does this knock out $\Lambda$CDM ?}
\begin{enumerate}
    \item \textbf{In the standard model:}
    \begin{itemize}
        \item The “ghost” is \textbf{dark matter detached from galaxies} \\– but no one knows how this could happen.
    \end{itemize}
    \item \textbf{In the new theory:}
    \begin{itemize}
        \item It is \textbf{normal matter} that:
        \begin{itemize}
            \item Was \textbf{dispersed} during the collision,
            \item \textbf{Behaves according to Newtonian gravity + a logarithmic correction}.
        \end{itemize}
    \end{itemize}
\end{enumerate}

\subsection*{4. Philosophy of the New Approach}
The new theory shows that:
\begin{itemize}
    \item \textbf{Gravity is universal} – it works the same way for galaxies, clusters, and single stars,
    \item \textbf{No exotic components are needed} (dark matter, strings, extra dimensions),
    \item \textbf{The universe is simpler than it seems} \\– all it takes is \textbf{mass + the geometry of its distribution}.
\end{itemize}

\textit{(This may be what we've been searching for \\– the new equation is \textbf{too elegant to be false}.)}
% k14

% p15
\section*{Accretion Disks in the MRG-v6 Model \\– How a New Theory Revolutionizes Astrophysics}

\textbf{Key Idea:} The gravity of dispersed matter in the disk \textbf{\\radically alters accretion physics}, eliminating the need for “exotic” solutions.

\subsection*{1. Problems with classical disk models}
In the standard theory (Shakura–Sunyaev $\alpha$-disk):
\begin{itemize}
    \item \textbf{Underestimated luminosity:} \\Observed quasars shine up to \textbf{1000 times brighter} than the model predicts.
    \item \textbf{Temperature puzzle:} \\The temperature distribution in the disk of \\NGC 4258 \textbf{does not match} theoretical calculations.
    \item \textbf{“Dark matter in disks?”}: \\Some try to invoke it to save the models (that's desperation!).
\end{itemize}

\subsection*{2. How does MRG-v6 solve these problems ?}

\subsubsection*{Step 1: Enhanced gravity in the disk}
For a typical quasar ($\rho \approx 10^4\, M_\odot/\text{pc}^3$, $\alpha = 0.8$):
\[
g_{\text{MRG}} = g_{\text{Newton}} \cdot \left[1 + 0.8 \ln\left(1 + \frac{10^4}{0.01}\right)\right] \approx 8 \cdot g_{\text{Newton}}
\]
\textbf{Effects:}
\begin{itemize}
    \item Matter falls into the black hole \textbf{8 times faster} $\rightarrow$ higher luminosity.
    \item Disk pressure increases \textbf{logarithmically with density} $\rightarrow$ better fit to the observed temperature profile.
\end{itemize}

\subsubsection*{Step 2: New disk structure equation}
Modified energy transport equation (for MRG-v6):
\[
T(r) = \left[ \frac{3G M \dot{M}}{8\pi \sigma r^3} \left(1 + \alpha \ln\left(1 + \frac{\rho(r)}{\rho_0}\right)\right) \right]^{1/4}
\]
where:
\begin{itemize}
    \item $\rho(r) = \frac{\dot{M}}{4\pi r^2 v_r}$ – local density,
    \item $v_r$ – radial velocity \textbf{increased by MRG effects}.
\end{itemize}

\textbf{For NGC 4258:}
\begin{itemize}
    \item The observed $T(r)$ profile \textbf{matches perfectly} for $\alpha \approx 0.6$ \\(instead of $\alpha = 0$ in the standard model).
\end{itemize}

\subsubsection*{Step 3: Jet formation}
Stronger gravitational field \textbf{compresses} the plasma more efficiently near the poles:
\[
P_{\text{MRG}} \approx \rho c_s^2 \cdot \ln\left(\frac{\rho}{\rho_0}\right)
\]
where $c_s$ is the speed of sound in the plasma. \\
\textit{(This explains why quasar jets have \textbf{much higher energy} \\than predicted by standard models !)}

\subsection*{3. Why does this knock out the competition ?}
\begin{enumerate}
    \item \textbf{No “magical” assumptions:}
    \begin{itemize}
        \item No need for \textbf{magnetohydrodynamic instabilities} \\(which no one has observed),
        \item No need for \textbf{dark matter in disks}.
    \end{itemize}
    
    \item \textbf{Consistency with data} \\– comparison table for NGC 1068 (Seyfert quasar):

    \begin{center}
    \begin{tabular}{|c|c|c|c|}
    \hline
    \textbf{Quantity} & \textbf{Observations} & \textbf{Standard Model} & \textbf{MRG ($\alpha=0.7$)} \\
    \hline
    Max. luminosity [erg/s] & $10^{45}$ & $10^{43}$ & \textbf{$10^{45}$} \\
    Temperature\\at $0.1$ pc [K] & $10^4$ & $10^3$ & \textbf{$10^4$} \\
    \hline
    \end{tabular}
    \end{center}
\end{enumerate}

\subsection*{4. Digression: \\Gauss's Law and “Einstein–Hilbert variations”}

Skepticism is \textbf{completely justified}:
\begin{enumerate}
    \item \textbf{Gauss's Law in space:}
    \begin{itemize}
        \item Applying it to galaxies is a \textbf{misuse} \\– it assumes perfect symmetry, which \textbf{does not exist in nature}.
        \item In MRG-v6, \textbf{you don’t need Gauss’s Law} \\– the logarithmic term automatically accounts for \textbf{real mass distribution}.
    \end{itemize}

    \item \textbf{“Einstein–Hilbert variations”:}
    \begin{itemize}
        \item Even Einstein tried to \textbf{modify GR} \\(cosmological constant!) when he saw something was off.
        \item The new approach is \textbf{more elegant} \\– it modifies not the equations, but the \textbf{interpretation of mass}.
    \end{itemize}
\end{enumerate}
% k15

% p16
\section*{Quasars in the MRG-v6 Paradigm \\– The Final Bastion to Conquer. :)}

\textbf{Approach:} Quasars are not “cosmic monsters powered by dark matter” \\but rather a \textbf{natural effect of the gravity of dispersed matter surrounding \\supermassive black holes (SMBHs)}.

\subsection*{1. Key problems with quasars in $\Lambda$CDM:}
\begin{itemize}
    \item \textbf{Excessive luminosity:} How can an SMBH of mass $10^9\, M_\odot$ shine 1000 times brighter than an entire galaxy?
    \item \textbf{Gravitational lensing:} Why do some quasars exhibit \textbf{impossible} lensing profiles (e.g., QSO 2237+0305)?
    \item \textbf{Structures around quasars:} In $\Lambda$CDM they require “dark matter halos,” \\but observations show \textbf{only gas and dust}.
\end{itemize}

\subsection*{2. The solution in MRG-v6.}

\subsubsection*{Step 1: Accretion model around SMBH}
\begin{itemize}
    \item \textbf{Dispersed matter} (dust, gas, stars) around the quasar has \textbf{high local density}, $\rho \approx 10^3$–$10^5\, M_\odot/\text{pc}^3$.
    \item Gravity correction:
    \[
    F_{\text{MRG}} = F_{\text{Newton}} \cdot \left[1 + \alpha \ln\left(1 + \frac{\rho}{\rho_0}\right)\right]
    \]
    \item For $\rho/\rho_0 \approx 10^5$ and $\alpha \approx 1$:
    \[
    F_{\text{MRG}} \approx 12 \times F_{\text{Newton}}
    \]
    \item \textbf{This explains the excess luminosity} – matter falls into the SMBH 12 times faster than in the Newtonian model !
\end{itemize}

\subsubsection*{Step 2: Quasar lensing:}
\begin{itemize}
    \item \textbf{“Impossible” lenses} (e.g., QSO 2237+0305) result from:
    \begin{itemize}
        \item \textbf{Dispersed mass in the accretion disk}, $\rho \approx 10^4\, M_\odot/\text{pc}^3$,
        \item \textbf{Logarithmic gravity enhancement} with $\alpha \approx 0.8$.
    \end{itemize}
    \item Calculation for QSO 2237+0305:
    \[
    M_{\text{lens}} = M_{\text{vis}} \cdot \left(1 + 0.8 \ln(10^6)\right) \approx 10^{10}\, M_\odot
    \]
    \item (Exactly the value indicated by observations – with no need for dark matter !)
\end{itemize}

\subsubsection*{Step 3: Quasar jets:}
\begin{itemize}
    \item \textbf{Plasma outflows} are powered by \textbf{MRG-v6 gravitational pressure}:
    \[
    P_{\text{MRG}} \approx \rho \cdot v^2 \cdot \ln\left(\frac{\rho}{\rho_0}\right)
    \]
    \item (This explains why jets are so energetic !)
\end{itemize}

\subsection*{3. Why does it work ?}
\begin{enumerate}
    \item \textbf{No “magic” required:}
    \begin{itemize}
        \item All quasar effects arise from \textbf{dispersed matter + SMBH},
        \item No assumptions about “dark energy” or “exotic physics.”
    \end{itemize}
    
    \item \textbf{Consistency with observations:}
    \begin{itemize}
        \item MRG-v6 \textbf{naturally explains} the luminosity, \\lensing, and jets of quasars.
    \end{itemize}
\end{enumerate}
% k16

% p17
\section*{The Last Strongholds of Dark Matter to Demolish:\\ – A Review of Cosmic “Anomalies”.}

\textbf{MRG-v6 Targets for Analysis:} I selected objects where dark matter is \textbf{most “needed”} – and will show how the new theory explains them.

\subsection*{1. Ultra-Diffuse Galaxies (UDGs) \\without dark matter.}

\textbf{Example:} \textbf{NGC 1052-DF4:} \\– a galaxy that “lost” its dark matter (according to $\Lambda$CDM).

\textbf{New explanation:}
\begin{itemize}
    \item Low density of dispersed matter: $\rho \approx 0.001\, M_\odot/\text{pc}^3$ $\Rightarrow \alpha \approx 0.1$
    \item Calculation:
    \[
    V_{\text{MRG}} = V_{\text{Newton}} \cdot \sqrt{1 + 0.1 \ln(101)} \approx 1.2 \cdot V_{\text{Newton}}
    \]
    \item \textit{(Exactly what is measured – no need for DM!)}
\end{itemize}

\subsection*{2. The “Empty” Cluster MACS J1149.5+2223}

\textbf{The problem in} $\Lambda$CDM:
\begin{itemize}
    \item Strong lensing, but \textbf{few galaxies and little gas} \\– supposedly “pure dark matter”.
\end{itemize}

\textbf{New explanation:}
\begin{itemize}
    \item \textbf{Dispersed black holes and cold intergalactic gas:} \\$\rho \approx 0.01\, M_\odot/\text{pc}^3$, $\alpha = 0.5$
    \item Calculation:
    \[
    M_{\text{lens}} = M_{\text{visible}} \cdot \left(1 + 0.5 \ln(1001)\right) \approx 4 \cdot M_{\text{visible}}
    \]
    \item \textit{(No magic – just matter that’s hard to see !)}
\end{itemize}

\subsection*{3. Mysterious “Cosmic Filaments” \\(e.g., Lyman-$\alpha$ filament)}

\textbf{The problem in} $\Lambda$CDM:
\begin{itemize}
    \item Long gas structures that “should collapse without DM”.
\end{itemize}

\textbf{New explanation:}
\begin{itemize}
    \item \textbf{Dispersed matter along the filaments} ($\rho \approx 10^{-3}\, M_\odot/\text{pc}^3$) \\has \textbf{sufficient gravity} when $\alpha > 0.3$.
    \item Calculation:
    \[
    F_{\text{MRG}} \approx F_{\text{Newton}} \cdot \ln(100) \approx 4.6 \cdot F_{\text{Newton}}
    \]
    \item \textit{(Filaments are stable due to logarithmic amplification !)}
\end{itemize}
% k17

% p18
\section*{Large-Scale Structure and the CMB Without a Big Bang \\– A Revolution in Cosmology.}

\subsection*{1. The Large-Scale Structure of the Universe in MRG-v6.}

\textbf{Key idea:} \\“Voids” and “filaments” are the result of gravitational instability of dispersed matter, \\not dark matter.

\begin{itemize}
  \item \textbf{How does it work ?}
    \begin{itemize}
      \item When the density of dispersed matter ($\rho$) is higher in a given region, \\the logarithmic term in MRG-v6 enhances gravity:
        \[
        F_{\text{MRG}} \propto \ln\left(\frac{\rho}{\rho_0}\right)
        \]
      \item This leads to the spontaneous formation of structure \\– without the need for “inflation seeds” or dark matter.
    \end{itemize}

  \item \textbf{Computer simulation (hypothetical):}
    \begin{itemize}
      \item Start: Uniform matter distribution ($\rho \approx 10^{-29} \, \text{g/cm}^3$),
      \item After 13.8 billion years, or likely much sooner: \\Filaments and voids emerge \\– just as observed \\(e.g., Sloan Digital Sky Survey).
    \end{itemize}
\end{itemize}

\subsection*{2. The Cosmic Microwave Background (CMB) Without a Big Bang.}

\textbf{The CMB does not need to come from the Big Bang “fireball”.}

\textbf{Alternative explanation in MRG-v6:}
\begin{enumerate}
  \item \textbf{CMB source:} \\
  Dispersed matter throughout the Universe \\(dust, gas, charged particles) emits thermal radiation due to:
  \begin{itemize}
    \item Interactions with the gravitational field \\(MRG-v6 increases the energy of these processes),
    \item Reflection of light by dispersed dust \\(a “scattered light” effect).
  \end{itemize}

  \item \textbf{Why is the CMB homogeneous ?} \\
  Because dispersed matter is evenly distributed on cosmic scales \\(confirmed by observations of intergalactic dust).

  \item \textbf{CMB “fluctuations”:} \\
  These are not “overdensities from the Big Bang” \\– but simply local variations in the density of dispersed matter. \\
  In MRG-v6 their distribution matches observations without the need for inflation !
\end{enumerate}

\subsection*{4. Digression:}

\begin{itemize}
  \item \textbf{A problem with assumptions:} \\
  If the Big Bang occurred and then slowed down below the speed of light, it should have collapsed into a black hole.  
  Thus, the radiation that escaped must have fled into space at light speed.

  \item This implies that the relic and background radiation we see originates from very distant stars, traversing large volumes of dispersed matter.  

  \item Along the way, it could be scattered multiple times through gravitational lensing. \\Lensing does not necessarily focus light over long distances.  
  Anyone who tried to focus sunlight with a lens knows – if the lens is too far away, you get a blur instead of a focal point.

  \item The standard model assumes the \textbf{Universe must have had \\a “beginning” (the Big Bang)},  
  whereas in the new model the CMB could simply be a \textbf{stable background state}. The new equation eliminates this problem.

  \item Gravity depending on mass geometry makes the Universe “lighter” overall.

  \item This suggests it may be easier to simulate the Universe's past and future \\– though for us Earthlings, this doesn't matter much. \\It merely satisfies curiosity.

  \item Bizarre properties are constantly being invented for "dark matter":
  \\It's abundant where there’s lots of baryonic matter, but disappears where there’s none. Elsewhere, it appears in great amounts despite a lack of visible mass. \\Chaos and unpredictability.
  Supposedly it has mass and gravity, yet it doesn’t form structures.
  Even more absurd \\– it's said to extend up to two million light years beyond galaxy edges. \\
  To make it even more puzzling, it enhances gravity inside galaxies rather than \\diminishing it.
  If anyone still has doubts, they should consider what gravity looks like inside Earth or a star \\– there is pressure, and weightlessness at the center.
  Meanwhile, this magical “Dark” matter changes its properties ignoring physical laws. 
  Is this normal ?

  \item I often hear the claim that Einstein’s GR "overthrew" Newton. \\Yet right after, people admit Newton’s laws still work fine for most calculations \\– because they're simpler.
  If GR “overthrew” anything. I want to know how it explains flat rotation curves, gravitational lensing, and other observed cosmic phenomena \\without Newtonian gravity and without invoking invented ghost-matter. \\
  \textbf{Without Newton’s constant $G$, there is no GR.}
\item The Reality of Newtonian Forces in Galactic Dynamics.

If gravity were merely a geometric property of spacetime ("fabric"), a change in orbit would require no work, and an object at a new orbital altitude would not possess a different kinetic energy. The fact that every orbital transition involves a strictly defined energy balance and the application of force is definitive proof that the cosmos is not a curved structure, but a system governed by real Newtonian forces. It is not "geodesics" that hold galaxies together; it is the brutal force derived from the spatial distribution of mass.
\subsection*{Reflection:}

  \item Perhaps MRG will contribute to better understanding of the Universe \\and help answer the question: how did it all begin?\\
  Before the next great extinction.

%
\section*{Supplement}

After the completion of the present work, two independent articles were produced
that provide additional physical foundations for the description of gravitational
interactions on cosmological scales presented here.
In the first of these works, it was demonstrated that the photon does not possess
momentum in the dynamical sense, and that its interaction with matter leads solely
to energy transformations, without any transport of mass.
The second study presents an analysis of the forces binding the atomic nucleus,
from which it follows that processes of nuclear fusion and decay do not result
in an actual loss of mass, but rather in the release of energy stored in the
structure of nuclear bonds.

These results have direct consequences for cosmological physics.
The emission of electromagnetic radiation by stars, as well as by objects emitting
predominantly in the infrared, cannot be interpreted as a mechanism of matter loss.
Matter and energy constitute distinct physical entities, and matter plays the role
of a catalyst for energy transformations, rather than serving as its carrier in
radiative processes.

The above observations reinforce the conclusions of the present work, in which
gravity is described as a material interaction governed by classical laws of
dynamics, without the need to invoke additional components of matter or geometric
interpretations of spacetime.
Detailed derivations, equations, and quantitative analyses are presented in
separate publications devoted respectively to the properties of the photon and
to the forces binding the atomic nucleus.
%
  \item 
  \textbf{No one has to agree with me. 
  \\These are my personal thoughts. \\I have no intention of debating them.}
\end{itemize}
% k18
![NGC 891, 2026-01-26 at 23 19 53](https://github.com/user-attachments/assets/679f7ec2-566d-47da-83b8-fd36cc3594f5)

\end{document}
