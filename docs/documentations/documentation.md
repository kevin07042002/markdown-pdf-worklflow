---
title: Testpage
author:
- Firstname Lastname
titlepage: true
geometry:
- top=30mm
- left=25mm
- right=25mm
- bottom=30mm
header-includes:
#- \usepackage[english,ngerman]{babel}
- \usepackage{setspace}
- \onehalfspacing
- \usepackage{helvet}
- \renewcommand{\familydefault}{\sfdefault}
- \usepackage{lineno}
- \usepackage[hang]{footmisc}
- \usepackage{graphicx}
- \usepackage{hyperref}
- \usepackage{fancyhdr}
- \usepackage{xcolor}
- \pagestyle{fancy}
- \setlength\headheight{26pt}
- \rhead{\includegraphics[width=1cm]{./images/logo-markdown.png}}
- \lfoot{Firstname Lastname}
---
\maketitle
\begin{figure}[h]
\centering
\includegraphics[scale=0.5]{"./images/logo-markdown.png"}
\end{figure}
\pagebreak

\tableofcontents
\pagebreak

# First side

## Test


# Second side

