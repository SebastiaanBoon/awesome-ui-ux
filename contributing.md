# Contribution Guidelines

Thank you for helping make this list better! Every contribution, from a one-line fix to a whole new section, is appreciated.

Please take a few minutes to read this page before opening a pull request. It keeps the list consistent and makes reviews quick and friendly.

## What belongs here

This list is a curation of the **best** UI/UX resources, not a directory of everything. A great entry is:

- **Useful**: it teaches something, solves a real problem, or inspires good work.
- **Maintained**: updated within the last couple of years, with working links and documentation. Archived, deprecated, or abandoned projects don't belong here.
- **Accessible to newcomers**: a clear homepage or README that explains what it is.
- **Not a duplicate**: please search the list first.
- **Not self-promotional spam**: you're welcome to suggest your own work if it is genuinely excellent, but say so in the pull request and expect it to be held to the same bar as everything else.

## How to add a resource

1. Find the best-fitting section in the [README](README.md). If none fits, open an issue to discuss a new one.
2. Add your entry at the **bottom** of that section.
3. Use this exact format:

   ```markdown
   - [Resource Name](https://example.com/) - Short, objective description.
   ```

4. Open a pull request with a title in the form `Add Resource Name`.

## Entry style

- Put a single space, a dash, and a single space between the link and the description.
- Start the description with an uppercase letter and end it with a period.
- Describe **what the resource is**, not how great it is. Skip marketing language such as "best", "amazing", or "ultimate".
- Don't repeat the resource name in the description.
- Keep it to one line, with no hard wrapping.
- Use the official spelling and capitalization of names (for example, `Node.js`, not `nodejs`).
- Link to the canonical page, not a shortened or tracking URL. Use `https` whenever it is available.
- Don't link to the same URL twice anywhere in the list.
- Don't add an entry that needs a login or payment just to see what it is, unless the service is widely known.

## Updating and removing entries

- Spotted a dead link, a rename, or a tool that has shut down? Please open a pull request that fixes or removes it. You'll be helping everyone.
- If a resource has become stale, open an issue or a pull request with a short note on why it should go.

## Checks that run on your pull request

Your pull request is automatically checked with [awesome-lint](https://github.com/sindresorhus/awesome-lint). If it reports a problem, you can reproduce it locally:

```sh
npx awesome-lint
```

Links are also checked on a schedule, so a failing link in an older entry is not your fault. Feel free to fix it in the same pull request if you like.

## Be kind

We want this to be a welcoming project. Please follow our [code of conduct](code-of-conduct.md) in issues, pull requests, and reviews.

## Questions?

Not sure whether something fits? Open an issue and ask. We're happy to help.
