
For our code in Matlab, please see the corresponding m-files. 

###Question 1

Consider the model below:

\begin{equation}
\label{A}
log(wage) = \beta_0 + \beta_1 age + \beta_2 black + \beta_3 education
\end{equation}

Where $log(wage)$ is the natural logarithm of wage in US Dollars of 2200 young workers in the United States. $age$ is the age of the respondents in years.\footnote{We also explored the possibility of introducing $age^2$ in our model. However a scatter plot indicated that the relation between $age$ and $log(wage)$ can be properly approached with a linear function. Putting $age^2$ in the model did not improve the model and its coefficient was not significant. We therefore decided to exclude $age^2$ from our model.} $Black$ is a dummy variable, indicating whether an individual has an Afro-American ethnicity. Finally, $education$ gives the years of education of the respondent. 

The OLS estimation yielded the results in table 1 below.

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
