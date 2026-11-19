# Simple Interest Calculator

A Bash script that calculates simple interest from a principal amount, an annual interest rate and a time period in years. The repository is also set up as a small open-source project with a contributing guide, a code of conduct and a license.

## How it works

Inputs (entered at the prompt):

- `p` – principal amount
- `r` – annual rate of interest (percent)
- `t` – time period in years

Output:

```
simple interest = p * t * r / 100
```

The script uses `expr`, so it works with whole numbers only.

## Getting started

```bash
git clone https://github.com/martinab121/github-final-project.git
cd github-final-project
bash simple-interest.sh
```

## Project structure

```
simple-interest.sh    the calculator script
CONTRIBUTING.md       how to contribute
CODE_OF_CONDUCT.md    community guidelines
LICENSE               Apache License 2.0
```

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License

Licensed under the [Apache License 2.0](LICENSE).

---

Final project of the IBM "Getting Started with Git and GitHub" course (Coursera / IBM Skills Network).
