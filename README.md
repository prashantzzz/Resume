# Resume - 90 ATS
![image](https://github.com/user-attachments/assets/8bc00bac-b7a8-45d6-9274-c5d9a432a609)

## Paste it in overleaf's new project to see the editable resume

%-------------------------
% Resume in Latex
% Author : Prashant
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}

\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}


\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}



%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
      
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}


\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------


\begin{center}
    {\Huge \scshape Prashant} \\ \vspace{1pt}
    Software Developer \\ \vspace{1pt}
    \small \href{mailto:prashant.2021@vitstudent.ac.in}\small 
    \href{https://prashantzz.vercel.app/}{\raisebox{-0.2\height}\faShareSquare\ \underline{Portfolio}} ~
    \href{tel:#}{ \raisebox{-0.1\height}\faPhone\ \underline{+91-8744969975} ~} 
    \href{mailto:prashant2003prashant@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{prashant2003prashant@gmail.com}} ~ 
    \href{https://linkedin.com/in/prashantzz}{\raisebox{-0.2\height}\faLinkedinSquare\ \underline{Linkedin}}  ~
    \href{https://github.com/prashantzzz}{\raisebox{-0.2\height}\faGithub\ \underline{Github}} 
\end{center}
\vspace{0.5mm}


%-----------EDUCATION-----------
\section{EDUCATION}
\resumeSubHeadingListStart
  \resumeSubheading
    {Bachelor of Technology $|$ Information Technology $|$ 8.6 CGPA}{2021 – 2025}
    {VIT Vellore, Tamil Nadu}{}
  
  \vspace{-3pt}% Additional negative space to remove gap
  \resumeSubheading
    {Senior Secondary (XII) $|$ Kendriya Vidyalaya Hindon, Ghaziabad $|$ \textbf{93\%}}{2020 – 2021}
    {}{}
  
  \vspace{-15pt}% Additional negative space to remove gap
  \resumeSubheading
    {Secondary (X) $|$ Kendriya Vidyalaya Narela, Delhi $|$ \textbf{87\%}}{2019 – 2020}
    {}{}
\resumeSubHeadingListEnd
%-----------EXPERIENCE-----------
\section{WORK EXPERIENCE}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Chubb \href{https://www.linkedin.com/posts/prashantzz_newjob-techintern-activity-7286705344293085185-dC1Q}{\raisebox{-0.1\height}\faExternalLink}}{Jan 2025 - Present} 
      {\underline{Tech Intern}}{On Site}
      \resumeItemListStart
        \resumeItem{\normalsize{Worked on .NET Core, SQL gaining real world experience and problems, Built APIs, Changed Encryption techniques, and SEO optimization, solving bugs, improved loading and efficiency of legacy applications.}}
      \resumeItemListEnd  
  
    \resumeSubheading
      {Salesforce $|$ PwC CTDP \href{https://trailhead.salesforce.com/}{\raisebox{-0.1\height}\faExternalLink}}{May 2024 - June 2024} 
      {\underline{Trainee}}{Remote}
      \resumeItemListStart
        \resumeItem{\normalsize{Completed the CTDP program by PwC, gaining comprehensive knowledge of Salesforce software, including Object Management and App Builder, configuration and Setup, Automation, including data import/export.}}
      \resumeItemListEnd  
  
    \resumeSubheading
      {SAIL India \href{https://www.linkedin.com/posts/prashantzz_newbeginnings-internship-sail-activity-7106663626261852162-n-TU}{\raisebox{-0.1\height}\faExternalLink}}{Sept 2023 - Oct 2023} 
      {\underline{Project Intern}}{On Site}
      \resumeItemListStart
        \resumeItem{\normalsize{E-commerce site on WordPress with WooCommerce, integrating a chatbot, Razorpay for payments, and SEO optimization, cutting load time by 20\% for better search engine rankings.}}
      \resumeItemListEnd  
  
    \resumeSubheading
      {GeM Tech Paras \href{https://www.linkedin.com/posts/prashantzz_internship-internshipextension-careerdevelopment-activity-7035116175877427200-YzU3}{\raisebox{-0.1\height}\faExternalLink}}{Jan 2023 - Dec 2023} 
      {\underline{UI/UX Intern}}{Remote}
      \resumeItemListStart
        \resumeItem{\normalsize{Designed UI/UX in designing and development team, generated thousands of revenue from clients.}}
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
\vspace{-12pt}

%-----------SKILLS-----------
\section{SKILLS \& LANGUAGES}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Database:}}{  \normalsize{MySQL / SQL Server / MongoDB / Supabase / MapReduce}} \\
     \textbf{\normalsize{Web development:}}{  \normalsize{ ASP .NET Core, React, Angular, Jquery, JWT Auth, Tailwind, Node Js, Wordpress}} \\
     \textbf{\normalsize{Languages:}}{  \normalsize{C\#, C, C++, Java, Python, TypeScript, JavaScript, HTML/CSS}} \\
    }}
 \end{itemize}
 \vspace{-15pt}

%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
              
        \resumeProjectHeading
          {\href{#}{\textbf{\large{\underline{MealPlanner}}} \href{https://prmealplanner.netlify.app/}{\raisebox{-0.1\height}\faExternalLink}} $|$ \large{\underline{Angular+TS, .NET 8, SQL Server, JWT Auth, RBAC, REST API, Tailwind}}}{2024}\\
          \resumeItemListStart
            \resumeItem {\normalsize{Full-Stack Development: Built a meal-planning app with Angular & .NET, implementing JWT auth, role-based access (Admin, Nutritionist, Customer), and dynamic shopping lists.}}
            \resumeItem {\normalsize{Feature Implementation: Developed recipe management, dietary tracking, and automated report generation for nutrition analytics with REST API integration.}}
          \resumeItemListEnd 
          \vspace{-13pt}
      
      \resumeProjectHeading
          {\href{#}{\textbf{\large{\underline{SteelStore For SAIL}}} \href{https://steelstore.rf.gd/}{\raisebox{-0.1\height}\faExternalLink}} $|$ \large{\underline{WooCommerce, PHP, elementor, Google Auth, Razorpay}}}{2023}\\
          \resumeItemListStart
            \resumeItem {\normalsize{WordPress E-commerce site, improved load time by 30\% using caching and compression.}}
            \resumeItem {\normalsize{Integrated Google Auth, a chatbot, Razorpay for payments, and SEO optimization.}}
          \resumeItemListEnd 
          \vspace{-13pt}
          
\resumeProjectHeading
          {\textbf{\large{\underline{Gen AI Projects}}} $|$ \large{\underline{NodeJs, Gemini API, HTML/CSS/JS, Tailwind, TesseractJs, AceJs}}}{2024}\\
          \resumeItemListStart
            \resumeItem {\normalsize{\href{https://genz-dev.netlify.app/}{\textbf{GenZdev} {\raisebox{-0.2\height}\faExternalLink}} - Generative frontend development with live preview, 50\% faster than manual.}}
            \resumeItem {\normalsize{\href{https://cureai.onrender.com/}{\textbf{CureAI} {\raisebox{-0.2\height}\faExternalLink}} - AI powered healthcare with image recognition diagnosis, accuracy: 90\%.}}
          \resumeItemListEnd 
          \vspace{-13pt}
      
      \resumeProjectHeading
          {\href{#}{\textbf{\large{\underline{GUI Applications}}} \href{https://github.com/prashantzzz/pAssist-Chatbot/releases/tag/v3.0}{\raisebox{-0.1\height}\faExternalLink}} $|$ \large{\underline{Python, Tkinter, Google/Wolfram/Akinator Search APIs, Manual NLTK}}}{2022}\\
          \resumeItemListStart
            \resumeItem {\normalsize{pAssist - Developed a voice based assistant windows app for daily tasks, saving time by 40\%.}}
            \resumeItem {\normalsize{Software testing tool - Image supported tool to automate GUI testing, reducing manual testing efforts.}}
            \resumeItem {\normalsize{School Data Management - Menu-driven app in Python with MySQL to manage student data.}}
          \resumeItemListEnd
          \vspace{-7pt}
    \resumeSubHeadingListEnd

\end{document}
