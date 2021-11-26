# Supabase CLI (WIP)

[Supabase](https://supabase.io) is an open source Firebase alternative. We're building the features of Firebase using enterprise-grade open source tools.

This repository contains all the functionality for our CLI. It is still under heavy development.

- [x] Running Supabase locally
- [x] Managing database migrations
- [x] Pushing your local changes to production
- [ ] Manage your Supabase Account
- [ ] Manage your Supabase Projects
- [ ] Generating types directly from your database schema
- [ ] Generating API and validation schemas from your database

## Getting started

### Install the CLI

#### macOS

```sh
brew install supabase/tap/supabase
```

#### Windows

```
scoop bucket add supabase https://github.com/supabase/scoop-bucket.git
scoop install supabase/supabase
```

#### Linux

Linux packages are provided in [Releases](https://github.com/supabase/cli/releases). To install, download the `.apk`/`.deb`/`.rpm` file depending on your package manager and run `sudo apk add --allow-untrusted <...>.apk`/`sudo dpkg -i <...>.deb`/`sudo rpm -i <...>.rpm` respectively.

### Run the CLI

```sh
supabase help
```

## Breaking changes

The CLI is a WIP and we're still exploring the design, so expect a lot of breaking changes. We try to document migration steps in [Releases](https://github.com/supabase/cli/releases). Feel free to file an issue if these steps don't work.

## Developing

To run from source:

```sh
# Go >= 1.16
go run -ldflags "-X github.com/supabase/cli/cmd.version=0.0.0" . help
```

---

## Sponsors

[![New Sponsor](https://user-images.githubusercontent.com/10214025/90518111-e74bbb00-e198-11ea-8f88-c9e3c1aa4b5b.png)](https://github.com/sponsors/supabase)
