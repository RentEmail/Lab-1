# Lab-1 Project

Project Description

This repository contains a .NET Core Desktop application. This application is built, tested, signed, and packaged using a workflow defined in the GitHub Actions. This workflow is triggered on both push and pull_request events to the main branch.

Installation

To install this project on your local machine, you need to have .NET Core installed. You can download it from here.

Once you have .NET Core installed, clone the repository:

bash
Copy code
git clone https://github.com/Endrit112/Lab-1.git
Usage

To run the application, navigate to the repository's directory and use the .NET CLI:

bash
Copy code
cd Lab-1
dotnet run
Contribution

We welcome contributions from everyone. If you're unsure where to start, you can look at the open issues in our GitHub repository.

When you are ready to contribute, follow these steps:

Fork the repository.
Create a new branch on your forked repository.
Commit your changes to your new branch.
Submit a pull request, detailing the changes you've made and the problem they solve.
Tests

The tests for this project are run in the GitHub Actions workflow. You can also run them locally using the .NET CLI:

bash
Copy code
dotnet test
