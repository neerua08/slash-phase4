# SLASH
**Group Number - 75**

**Team Members -** 
Rohan Manish Ajmera, Hemil Mehta, Jash Gopani, Akhil Neeruganti

## Difficulties faced during Project Evaluation and Setup
1. After cloning the project "c"-slash, the installation instructions directed the user to utilize the package manager pip and install all of the package dependencies based on the requirements.txt file. We used the command that was described in the user manual for the installation. Following a successful installation using the provided command, we attempted to launch the program in accordance with the rest of the instructions. However, on attempting to run the application, an error appeared which said that the necessary packages could not be located or installed. As we looked into the issue further, we discovered that we had two different versions of Python loaded on our local system (the most recent one was for vscode, and the other was for Jupyter Notebook), and that the dependencies were only installed on the later version. We decided to keep the LTS version (the one for the Jupyter Notebook) and remove the other one in order to fix the problem. In addition to this, we were required to work with an older version of Python (3.9.7)
2. It was tough to grasp how to participate as a developer since there was an absence of documentation for the design language system that was being used by the project. As there was no formatter disclosed for the code, no frontend theme or design standards, and no system structure/design related diagram, we had to manually figure out the system flow, which we understood via trial and error.
3. On using the project, we found that the command line version was functioning as mentioned in the documentation with a few minor edge-case related technical bugs here and there. Further, on using the UI version, i.e., “Slash-Mini”, everything was functional and the application displayed multiple search results as one would expect. On a closer look, we found 2 major issues.
   * The scraped search results were not always pertinent to the search query. For instance, when we searched for "Dell Inspiron 14 Plus," we were presented with a list of results that referred to a wide variety of products, not just the one we were looking for. These results included things like laptop skins, covers, bags, and a few other models related to the Dell Inspiron series, with the actual product appearing at the bottom of the list. From a user experience standpoint, this made it harder to locate the appropriate product.
   * When the user clicked the filter button located on the results filter controls, a new search request was initiated rather than the presently received results being filtered.

## Things that could have been avoided 
1. It would have been possible to avoid scraping things from Etsy if it had been realized that the vast majority of the items obtained from that platform were nearly or entirely irrelevant.
2. It would have been more efficient to focus on building a web application instead of a command line interface, which would have allowed the product to appeal to a far larger audience. It is also difficult to operate without being provided with detailed instructions.
3. The user interface of the webpage is rendered non-responsive as a result of the use of HTML tables, which also makes the webpage less user-friendly in general.
4. A more clear documentation could have prevented the struggles of deploying the application. With this, we could understand what software was needed and the version of the software to use.

## Proposed solutions to mitigate the above problems
1. In order simplify the installation process, we would prioritize the development of extensive documentation that is understandable to all users trying to clone and execute the project. We would adhere to the following guidelines:
    * Enumerate frequently asked questions and errors that arise throughout the various stages of project setup, development, testing, and deployment.
    * A comprehensive document that encompasses the details of test cases.
    * This document provides information pertaining to style checkers, code formatters, and syntax checkers.
2. To enhance the readability of the readme.md files, it is advisable to limit the number of project videos included inside the file. Instead, a more effective approach would be to add the films to a YouTube playlist and include the corresponding URL within the readme file. 
3. Include a small number of diagrams and documentation of the code in order to provide the reader with a high-level grasp of the architecture, data flow, and specifics of the API that will be used by the developer.
4. Maintain release notes that may be used as reference material for both current and future developers to understand the evolution of the project as well as the direction it is heading.
5. In the software documentation, explain the rationale behind the selection of particular software and tools, as well as the significance of any decisions made for the project itself.
6. Clarifying the supported versions of the requirements will help eliminate questions about which version to implement.
