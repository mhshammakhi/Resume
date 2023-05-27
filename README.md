What is this repo?
--------------------------------------------------------
This repo contains my resume which is based on LaTeX.
This template is ATS-friendly, ensuring compatibility with automated applicant tracking systems. This feature is crucial as many large companies utilize ATS for initial CV screening before human review.

How to add references?
--------------------------------------------------------
Add this code chunk to the end of the .tex file:
```
\section{References}
  \resumeSubHeadingListStart

    \resumeSubheading
      {Reference1's name}{Reference1's email address}
      {Reference1's title}{{Reference1's location}}

    \resumeSubheading
      {Reference2's name}{Reference2's email address}
      {Reference2's title}{{Reference2's location}}

    \resumeSubheading
      {Reference3's name}{Reference3's email address}
      {Reference3's title}{{Reference3's location}}

  \resumeSubHeadingListEnd
```
