# Intro

> Building an application on Amazon ECS.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series, available in English and Vietnamese.

**Read the workshop online:** https://vanhoangkha.github.io/000108-Build-application-on-Amazon-ECS/

## Overview

In this workshop, we will show an overview of the Amazon ECS service, the components that make up the service, such as how to connect to the application from the internet, and how to connect to the application. Connect service-to-service without going to the internet. In addition, the workshop also introduces the CloudFormation service to help build system using IaC quickly and easily. We will also build a proof of concept about "Pilot Light" disaster recovery strategy

## Workshop contents

1. ECS Introduction
2. CloudFormation Introduction
3. Deploy Application
   - Setup CloudFormation
   - Debug with ECS Exec
   - Monitor
4. Disaster Recovery Strategy
5. Clean up

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone https://github.com/vanhoangkha/000108-Build-application-on-Amazon-ECS.git
cd 000108-Build-application-on-Amazon-ECS
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages (`*.md` English, `*.vi.md` Vietnamese) |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
