## Cloud Development Environment with IBM Granite Code, Continue and Ramalama

[![Contribute](https://www.eclipse.org/che/contribute.svg)](https://workspaces.openshift.com#https://github.com/rohankanojia-demos/openshift-devspaces-continue-ramalama-poc)

This repository demonstrates the integration of [OpenShift DevSpaces](https://developers.redhat.com/products/openshift-dev-spaces/overview) with the [Continue AI coding assistant](https://marketplace.visualstudio.com/items?itemName=Continue.continue) and [IBM Granite](https://www.ibm.com/granite) models for enhanced cloud development workflows. It serves as a proof of concept (POC) for leveraging AI tools in collaborative development environments.

## What is Ramalama?
A CLI tool to manage and serve AI models locally, similar to Ollama and Goose CLI. Its distinguishing factor focuses on running LLMs in secure, isolated container environments. It’s compatible with pulling models from well-known registries like Hugging Face or Ollama Hub.

## Prerequisites
- [Red Hat Developer Sandbox](https://developers.redhat.com/developer-sandbox) Account
- OpenShift DevSpaces account.
- GitHub OAuth access for repository integration.
- Basic knowledge of cloud development environments and [devfile](https://devfile.io/).

## How to try it?

1. Go to [Red Hat Developer Sandbox](https://developers.redhat.com/developer-sandbox) and register an account there.
2. Once you've got an account, you can access Red Hat OpenShift Dev Spaces by going to https://workspaces.openshift.com
3. On User Dashboard, navigate to Create Workspace tab and provide URL of this repository.
4. Wait for the Cloud Development environment to start
5. Once Cloud Development environment is ready, you'll see that [Continue extension](https://marketplace.visualstudio.com/items?itemName=Continue.continue) gets automatically installed. You'll also see that your workspace notifies you about a process running in the cluster (that's basically granite-code LLM served by Ramalama).
6. Your Continue extension is automatically configured to connect to LLM, on clicking Continue icon, you should be able to query LLM with various coding tasks.