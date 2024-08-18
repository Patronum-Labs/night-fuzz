# <h1 align="center">🌙 Night-Fuzz: Foundry Fuzzing Template</h1>

<p align="center"><b>What's stopping you from fuzzing your tests overnight?</b></p>

<p align="center">Night-fuzz is a template for turbocharging your smart contract testing with overnight fuzz campaigns.</p>

## 🛠 Setup

1. Click **Use this template** on GitHub to create a new repository with this template.
2. Clone your new repository locally.

## 📦 Dependencies

- [Git](https://git-scm.com)
- [Foundry](https://github.com/foundry-rs/foundry)

## 🧪 Running Tests

For a quick test run:

```bash
forge test
```

## 🌙 Nightly Fuzzing

The `.github/workflows/nightFuzz.yml` file configures a GitHub Action to run extensive fuzzing every night at midnight UTC. This allows for much larger test runs without impacting your daily development workflow.

To customize the nightly fuzzing:
1. Open `.github/workflows/nightly-fuzz.yml`
2. Adjust the cron schedule or fuzzing parameters in `foundry.toml` as needed

## 📜 License

This project is licensed under the [MIT License](LICENSE).
