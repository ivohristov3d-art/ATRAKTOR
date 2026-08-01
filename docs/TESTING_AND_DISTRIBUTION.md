# Testing and Distribution

## Current Distribution Model

ATRAKTOR ENGINE remains private.

External testing will use controlled access rather than exposing the source repository.

## Recommended Closed-Test Path

For the first tester, prepare a versioned installation package containing only the files required to install and run ATRAKTOR.

The tester should not need Git, source-code access, or knowledge of the internal repository.

A test package should contain:

- installer or structured installation script;
- validation script;
- version manifest;
- release notes;
- basic start instructions;
- feedback instructions;
- no personal runtime data;
- no backups;
- no development-only files;
- no secrets or provider credentials.

## GitHub Collaborator Access

Private-repository collaborator access may be used for trusted technical collaborators.

It is not the preferred experience for a nontechnical test user.

## Public Repository

The public ATRAKTOR repository contains product information and public release materials.

It does not grant access to the private ATRAKTOR ENGINE source code.

## First Test User

The recommended first external test is a controlled installation on Ninka's computer using a dedicated Closed Alpha package.

The result should validate:

1. clean installation on another computer;
2. successful startup;
3. creation or opening of a test project;
4. basic conversation flow;
5. persistence after restart;
6. uninstall or safe removal;
7. collection of usability feedback.
