
%----------------------------------------------------------------------------------------
%       PACKAGES AND OTHER DOCUMENT CONFIGURATIONS
%----------------------------------------------------------------------------------------
\documentclass[paper=letter, fontsize=12pt]{article}
\usepackage[english]{babel} % English language/hyphenation
\usepackage{amsmath,amsfonts,amsthm} % Math packages
\usepackage[utf8]{inputenc}
\usepackage{float}
\usepackage{lipsum} % Package to generate dummy text throughout this template
\usepackage{blindtext}
\usepackage{graphicx} 
\usepackage{caption}
\usepackage{enumerate}
\usepackage{subcaption}
\usepackage[sc]{mathpazo} % Use the Palatino font
\usepackage[T1]{fontenc} % Use 8-bit encoding that has 256 glyphs
\linespread{1.05} % Line spacing - Palatino needs more space between lines
\usepackage{microtype} % Slightly tweak font spacing for aesthetics
\usepackage[hmarginratio=1:1,top=32mm,columnsep=20pt]{geometry} % Document margins
\usepackage{multicol} % Used for the two-column layout of the document
%\usepackage[hang, small,labelfont=bf,up,textfont=it,up]{caption} % Custom captions under/above floats in tables or figures
\usepackage{booktabs} % Horizontal rules in tables
\usepackage{float} % Required for tables and figures in the multi-column environment - they need to be placed in specific locations with the [H] (e.g. \begin{table}[H])
\usepackage[hidelinks]{hyperref} % For hyperlinks in the PDF
\usepackage{lettrine} % The lettrine is the first enlarged letter at the beginning of the text
\usepackage{paralist} % Used for the compactitem environment which makes bullet points with less space between them
\usepackage{abstract} % Allows abstract customization
\renewcommand{\abstractnamefont}{\normalfont\bfseries} % Set the "Abstract" text to bold
\renewcommand{\abstracttextfont}{\normalfont\small\itshape} % Set the abstract itself to small italic text
\usepackage{titlesec} % Allows customization of titles
\usepackage{color}

\setlength{\parindent}{0pt}
\setlength{\parskip}{1ex plus 0.5ex minus 0.2ex}
\renewcommand\thesection{\Roman{section}} % Roman numerals for the sections
\renewcommand\thesubsection{\Roman{subsection}} % Roman numerals for subsections

