# Automox Worklets Repository

A collection of custom worklets for extending Automox endpoint management capabilities.

## Overview

This repository contains ready-to-use worklets for Automox that help automate endpoint management tasks across Windows, macOS, and Linux systems.

## Directory Structure

```
├── windows/
│   ├── software/
│   ├── security/
│   ├── maintenance/
│   └── configuration/
├── macos/
│   ├── software/
│   ├── security/
│   └── configuration/
├── linux/
│   ├── software/
│   ├── security/
│   └── configuration/
└── cross-platform/
    └── utilities/
```

## Using These Worklets

1. Browse to the appropriate directory for your OS and task
2. Open the worklet file to review the code
3. In Automox console, navigate to **Manage → Policies**
4. Click **Create Policy** and select **Worklet**
5. Copy and paste the code into the evaluation and remediation sections
6. Configure parameters as needed and deploy

## Contributing

We welcome contributions! Please:
- Fork this repository
- Add your worklet to the appropriate directory
- Include proper documentation in your script
- Submit a pull request with a clear description

## Best Practices

- Include error handling in your worklets
- Test thoroughly before deploying to production
- Use descriptive names and good documentation

## Resources

- [Automox Worklets Documentation](https://help.automox.com/hc/en-us/articles/5352100773396-How-to-Use-Worklets)
- [Automox Worklets Catalog](https://www.automox.com/worklets)

## License

This repository is licensed under the MIT License.
