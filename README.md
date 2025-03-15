# Final_Project_AP
The repository contains the project of the class of Advanced Programming.

# Repository Rules

## Gitflow Branching Strategy

We will follow the Gitflow strategy throughout the project, which includes the following four main branches:

- **main**: This branch contains the public code.
- **develop**: The main development branch where new features are integrated.
- **release**: This branch is used to prepare updates before merging into `main`.
- **hotfix**: This branch is used for fixing bugs in the `main` branch.

## Branching and Development Workflow

- Development will be carried out on the `develop` branch, creating additional feature branches as needed (or at least the name of the developer).
- Merging into `develop` requires approval from another team member (after testing the changes).
- To create a new branch, use the following command:

  ```sh
  git checkout develop
  git checkout -b "feature_branch / name_developer"
  ```

## Code and Documentation Guidelines

- All code must be written in English.
- Grammar will not be reviewed, so using tools is recommended.
- Each feature must be documented, including:
  - Function or class descriptions.
  - Explanation of parameters and attributes.

By following these guidelines, we ensure a structured and efficient workflow in our GitHub repository.

