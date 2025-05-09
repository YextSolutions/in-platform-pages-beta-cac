# In-Platform Pages Beta

This repository contains the required CaC of In-Platform Pages for Yext. This will add a series of demo entities that have custom fields that can be bound to page section components.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Yext CLI](https://hitchhikers.yext.com/docs/cli/getting-started/install/)
- A blank Yext Account with the following features turned on
  - Pages
  - Pages Visual Editing
  - Pages Directory Generation

## Instructions

1. Clone this repository:

```bash
git clone [repository-url]
cd in-platform-pages-beta-cac
```

2. Login to your Yext Account through the Yext CLI

```bash
yext init [Yext account id]
```

3.  Push the resources to your account

```
yext resources apply
```

You are now ready to start beta'ing the new in-platform, Yext Pages experience!

## Additional Resources

- [Yext CLI Documentation](https://hitchhikers.yext.com/docs/cli/getting-started/overview/)
