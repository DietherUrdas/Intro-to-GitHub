# Intro-to-GitHub

## Purpose of a Repository

A repository (or "repo") is where a project's files and their full change history are stored and managed, so work stays organized, trackable, and shareable.

## Version Control (Git, GitHub, GitLab)

A repo holds source code, documentation, and configuration, plus a complete record of every change. It lets you:
- Track history: see who changed what and when, and roll back mistakes.
- Collaborate: work in parallel using branches, pull requests, and merging.
- Keep one source of truth: a single backed-up copy on a remote server, shared publicly (open source) or privately.
- Automate: trigger testing, builds, and deployment whenever changes are pushed.

## Software Design (Repository Pattern)

A repo is a code layer between application logic and the data source (e.g. a database). It hides how data is stored or fetched, so code can ask for "all users" or "order #42" whether the data comes from SQL, an API, or a file. The result is cleaner code, easier testing (swap in a fake data source), and the freedom to change storage technology later.
Adding new line for Task 4 assignment
