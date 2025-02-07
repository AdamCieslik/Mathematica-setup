# Wolfram Mathematica Notebooks with Custom Styling  

This repository contains a collection of **Wolfram Mathematica** notebooks featuring a custom visual style. The styling enhances readability and clarity, ensuring that code cells, mathematical equations, and text are presented in a structured and visually clear manner.  

## Features & Objectives  
This repository includes three different files that share common goals:  
- **Ensuring that code cells are delineated by borders**, making them visually distinct from textual content.  
- **Using the "Times New Roman" font** for all textual elements; however, this can be changed if needed.  
- **Displaying the estimated execution time** on the right side of each code cell.  

## File Descriptions  
Each of the following files is designed to implement these style settings:  

- **`Preamble Notebook.nb`** – This notebook contains all the style settings described above, located in the *Notebook Style* section. To apply them, simply load this notebook.  
- **`Preamble Notebook + MaTeX.nb`** – This is an extended version of the previous notebook, with an additional section for loading the **MaTeX** library. If **MaTeX** is already installed on your computer, the code will simply load it; otherwise, it will attempt to install it automatically.  
- **`AdamC_Light.nb`** – This notebook encodes the custom style directly, so you don't need to load the *Notebook Style* preamble manually.  

---

## Installing `AdamC_Light.nb`  
To install and use the `AdamC_Light.nb` stylesheet, follow these steps:  

1. Open your Mathematica notebook and type the following command:  
   ```mathematica
   SystemOpen[$UserBaseDirectory <> "/SystemFiles/FrontEnd/StyleSheets/"]
   ```
   This will open the directory for user-defined stylesheets.
2. Move or copy AdamC_Light.nb to the StyleSheets folder.
3.	Restart Mathematica to apply the changes.
4.	Open the notebook where you want to use the new style.
5.	Apply the style:
	•	Navigate to Format > Stylesheet.
	•	You should see AdamC_Light in the list of available styles.
	•	Select it to apply the custom style to your notebook.


## Additional Resources  
If you're looking for tools to enhance your workflow, consider these:  

- **[Mathcha.io](https://www.mathcha.io)** – A powerful online tool for creating mathematical drawings and diagrams.  
- **[Obsidian](https://obsidian.md/)** – A highly flexible and efficient note-taking application.

---

## ⚡ Feel Free to Contribute!  

---

**Thank you for your interest!**  
