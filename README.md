# CertWatch Documentation

[![GitHub](https://img.shields.io/badge/GitHub-certwatch--app%2Fdocs-blue)](https://github.com/certwatch-app/docs)

This directory contains the documentation for [CertWatch](https://certwatch.app), built with [Mintlify](https://mintlify.com).

## Structure

```
docs/
├── docs.json              # Main configuration file
├── index.mdx              # Documentation home page
├── quickstart.mdx         # Getting started guide
├── certificates/          # Certificate management docs
├── notifications/         # Notification channel docs
├── teams/                 # Teams & organizations docs
└── api-reference/         # API documentation
```

## Local Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview documentation changes locally:

```bash
npm i -g mintlify
```

Run the development server:

```bash
mintlify dev
```

View your local preview at `http://localhost:3000`.

## Deployment

Documentation is automatically deployed via the Mintlify GitHub integration when changes are pushed to the main branch.

## Contributing

When adding or updating documentation:

1. Follow the existing file structure and naming conventions
2. Use MDX for rich content with React components
3. Test changes locally with `mintlify dev` before pushing
4. Ensure all internal links are valid

## Resources

- [Mintlify Documentation](https://mintlify.com/docs)
- [CertWatch App](https://certwatch.app)
- [CertWatch Support](mailto:support@certwatch.app)
