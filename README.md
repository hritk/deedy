# deedy

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Deedy - One Page Two Column Resume
% LaTeX Template
% Version 1.2 (16/9/2014)
%
% Original author:
% Debarghya Das (http://debarghyadas.com)
%
% Original repository:
% https://github.com/deedydas/Deedy-Resume
%
% IMPORTANT: THIS TEMPLATE NEEDS TO BE COMPILED WITH XeLaTeX
%
% This template uses several fonts not included with Windows/Linux by
% default. If you get compilation errors saying a font is missing, find the line
% on which the font is used and either change it to a font included with your
% operating system or comment the line out to use the default font.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% 
% TODO:
% 1. Integrate biber/bibtex for article citation under publications.
% 2. Figure out a smoother way for the document to flow onto the next page.
% 3. Add styling information for a "Projects/Hacks" section.
% 4. Add location/address information
% 5. Merge OpenFont and MacFonts as a single sty with options.
% 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% CHANGELOG:
% v1.1:
% 1. Fixed several compilation bugs with \renewcommand
% 2. Got Open-source fonts (Windows/Linux support)
% 3. Added Last Updated
% 4. Move Title styling into .sty
% 5. Commented .sty file.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
% Known Issues:
% 1. Overflows onto second page if any column's contents are more than the
% vertical limit
% 2. Hacky space on the first bullet point on the second column.
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


\documentclass[]{deedy-resume-openfont}
\usepackage{fancyhdr}
 
\pagestyle{fancy}
\fancyhf{}
 
\begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     LAST UPDATED DATE

% %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%\lastupdated

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     TITLE NAME
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\namesection{Hritik}{Raj}{ \urlstyle{same}\href{http://github.com/hritk}{Kolkata}| \href{http://}{India}\\
\href{mailto:ritikrj1@gmail.com}{ritikrj1@gmail.com} | (91) 7303554662 | \href{http://github.com/hritk}{@hritik-raj}
}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN ONE
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\begin{minipage}[t]{0.33\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EDUCATION
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Education} 

\subsection{IEM Kolkata}
\descript{B.tech in Electrical Engg}
\location{2019-23 | Kolkata, IN}
 GPA: 8.6 / 10}
\sectionsep

\subsection{Delhi Public School}
\descript{ Computer Science}
\location{2018 | Ranchi, IN}

\sectionsep

\subsection{RK Mission}
\location{2016| Hazaribag, India}
\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     LINKS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Links} 
% Facebook:// \href{https://facebook/dd}{\bf dd} \\
Github:// \href{https://github.com/hritk}{\bf hritikraj1} \\
LinkedIn://  \href{https://www.linkedin.com/in/hritik-raj-506624117/}{\bf hritikraj22} \\
% YouTube://  \href{https://www.youtube.com/user/DeedyDash007}{\bf DeedyDash007} \\
% Twitter://  \href{https://twitter.com/debarghya_das}{\bf @debarghya\_das} \\
Behance://  \href{https://www.behance.net/hritikraj1}{\bf Hritik-Raj}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     COURSEWORK
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

% \section{Coursework}
% % \subsection{Graduate}
% % Advanced Machine Learning \\
% % Open Source Software Engineering \\
% % Advanced Interactive Graphics \\
% % Compilers + Practicum \\
% % Cloud Computing \\
% % Evolutionary Computation \\
% % Defending Computer Networks \\
% % Machine Learning \\
% \sectionsep

% \subsection{Undergraduate}
% Data Structures and Algorithm \\
% Operating Systems \\
% Artificial Intelligence + Practicum \\
% Functional Programming \\
% Computer Graphics + Practicum \\
% {\footnotesize \textit{\textbf{(Research Asst. \& Teaching Asst 2x) }}} \\
% Unix Tools and Scripting \\

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     SKILLS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Skills}
\subsection{Programming}
% \location{Over 5000 lines:}
C\textbullet{}   C++ \textbullet{} Python \textbullet{} Javascript \\
ES6\textbullet{} React \ \\ 
\location{Tools:}
Figma\textbullet{} HTML \textbullet{} CSS \textbullet{} Figma \textbullet{} Git \\
\location{Core:}
OS \textbullet{} DBMS\textbullet{} OOPS \textbullet{} 
\sectionsep
\section{Interests} 
Gaming \textbullet{} Travel\textbullet{} Books\textbullet{} Music\textbullet{} 
\sectionsep

