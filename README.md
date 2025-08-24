# Final Certification Project

## “Web Development with Python”

Dear students, below is the assignment for the final project, which you must complete after finishing the courses *“Python Basics”*, *“HTML/CSS Web Development”*, *“Flask and FastAPI Frameworks”*, and *“Django Framework”*.

---

### Project Description

1. **Objective:** to review and practice the material learned throughout the program.
2. The project includes **mandatory** and **optional** tasks.

   * The mandatory task must be completed to receive your diploma. It will be graded.
   * The optional tasks can be completed for your portfolio and submitted for feedback. They are useful but do not affect the grade.
3. **Tools required for the mandatory task:** Python, Django framework.
4. **Submission format:** a link to a signed and viewable copy of this template with completed tasks in the designated fields. See instructions.

---

### Mandatory Task

**Project:** *Recipe Website* in Django

#### Task Overview

Using Django, create a website where users can add their own recipes and view recipes from other users. The final project must be submitted as a link to a working deployed website and the repository with the source code.

#### Detailed Task Description

Create a Django project and application(s) for the recipe site.

#### Models

Use Django’s built-in `User` model for users.
Prepare the following models:

* **Recipes**

  * Title
  * Description
  * Cooking steps
  * Cooking time
  * Image
  * Author
  * *Optional: additional fields such as ingredients, etc.*
* **Recipe Categories** *(optional)*

  * Name
  * *Optional: additional fields*
* **Join Table** for Recipes and Categories *(if implemented)*

  * Required linking fields
  * *Optional: additional fields*

#### Templates

Prepare a base template and the following child templates:

* Home page with 5 random recipes (brief view)
* Detailed recipe page
* Registration, login, and logout pages
* Add/Edit recipe page
* *Optional: any additional templates of your choice*

#### Forms

Create forms for inputting and editing recipes in your project. Integrate them into templates.

#### Views

Implement views that cover the entire project: models, forms, and templates.

#### Routes

Configure routes, ensuring all views and their related models, forms, and templates work properly.

#### Deployment & Content

Deploy the project on a cloud server. Populate the database with at least 5 recipes.
*If studying in a group, exchange links with classmates: add recipes to their site, and they add recipes to yours.*
