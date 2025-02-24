# Contributing to Delaware Valley Region School Atlas  

This file will include information on how contributors can help, such as:

Adding or updating school data.
Improving the code or visualizations.
Fixing bugs or optimizing the project.

---

## How to Contribute  

### Contributing to the SchoolsDatabase
- Please make sure the format stays consistent.
- The geoencoder in the code will automatically find the coordinates. Just provide:
    1. 'name' column: the name of school
    2. 'type' column: the school type -- ensure this entry remains one of the four: 
        - **District Public**
        - **Charter Public**
        - **Secular Private** 
        - **Religious Private**
    3. 'address'column: the address to the school
    4. 'county' column: the county that the school is located in -- ensures it is in the Del.Val. Region

### Contributing to the the Project
1. **Fork the Repository**:  
Click on the "Fork" button in the top-right corner of the repository page to create a personal copy of the project.

2. **Clone Your Fork**:  
To clone this repository, run the following command in your terminal:

```bash
git clone <your_forked_repository_url>
```

3. **Installing Poetry For Dependencies**
Run the following command to install Poetry (if you don’t already have it installed):

``` bash
curl -sSL https://install.python-poetry.org | python3 -
```

### Project Usage
1. Clone the repository and navigate to the project directory:

``` bash
cd <repository_folder>
``` 

2. Install dependencies using Poetry:

```bash
poetry install
```

3. Run the project by executing the code in SACJResearch-SchoolAtlas.ipynb

4. Make Your Changes:
- Add or update school data in the appropriate files.
- Improve the map visualizations or fix issues in the code.

5. Commit Your Changes:
Write a clear and concise commit message. 

Example:
```bash
git commit -m "Added new charter school data for Bucks County"
```

6. Push Your Changes:
```bash
git push origin <branch_name>
```

7. Submit a Pull Request:

Go to the original repository and click “Compare & Pull Request.”
Describe your changes and how your updates contribute.

8. Recommended: HTML Export for Cleaner Visibility

For a better and cleaner view of the notebook's output, you can export the `SACJResearch_SchoolAtlas.ipynb` to HTML. This will remove code contents, leaving only the title, description, and visualizations, making it more suitable for presentations or reports.

Use the following command in the terminal command line when finished updating to export the notebook to HTML:

```bash
jupyter nbconvert --to html --no-prompt --TemplateExporter.exclude_input=True --TemplateExporter.exclude_output=False SACJResearch_SchoolAtlas.ipynb
```

