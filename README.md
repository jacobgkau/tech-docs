# System76 Technical Documentation (mdBook Version)

This is an archive of the [System76 Tech Docs repository](https://github.com/system76/tech-docs) as it
appeared when using its original website engine of [mdBook](https://github.com/rust-lang/mdBook). I've forked
this archive because it's been a significant part of my professional career for the past ~6.5 years.

When this repository was live, it could be viewed at https://tech-docs.system76.com (later moved
to https://system76.com/tech-docs). This earlier version can now be viewed at
https://web.archive.org/web/20260610220520/https://system76.com/tech-docs/, or using the instructions below.

## Editing

There are two methods to view and edit the book. There is a quick method that
does not include additional UI elements such as search, and the complete way
that will render the book as it is rendered on the official website.

### GitHub (Quick)

The book can be viewed and edited on GitHub by going to
[src/README.md](src/README.md).

### mdBook (Complete)

- Download and extract [mdBook](https://github.com/rust-lang/mdBook/releases).
    - The last version used for this repository was [0.5.2](https://github.com/rust-lang/mdBook/releases/tag/v0.5.2).
- Clone the repository using `git`.
- From the cloned repository, run `mdbook serve` (using the path to `mdbook` as necessary).
- You may now view the book at: `http://localhost:3000`
- Edits are made in the `src` directory. The server will automatically update the generated website and refresh any open browser tabs when changes are made.
