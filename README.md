# Course for *reflimR* and *reflimR_Shiny*

This guide will walk you through the steps to download the `.Rmd` file from GitHub and open it in RStudio to follow the course for the R package [*reflimR*](https://cran.r-project.org/web/packages/reflimR/index.html) and the Shiny Application [*reflimR_Shiny*](https://github.com/SandraKla/reflimR_Shiny).

## Step 1: Download the Repository from GitHub

Since the course includes additional files (e.g., images), you need to download the entire repository:

1. **Go to the GitHub repository**
    - Open your web browser and navigate to this GitHub repository

2. **Download the entire repository**
    - On the GitHub repository page, click the **`Code`** button.
    - Click **`Download ZIP`**.
    - Extract the ZIP file on your computer.

## Step 2: Open the `.Rmd` File in RStudio

1. **Launch RStudio**.
2. **Set the Working Directory**:
    - Since the `.Rmd` file requires additional files, set the working directory to the extracted folder:

```r
setwd("/path/to/extracted/folder") # Replace `/path/to/extracted/folder` with the actual folder path
```

3. **Open the `.Rmd` file**:
    - Click on `File` → `Open File...`.
    - Navigate to the extracted folder.
    - Select the `.Rmd` file and click `Open`.

4. **Run the R Markdown File**:
    - Click `Knit` (top of the RStudio editor) to render the document.
       
## Contact

You are welcome to:
- Submit suggestions and bugs at: https://github.com/SandraKla/reflimR-workshop/issues
- Make a pull request on: https://github.com/SandraKla/reflimR-workshop/pulls
- Write an email with any questions and problems to: s.klawitter@ostfalia.de
