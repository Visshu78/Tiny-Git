# Tiny Git

**Tiny Git** is a minimalistic implementation of a Git-like version control system. It provides basic functionalities to initialize a repository, store objects, create commits, and even clone repositories.

## Features

- Initialize a Git repository (`init`)
- Hash and store objects (`hash-object`)
- Read stored objects (`cat-file`)
- Write and manage trees (`write-tree`)
- Create commits (`commit-tree`)
- Clone remote repositories (`clone`)

## How It Works

Tiny Git uses basic operations like compression, hashing, and file manipulation to replicate some of Git's core functionalities. It supports basic blob, tree, and commit object types and provides an elementary repository structure inside a `.git` folder.

## Implementation Details

Tiny Git includes:

- **Object Storage**: Uses zlib compression and SHA-1 hashing to store blobs, trees, and commits in `.git/objects`.
- **Basic Repository Structure**: Implements `.git` with `HEAD`, `objects`, and `refs`.
- **Custom Commands**: Provides simplified versions of Git commands like `init`, `cat-file`, and `clone`.

## Limitations

- No branching or merging capabilities
- No index or staging area
- Limited support for remote repository features

---

Explore, learn, and experiment with the inner workings of a version control system using **Tiny Git**!
