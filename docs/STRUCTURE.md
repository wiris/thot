# Project Structure

## General overview

```
.
├── README.md           - Project description and router to documentation
├── docs                - Documentation files
└── [product_name]      - Folder containing any plan text file to be consumed 'in app'.
```

## Documentation

The main project documentation is located at [docs](../docs).

```
docs
├── README.md                             - General project description and specification. Main router for the project's documentation
├── ENVIRONMENT.md                        - The project's environments descriptions router
├── RELEASE.md                            - How the project is released
├── STRUCTURE.md                          - The project's directory structure and a brief description of each file
├── ISSUE_REPORTING.md                    - The way to handle project issues
└── USAGE.md                              - How to use the project
```

## Other folders

The rest of the folders in this repository are meant to contain any `plain text file`, grouped by certain criteria. Most of the time the criteria to be used is the product that will consume that files, but no rules regarding this topic have been set __by the moment__, so as a rule of thumb, just use the common sense.