# Docu-Mentor

<img width="212" alt="docu_mentor" src="https://github.com/maxpumperla/docu-mentor/assets/3462566/de9f387a-4c97-4ade-a811-3b6282950f2c">

Automatically get suggestions to improve your PRs from this
GitHub app powered by [Anyscale Endpoints](https://app.endpoints.anyscale.com/).

## Installation

Simply install the app on your project on GitHub: [Docu-Mentor App](https://github.com/apps/docu-mentor)

## Usage

Then in any PR in your project, create a new comment that says:

```bash
@docu-mentor run
```

and I will start my analysis. I only look at what you changed
in this PR. If you only want me to look at specific files or folders,
you can specify them like this:

```bash
@docu-mentor run doc/ README.md
```

In this example, I'll have a look at all files contained in the
"doc/" folder and the file "README.md".

## Checking that it works

Simply run

```bash
pytest . -s
```

to evaluate the doc sanitation bot against GPT-4.

## How it works under the hood

TODO
