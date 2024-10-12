<div align="center">
    <a href="https://cloudcomputingclub.cs.uml.edu/">
        <img src="static/img/logo.png" alt="Logo" width="50%" height="50%"/>
    </a>
    <hr>
    <h1>UML Class Resources</h1>
</div>
Class Resources Repository. Integrates with Club website.<br/>

This is the official repository for hosting UML class resoures on the [club website](https://umlcloudcomputing.org/docs/resources).

## 📒 Guidelines & Rules

This is a **student-led initiative** for sharing helpful resources for Computer Science classes at the University of Massachusetts Lowell. We aim to build a collaborative space where students can contribute valuable content while maintaining academic integrity. 🎓

### 📝 Contribution Guidelines
- **We welcome contributions** like topics, study materials, explanations, practice questions, and any content that helps students understand the course material. 📘
- **Rules**:
    - No assignment solutions.
    - No handouts or documents from the class unless **explicitly permitted** by the professor. 🚫
    - All contributions must be **original** or have **proper permissions** for use. ❗
    - No course material should be shared without permission. 🔒
- You may **reference assignments** but **do not** provide solutions or assignment instructions. ⚠️
- Please review the [UMass Lowell Academic Integrity Policy](https://www.uml.edu/catalog/undergraduate/policies/academic-policies/academic-integrity.aspx) to ensure compliance. 📚

### 🚨 Important Reminders
- **All contributions must be original** or have proper permissions to use class content. ❗
- **Respect intellectual property**: Sharing any course material without permission is prohibited. 🔒

### 🌟 How to Contribute
1. Create a new branch, preferablly following [conventional commits standards](https://www.conventionalcommits.org/en/v1.0.0/)
2. Make your edits on the appropriate branch within `docs/web_docs/`.
3. Once your changes are complete, submit a **pull request (PR)** with clear details about the updates or content you are adding to this repository.

#### 🔨 Building your changes locally
Since this repository hosts the content displayed on the website *independently* from the website source code itself, viewing the content of your edits to the markdown docs is done using a docs only instance of Docusaurus.

Prequisites:
- Node package manager - `npm`

When you've cloned the repository for the **first time**, run the following command to install the project's dependencies:
```bash
npm install
``` 

**For subsequent runs** and after running installing the dependencies:

Run the following command locally in your terminal:
```bash
npm start
```

This will open a development server that will perform **live** and **accurate** updates to your markdown edits. The compiled content on the development folder is accurate to the production site. 

> [!IMPORTANT]
> When the developer server starts you will be prompted to a page with information about contribution guidelines. Read this closely! It's important that every contributor understands and follows these rules!

To **stop** the server use `Ctrl + C` in your terminal. 

>[!NOTE]
> Our club leaders will moderate all contributions to ensure they follow the guidelines and maintain academic integrity. 🛠️

### 📬 Removal Requests
If a professor or faculty member would like to have content removed, please [contact us](mailto:cloudcomputingclub@uml.edu) with "**Removal Request**" in the subject header. 📨

### 🌟 Let’s Collaborate
Let’s make this platform a valuable resource while keeping academic standards high! 💡

