__std_api__ 
# Standard Application Programming Interface:

Start with a clear and descriptive title that conveys the purpose of your project. 
Follow it with a brief summary that explains what your project does and why it's useful or interesting.

Create and maintain a consistent API code base.
The default API handles DELETE, GET, POST, and PUT functions.


__Architecture__

| client | <--> | server | <--> | database |
| ------ | -- | ------ | -- | -------- |
| test-route-delete-handler | <--> | api-delete-handler | <--> | sql-delete-handler |
| test-route-get-handler    | <--> | api-get-handler    | <--> | sql-get-handler |
| test-route-post-handler   | <--> | api-post-handler   | <--> | sql-post-handler |
| test-route-put-handler    | <--> | api-put-handler    | <--> | sql-put-handler |

### Table of Contents: 
If your README is lengthy, include a table of contents to help users quickly navigate to specific sections.

* [Definitions](definitions.md)

## Installation: 
Provide clear instructions on how to install and set up your project. 
Include any dependencies, libraries, or tools required for the project to run smoothly. 
If necessary, include code snippets or commands for easy copy-pasting.

# Installation: 
Two part installation: 
1. install the repository and then 
1. install the runtime application.

## Repository Install
### Dependencies
#### Python 3
1. Install Python 3

#### [std_workspace](https://github.com/Wilfongjt/std_workspace.git)
1. use git.ws.sh workspace tool to download repository
1. ~/Developement/_tools/git.ws.sh

### The Repository Installation

__Tasks__

* Open a command window
* Navigate to your home folder, eg cd ~/
* Create one folder to store all development
* Create an organization
* Create a workspace
* Clone std_workspace
 
__Commands__
   
   ```commandline
    cd ~
    
    mkdir Development/

    cd Development/
    mkdir <ORGANIZATION>/
    
    cd <ORGANIZATION>/
    mkdir <WORKSPACE>/
    
    cd <WORKSPACE>/
    git clone  https://github.com/<<GH_ACCOUNT>>/<PROJECT>.git
    
    cd <PROJECT>/
   ```

## Usage: 
Explain how users can use your project. 
Provide examples, code snippets, or instructions to demonstrate how to utilize the various features and functionalities. 
Include any necessary configuration or setup steps.

## Documentation: 
If your project has extensive documentation, provide links or instructions on how to access it. 
This could include links to a separate documentation website, wiki, or specific sections within your repository.

### Contributing: 
Encourage others to contribute to your project by providing clear guidelines on how to get started, submit bug reports, propose new features, or contribute code. 
Include any code formatting conventions, testing guidelines, or contribution workflows that you expect contributors to follow.

### License: 
Specify the license under which your project is released. 
It's essential to clarify the permissions and restrictions associated with your codebase.

### Changelog: 
Maintain a changelog that summarizes the significant changes made to your project in each version release. 
This helps users understand what's new and assists in tracking the project's progress.

### Credits and Acknowledgments: 
Give credit to any individuals, libraries, or resources that have influenced or assisted your project. 
Include links to their repositories or relevant websites.

### Contact Information: 
Provide a way for users to get in touch with you, whether it's through email, social media, or a dedicated issue tracker.

### Badges: 
Optional but helpful, include badges in your README to highlight project status, build passing/failing, code coverage, and other relevant metrics. 
Badges can quickly convey project information at a glance.