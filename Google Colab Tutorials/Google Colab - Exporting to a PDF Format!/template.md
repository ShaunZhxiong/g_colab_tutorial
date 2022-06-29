# nbconvert

- Method 1 - Convert notebook to HTML then print as PDF
!jupyter nbconvert --to html /content/KNN.ipynb

- Method 2 - Convert notebook diretcly as a PDF (recommended)
!sudo apt-get install texlive-xetex texlive-fonts-recommended texlive-plain-generic
!jupyter nbconvert --to pdf /content/KNN.ipynb
