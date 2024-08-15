# Lilcody: A tiny coding assistant

Lilcody is a minimal version of Cody from Sourcegraph. The intent is to extract the core parts of Cody to create a small codebase that can be easily studied and experimented with by developers interested in understanding how such tools work.

To minify (or "distill", if you are into the whole LLM thing) Cody, we are lifting just the core code, and removing all handing of user accounts, authentication, and other features that are not strictly necessary for the core functionality.

We are hoping to make the commit history in the main branch fairly clean, building key features 1 large commit at a time, so you can look at things layer by layer by examining the git history.

Naturally, this codebase owes 100% of its existence to Cody, and we are grateful to the Cody team for their hard work and dedication to making Cody a reality. The Cody project can be found at https://github.com/sourcegraph/cody. It is made available under the permissive Apaache 2.0 license.