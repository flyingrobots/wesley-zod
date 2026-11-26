# Security

## Reporting a vulnerability

Email <security@flyingrobots.dev>. Please do not open a public issue for a vulnerability.

Include what you found, how to reproduce it, the version or commit, and what an attacker could do with it. You will get an acknowledgement, and a fix or a decision will be coordinated with you before anything is made public.

## Supported versions

wesley-zod is pre-1.0. Security fixes are made on `main` and released as the next version. Older versions are not patched.

## What the target does with its input

It reads one IR document from Wesley and returns generated files to Wesley, which writes them. It treats the IR as data: nothing in it is executed. Treat generated code as you would any code you did not write, and review it before you ship it.
