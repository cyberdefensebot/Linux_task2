# GitHub-Ready Lab Workflow Template

## Project description

This repository is a professional, reusable structure for completing a Linux, cybersecurity, networking, programming, or other technical practical lab and documenting the work for GitHub.

**Important:** The uploaded task supplied for this package is a reusable workflow-generation prompt rather than a specific technical lab. Therefore, this package does **not** invent usernames, commands, IP addresses, permissions, configurations, screenshots, results, or other lab-specific requirements.

Populate the marked placeholders after the actual lab/activity document is supplied.

## Objective

Provide a consistent GitHub-ready workflow for:

- understanding a technical lab;
- documenting the required procedure;
- recording commands;
- collecting genuine evidence;
- verifying results;
- preparing submission materials; and
- packaging the completed work professionally.

## Current task status

- [ ] Specific lab/activity document supplied
- [ ] Lab objective extracted
- [ ] Lab-specific requirements extracted
- [ ] Required commands identified
- [ ] Required files/directories identified
- [ ] Evidence requirements identified
- [ ] Submission requirements identified
- [ ] Workflow customized
- [ ] Lab performed
- [ ] Evidence collected
- [ ] Final verification completed

## Technologies/tools

No specific technology is assumed by the supplied prompt.

Possible tools may be added only when required by the actual lab, for example:

- Linux shell
- Git
- GitHub
- GitHub Actions
- Python
- Networking utilities
- Cybersecurity tools

Do not add a tool merely because it is common in technical labs.

## Prerequisites

Before customizing this repository, obtain the actual lab/activity document and extract its exact requirements.

You may also need:

- a suitable lab environment;
- required permissions;
- Git;
- a GitHub account/repository;
- any software explicitly required by the lab.

## Project structure

```text
github-ready-lab-workflow-template/
├── README.md
├── .gitignore
├── docs/
│   ├── README.md
│   └── task-overview.md
├── workflow/
│   ├── README.md
│   └── workflow.md
├── commands/
│   ├── README.md
│   └── commands.sh
├── scripts/
│   └── README.md
├── evidence/
│   ├── README.md
│   ├── screenshots/
│   │   └── .gitkeep
│   └── terminal-output/
│       └── .gitkeep
└── submission/
    ├── README.md
    ├── command-history.txt
    └── final-output.txt
```

## Step-by-step workflow

1. Read the actual lab/activity document.
2. Record the objective and every explicit requirement in `docs/task-overview.md`.
3. Customize `workflow/workflow.md` with only the required practical phases.
4. Put the required commands, in the correct order, in `commands/commands.sh`.
5. Create scripts only where automation is genuinely appropriate.
6. Perform the lab in the required environment.
7. Capture genuine screenshots and terminal output in `evidence/`.
8. Record actual command history and final results in `submission/`.
9. Run the final verification checklist.
10. Commit and push the project to GitHub.

## Expected results

No completed lab result is claimed in this template.

The completed project should contain:

- a lab-specific README;
- a complete, logically ordered workflow;
- the exact required commands;
- genuine evidence;
- actual verification results;
- completed submission materials.

## Evidence requirements

See [`evidence/README.md`](evidence/README.md).

Only genuine evidence produced while performing the lab should be added.

## Submission requirements

See [`submission/README.md`](submission/README.md).

The exact academic submission requirements must come from the actual lab document. No submission rule has been invented here.

## Safety and permission notes

Follow the permissions and safety requirements stated by the actual lab.

Do not run privileged, destructive, networking, security, or cleanup commands merely because they appear in a generic template. Any such commands must be supported by the actual activity instructions and executed in an appropriate authorized environment.

## Final verification checklist

- [ ] Actual lab document reviewed
- [ ] Objective documented
- [ ] Every lab requirement documented
- [ ] Required commands documented
- [ ] Required files/directories documented
- [ ] Required configuration documented
- [ ] Required evidence documented
- [ ] Workflow matches the lab
- [ ] Commands are in the correct order
- [ ] Privilege requirements are explicit
- [ ] No fake results included
- [ ] No fake screenshots included
- [ ] Actual evidence captured
- [ ] Command history saved
- [ ] Final output saved
- [ ] Submission requirements completed
- [ ] Repository reviewed before pushing to GitHub
