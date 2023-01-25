# Standardized Pipelines

This book references all the bioinformatics standardized pipelines of the HaploTeam. All pipelines that are widely used across multiple projects can be described here. The purpose of this book is to improve reproducibility of the analyses by using the same protocols for recurring tasks, such as short sequencing reads mapping or SNP filtering. 

# How to modify the book ?

First, download the git repository.  
```{bash}
git clone https://github.com/HaploTeam/StandardizedPipelines
```

Modify anything you want (add pages, modify existing ones, etc) and regenerate the book with Rstudio (open R project and then Build > Build All). Then, update the git repository. 

```{bash}
git add .
git commit -m "New commit"
git push -u origin main
```