\titleformat{\section}[block]{\large\scshape\centering}{\thesection.}{1em}{} % Change the look of the section titles
\titleformat{\subsection}[block]{\large}{\thesubsection.}{1em}{} % Change the look of the section titles
\newcommand{\horrule}[1]{\rule{\linewidth}{#1}} % Create horizontal rule command with 1 argument of height
\usepackage{fancyhdr} % Headers and footers
\pagestyle{fancy} % All pages have headers and footers
\fancyhead{} % Blank out the default header
\fancyfoot{} % Blank out the default footer

\fancyhead[C]{Tilburg University $\bullet$ 27 November 2015 $\bullet$ Minke Remmerswaal and Chao Zhang} % Custom header text

\fancyfoot[RO,LE]{\thepage} % Custom footer text
%----------------------------------------------------------------------------------------
%       TITLE SECTION
%----------------------------------------------------------------------------------------
\title{\vspace{-15mm}\fontsize{24pt}{10pt}\selectfont\textbf{Second Assignment for Econometrics 1. Empirical exercises.\footnote{This is only the empirical part of this problem set. The theoretical part is a separate document.}}} % Article title
\author{
\large
{\textsc{Minke Remmerswaal, ANR 111200 \footnote{Email address: M.Remmerswaal@cpb.nl} }}\\[2mm]
{\textsc{Chao Zhang, ANR 859658 \footnote{Email address: c.zhang@syr.edu} }}\\[2mm]
}
\date{}

%----------------------------------------------------------------------------------------
\begin{document}
\maketitle % Insert title
\thispagestyle{fancy} % All pages have headers and footers


For our code in Matlab, please see the corresponding m-files. 

\subsection*{Question 1}

Consider the model below:

\begin{equation}
\label{A}
log(wage) = \beta_0 + \beta_1 age + \beta_2 black + \beta_3 education
\end{equation}

Where $log(wage)$ is the natural logarithm of wage in US Dollars of 2200 young workers in the United States. $age$ is the age of the respondents in years.\footnote{We also explored the possibility of introducing $age^2$ in our model. However a scatter plot indicated that the relation between $age$ and $log(wage)$ can be properly approached with a linear function. Putting $age^2$ in the model did not improve the model and its coefficient was not significant. We therefore decided to exclude $age^2$ from our model.} $Black$ is a dummy variable, indicating whether an individual has an Afro-American ethnicity. Finally, $education$ gives the years of education of the respondent. 

The OLS estimation yielded the results in table \ref{1} below.\footnote{The P-values of the estimated coefficients are given between brackets.} 

\begin{table}[h]
\centering
\caption{OLS estimations of model \ref{A}}
\label{1}
\begin{tabular}{lll}
					& $\hat{\beta}_{OLS}$ \\
constant  			&   4.5725 (0.000)    \\
age 					&   0,0436 (0.000)   \\
black      			& -0,2127 (0.000)   \\
education    		&   0,0388 (0.000)    \\
\end{tabular}
\end{table}

The OLS estimation indicates a positive effect of $education$ on $log(wage)$. An extra year of education increases wage of the respondents by approximately 3.9 percent, ceteris paribus.

All coefficients are highly significant, with a P-value of 0. Together, the regressors explain roughly twenty percent of the variation in $log(wage)$.

$Education$ is potentially endogenous and causing the OLS results above to be incorrect. There are  unobserved factors that may affect $log(wage)$ as well as $education$. Ability of the respondent may for example influence both the years of education as well as the wage. 

\newpage

\subsection*{Question 2}

We will re-estimate the model in equation \ref{A}, but with an IV estimator to control for potential endogeneity in $education$. We estimate the model in two stages. First we regress $education$ on our instrument, $father~education$, and next we regress $log(wage)$ on $education$ predicted in the first stage.   

\begin{equation}
\label{B}
education = \alpha_0 + \alpha_1 age + \alpha_2 black + \alpha_3 father~education
\end{equation}

\begin{equation}
\label{C}
log(wage) = \beta_0 + \beta_1 age + \beta_2 black + \beta_3 (\hat{\alpha}_0 + \hat{\alpha}_1 age + \hat{\alpha}_2 black + \hat{\alpha}_3 father~education)
\end{equation}

\begin{table}[h]
\centering
\caption{OLS and IV estimations with one instrument}
\label{2}
\begin{tabular}{llll}
					& $\hat{\beta}_{OLS}$ 	& $\hat{\beta}_{IV}$ \\
constant  			&   4.5725 (0.000) 		& 4.3332 (0.000) \\
age 					&   0.0436 (0.000)  		& 0.0431 (0.000) \\
black      			& -0.2127 (0.000) 		& -0.1876 (0.000)\\
education     		&   0.0388 (0.000)  		&  0.0571 (0.000)\\
\end{tabular}
\end{table}


According to the IV estimation, if education increases with one year, then wage will increase with 5.7 percent, ceteris paribus. This relationship is highly significant. 

Compared to the OLS estimations in Question 1, the IV effects are similar but slightly smaller. The effect of $education$ on $log(wage)$ however has become larger.  


\newpage

\subsection*{Question 3}

There are two conditions for a consistent IV estimator:

\begin{enumerate}
\item $education$ (our endogenous regressor) and $father~education$ (our instrument) must be correlated: \\
 cov($education$, $father~education$) $\neq$ 0
\item The instrument, $father~education$ must be independent of $u$: \\ 
cov($father~education$, $u$) = 0 
\end{enumerate}

The first condition will likely hold: children of parents who are highly education often are more highly educated themselves. Intuitively, people who are highly educated emphasize more on their children's education. Say, they invest more in children's education and high requirement on children's academic performance. These contributes to longer education.Our data confirms this: we find a strong and significant positive correlation with both the father's as well as the mother's year education. 

To test the first assumption more formally, we conduct a test. We estimate an OLS on model \ref{D}:

\begin{equation}
\label{D}
education = \beta_0 + \beta_1 father~education
\end{equation}

This results in the coefficients in Table \ref{3}:

\begin{table}[h]
\centering
\caption{OLS estimations of model \ref{D}}
\label{3}
\begin{tabular}{lll}
					& $\hat{\beta}_{OLS}$ \\
constant 			&   10.3184 (0.000)    \\
father education 	& 0.3283 (0.000)
\end{tabular}
\end{table}

We find a positive and highly significant effect of a father's education on years of education of the respondent. The first condition for IV is therefore satisfied. 

The second condition cannot be tested formally. If we would consider more than one instrument, a test would be possible. However, using the test of merely one instrument will always give a coefficient of zero. A correlation between the father's years of education and $log(wage)$ is also not sufficient, because it can indirectly (via the respondents' education) affect $log(wage)$, and thus give a correlation. 

We must use economic intuition and theory to argue that the second assumption is valid. It is likely that a respondent's father's years of education does not have a direct effect on the wage of the respondent. Based on common sense, $log(wage)$ would not affect $father~education$ because there is no direct reason we could think that it would. 
    

\newpage

\subsection* {Question 4}

At a first glance when comparing the results of the IV and OLS estimations in Table \ref{2}, they are slightly different but still very similar. The standard errors of the OLS estimation are slightly smaller (again except for $education$), so if education appears not to be endogenous, we would prefer using the OLS estimator as it is more efficient (see table \ref{5}): 

\begin{table}[h]
\centering
\caption{The coefficients and standard errors of the OLS and IV estimations with one instrument}
\label{5}
\begin{tabular}{lllll}
				& $\hat{\beta}_{OLS}$ 	& $SE_{OLS}$ 	& $\hat{\beta}_{IV}$ 	& $SE_{IV}$ \\
constant  		&   4.5725 (0.000) 		& 0.0877 		& 4.3332 (0.000) 		& 0.1243 \\
age 				&   0.0436 (0.000)  		& 0.0027 		& 0.0431 (0.000) 		& 0.0027 \\
black       		& -0.2127 (0.000) 		& 0.0233 		& -0.1876 (0.000) 		& 0.0251 \\
education    	&   0.0388 (0.000) 		& 0.033 			&  0.0571 (0.000) 		& 0.0075 \\
\end{tabular}
\end{table}

We shall test the following null hypothesis:

\begin{itemize}
\item[$H_0: E(X'u) = 0$ (OLS is fine)]
\item[$H_1: E(X'u) \neq 0$ (we should do IV)]
\end{itemize}


The null hypothesis can be tested via two ways: 

\subsubsection*{Test one}
According to Davidson and Mackinnon (1999), we can use auxiliary regression \ref{H} to test the null hypothesis.

\begin{equation}
\label{H}
y = X\beta + P_wY\delta + u
\end{equation}

where $y$ is $log(wage)$, $X$ are the regressors in the model (in this case $age$, $black$ and $education$. $P_w$ is the projection matrix of $W$, a matrix with the instruments. $father~education$ is part of $W$. $Y$ are those regressors in $X$ that are potentially endogenous (in this case $education$). 

We conducted an OLS regression for equation \ref{H}. If $\delta = 0 $ then the null hypothesis is not rejected and we should choose OLS over IV. However, we find an significant coefficient of 0.0059. We must reject the null hypothesis and choose the IV estimator. 

\subsubsection*{Test two}
We use a Durbin-Wu-Hausman test to see if the OLS and IV estimates are statistically different. 

\begin{equation}
\label{G}
Durbin-Wu-Hausman~test~statistic = (\hat{\beta}_{IV} - \hat{\beta}_{OLS}) (\hat{var}(\hat{\beta}_{IV}) - \hat{var}(\hat{\beta}_{OLS}))^{-1} (\hat{\beta}_{IV} - \hat{\beta}_{OLS})
\end{equation}

Our test statistic is significant with a P-value of 0.0094. The null hypothesis must be rejected: the OLS estimates are statistically different from the IV-estimates. IV-estimation is therefore preferred. 


\newpage

\subsection*{Question 5}

We repeat Question 2 but use an additional instrument: $mother~education$. This results in the model below:

\begin{equation}
\label{E}
education = \alpha_0 + \alpha_1 age + \alpha_2 black + \alpha_3 father~education + \alpha_4 mother~education
\end{equation}

\begin{equation}
\label{F}
log(wage) = \beta_0 + \beta_1 age + \beta_2 black + \beta_3 (\hat{\alpha}_0 + \hat{\alpha}_1 age + \hat{\alpha}_2 black + \hat{\alpha}_3 father~education + \hat{\alpha}_4 mother~education)
\end{equation}

This gives the results in table \ref{4}.

\begin{table}[h]
\centering
\caption{OLS and IV estimations with one and two instruments}
\label{4}
\begin{tabular}{lllll}
& $\hat{\beta}_{OLS}$ & $\hat{\beta}_{IV_{one~instrument}}$ & $\hat{\beta}_{IV_{two~instruments}}$  \\
constant  &   4.5725 (0.000) & 4.3332 (0.000) & 4.2935 (0.000) \\
age &   0.0436 (0.000)  & 0.0431 (0.000) & 0.0430 (0.000) \\
black       & -0.2127 (0.000) & -0.1876 (0.025) & -0.1835 (0.1716) \\
educ     &   0.0388 (0.000)  &  0.0571 (0.195) & 0.0602 (0.000) \\
\end{tabular}
\end{table}

The estimates of the two IV estimations are very similar. Using two instruments is a bit more
efficient as the standard errors are slightly smaller. 

%----------------------------------------------------------------------------------------
\end{document}

The differences 