\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%
%     COLUMN TWO
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\end{minipage} 
\hfill
\begin{minipage}[t]{0.66\textwidth} 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     EXPERIENCE
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Experience}
\runsubsection{Quadeveloper}
\descript{| Web Developer Intern }

\location{ 2022| Noida, IN}
\item React was main stream library along with next js implementation,jira and git extensively used
\sectionsep

\runsubsection{Pluto Tours}
\descript{|UI/UX Intern }
\location{ 2021| remote}
\item Figma used as tool, prototyping , architecture design
\sectionsep

% \runsubsection{Coursera}
% \descript{| KPCB Fellow + Software Engineering Intern }
% \location{June 2014 – Sep 2014 | Mountain View, CA}
% \vspace{\topsep} % Hacky fix for awkward extra vertical space
% \begin{tightemize}
% \item 52 out of 2500 applicants chosen to be a KPCB Fellow 2014.
% \item Led and shipped Yoda - the admin interface for the new Phoenix platform. 
% \item Full-stack developer - Wrote and reviewed code for JS using Backbone, Jade, Stylus and Require and Scala using Play
% \end{tightemize}
% \sectionsep

% \runsubsection{Google}
% \descript{| Software Engineering Intern }
% \location{May 2013 – Aug 2013 | Mountain View, CA}
% \begin{tightemize}
% \item Worked on the YouTube Captions team, in Javascript and Python to plan, to design and develop the full stack to add and edit Automatic Speech Recognition captions. In production.
% \item Created a backbone.js-like framework for the Captions editor.
% \end{tightemize}
% \sectionsep

% \runsubsection{Phabricator}
% \descript{| Open Source Contributor \& Team Leader}
% \location{Jan 2013 – May 2013 | Palo Alto, CA \& Ithaca, NY}
% \begin{tightemize}
% \item Phabricator is used daily by Facebook, Dropbox, Quora, Asana and more.
% \item I created the Meme generator and more in PHP and Shell.
% \item Led a team from MIT, Cornell, IC London and UHelsinki for the project.
% \end{tightemize}
% \sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     RESEARCH
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\section{Projects}
\runsubsection{BURGER BUILDER APP}
\descript{| React/Redux}
\location{2022 }
Website is suited to the purpose of state management using react js and redux. using this app we can generate our custom burger and generate bills stored in firebase. Deployed on netlify  \textbf{\href{https://burger-builder-by-hr.netlify.app/}{Burger-Builder}} , 
\sectionsep

\runsubsection{MEMORY MANAGEMENT SYSTEM}
\descript{| C++}
\location{2022 }
This is C++ based memory alllocation system based on Fit search, Next search , Best search and Worst search to implement the core operating system concepts. Deployed on repl.it 
\sectionsep

\runsubsection{TODO APP}
\descript{| JavaScript}
\location{2021 }
This is based using material ui and javascript to make a web app which keeps track of work to do and you can keep track of the list.Deployed on netlify \textbf{\href{https://todo-listzz.netlify.app//}{TodoList Webapp}} , 
\sectionsep

 
\runsubsection{TWO IN ONE DRONE}
\descript{|Micro Controllers}
\location{2019 }
A micro controller based drone with a range of over 150m with gps tracking this drone could land and stream in water . Made using Ardupilot micro controller and mission planner firmware , 



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     AWARDS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%



\sectionsep

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     PUBLICATIONS
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%



 


\section{Miscellaneous}
\textbullet{} Member of Iem coding club \location{2022 }\\
\textbullet{} Member of Toastmasters International club
\location{2020 }
\textbullet{} Top 5 In IEM debate Competetion
\location{2020 }
\textbullet{} Top 20 in codechef Mathematics Olympiad
\location{2019 }
\textbullet{} Top 1oo International Mathematics Olympiad
\location{2014 }
\renewcommand\refname{\vskip -1.5em} % Couldn't get this working from the .cls file

\bibliography{publications}
\nocite{*}

\end{minipage} 
\end{document}  \documentclass[]{article}
