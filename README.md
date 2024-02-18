# My Curriculum Vitae
You can view it in the cv.pdf file or download it [here](https://github.com/maria-a-gutierrez/public-cv/raw/main/cv.pdf).

## Meta
What is the point of this repository? 
- I edit my CV on Overleaf. Before, with each new update in the CV, I downloaded the compiled pdf, uploaded it to my website media files, and updated all links to it in website. Now it is all automatic.  

How does the automatic process work?  
- The groundwork is in another (private) repository. The Overleaf project with my CV pushes each update in the TeX file from Overleaf to the private repo. That repo has a workflow that compiles the pdf after each push (using [this Github Action](https://github.com/thomas-chauvet/latex2pdf-action)) and pushes the updated pdf to the public repo (that you are in right now). 
