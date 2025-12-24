# Workflow Testing

Practice repository for testing GitHub Actions workflows and custom actions.

## What's Inside

- **Custom actions** - Calculator and greeting actions with inputs/outputs
- **Automated tests** - Running tests on push
- **Conditional deployments** - Deploy to different environments based on branch
- **Hello World** - Basic workflow trigger

## Structure
```
.github/workflows/
├── hello.yml
├── test.yml
├── test2.yml
├── use-calculator.yml
├── use-greeting.yml
└── Deploy-Conditionnel.yml
```

## Usage

Push code to trigger workflows. Some workflows use custom actions from separate repositories.
