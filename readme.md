# Writing Documentation
Adding clear and thorough documentation to your projects is very important both for yourself and for others. It is important for yourself so that when you revisit your code in the future, you have ways to remember the purpose, tooling, and development history of what you made. Documentation is important for others because without it, no one will use or contribute to your code. From [A beginner’s guide to writing documentation](http://www.writethedocs.org/guide/writing/beginners-guide-to-docs/):

>If people don’t know why your project exists,
they won’t use it.  
If people can’t figure out how to install your code,
they won’t use it.  
If people can’t figure out how to use your code,
they won’t use it.  

In short, writing good documentation is a way for developers to transfer the *why* behind the code that they create. Code without documentation is not useful.

## Learning Objectives
- Define the steps in adding documentation to a hosted repository
- Describe the content that good documentation should contain
- Define what Markdown is and how to use it
- Create a `readme.md` for a project

## Adding Documentation to a Repo
The first step to adding documentation to a project is to a create a `readme.md` file (sometimes capitalized as `README.md`) to the **root directory** of your project's repository. By using this naming convention, code hosting platforms such as GitHub will automatically detect this file, render it into HTML, and display it when users navigate to your repository.

## Documentation Content
You want to provide your readers with all of the information that they need to know, but no more. Unlike some other forms of writing, documentation should be clear, concise, and to the point. Similarly, it should be written in a way to appeal both to normal users (who don't know or care how the code works) and developers (who may want to evaluate or contribute to your code).

Generally, a good `readme` will have *at least* the following sections:
- **Description**
  - What your project is / should be used for
  - What problem(s) your projects solves
- **Brief Example**
  - This could be a code snippet showing how your project should be used (if it is meant to be integrated into another app)
  - This could be a screenshot of your project running in the browser (if it is a stand-alone application)
- **List of Features / User Stories**
  - This typically will be a short list of the features / user stories that you planned during the development phase of the project
  - To provide more detail, you can show how you categorized these features into Bronze (MVP), Silver, and Gold Levels and indicate which features you complete / have yet to complete
- **List of Technologies Used**
  - Often you will want to list the technologies you used to create the project.
  - This typically would consist of all primary languages, frameworks, and libraries your app is composed of.
  - This is particularly important when it comes to recruiters scanning your projects for keywords.
- **Installation Instructions / Getting Started**
  - This section should walk a reader, step by step, through the process of setting up your project.
  - For a tool meant to be integrated into other projects, this would likely outline the process of installing and accessing your project.
  - For an application, this would likely outline the process of forking, cloning, and starting the app locally.
- **Contribution Guidelines**
  - This section should offer guidance on where and how users can contribute to your code, identify bugs, and propose improvements.
  - Good links to include are:
    - A link to the project's main repository
    - A link to the project's issue tracker


## Markdown
The `.md` extension on your `readme.md` stands for [Markdown](https://en.wikipedia.org/wiki/Markdown), which is a light-weight markup language that can be easily rendered into HTML (or other formats). However, its syntax is much simpler and faster to write than HTML, making it a good choice for writing up documentation.
> This lesson is written in Markdown

## You Do: Markdown Tutorial
Complete this short tutorial on Markdown's syntax. Please raise your hand if you get stuck or have questions.

[Markdown Tutorial](http://www.markdowntutorial.com/)
