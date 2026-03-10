# DevOps Lab – Experiment 2

## Working with Maven

### Aim

To understand Maven and create a Maven project, learn about the POM file, manage dependencies, use plugins, deploy a simple website to GitHub Pages, and perform automated testing using Selenium with TestNG.

---

### Introduction to Maven

Maven is a build automation and project management tool mainly used for Java projects. It simplifies the process of building applications, managing dependencies, and maintaining a standard project structure. Maven uses an XML configuration file called **pom.xml** which contains information about the project, its dependencies, and build configurations.

---

### Key Benefits of Maven

* Automatically manages project dependencies.
* Automates the build process including compilation, testing, and packaging.
* Provides a standard directory structure for Java projects.
* Easily integrates with CI/CD tools such as Jenkins.

---

### Key Features of Maven

**Project Management:**
Maven manages project configuration, dependencies, and build lifecycle.

**Standard Directory Structure:**
Maven enforces a consistent structure which helps developers organize projects easily.

**Build Automation:**
Tasks like compiling source code, running tests, packaging applications, and deploying artifacts are automated.

**Dependency Management:**
Required libraries and frameworks are automatically downloaded from online repositories such as Maven Central.

**Plugin Support:**
Maven provides plugins to perform additional tasks such as packaging, testing, deployment, and code analysis.

---

### Creating a Maven Project

A Maven project can be created using IntelliJ IDEA by selecting Maven as the project type. During project creation, the project name and location are specified and Maven automatically generates the required project structure and configuration files.

---

### Understanding the POM File

The POM (Project Object Model) file is the most important configuration file in a Maven project. It contains details about the project including the project identifier, version information, dependencies, and plugins used during the build process.

---

### Dependency Management

Dependencies such as Selenium and TestNG can be added to the project using the POM file. Maven automatically downloads these dependencies from the Maven Central repository and includes them in the project during the build process.

---

### Creating a Simple Website

A simple static website is created inside the resources directory of the project. This website includes basic files such as an HTML page, a CSS file for styling, and an image logo.

---

### Deployment Using GitHub Pages

The project can be deployed using GitHub Pages. Static website files are copied into the **docs folder** of the repository so that GitHub Pages can host the website directly from that location.

After pushing the project to GitHub, GitHub Pages is enabled in the repository settings by selecting the main branch and the docs folder as the source.

Once enabled, the website becomes accessible through a public GitHub Pages URL.

---

### Selenium Test Automation

A Selenium test is created using the TestNG framework. The test opens a browser, loads the deployed website, and verifies whether the webpage title matches the expected title. After the validation, the browser is automatically closed.

---

### Result

Successfully created a Maven project, managed dependencies using the POM file, deployed a simple website using GitHub Pages, and executed an automated Selenium test using TestNG.

---

### Author

Prathibha D
B.E Computer Science and Engineering
East West College of Engineering
VTU
