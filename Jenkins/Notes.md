- Jenkins by default runs on port 8080
- ![image](https://github.com/muppin/mastering-DevOps/assets/56094875/a421d99b-b0ec-416f-9f36-9deedadc6965)


**Credentials**
- **Scope** - System and Global
     - System - Only available for jenkins server and nodes. Not for jenkins jobs.
     - Global - Everywhere acessible ( jenkins, nodes, items, all child items)
     - Project - Limited to project, only with multibranch pipeline. Inside pipeline. System credentials not accessible here.

- **ID** - Reference  for your credentials
- **Folder plugin** - Enables to organize build jobs in folders. Credentials scoped to your project.



**Discover Branches**
- Filter by name - Regular expression. Example: `^dev|master.*$ `
- For all branches `.*`  (Any character, any number of times)
  

**Jenkins File**
![Uploading image.png…]()


