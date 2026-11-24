## Getting Started

### Cloning the repository

Basic calculator used to test with both unit and fuzzing testing.

This project uses [Foundry](https://book.getfoundry.sh/) and manages its dependencies (e.g. `forge-std`) as **git submodules** in the `lib/` folder. To make sure they are downloaded, clone the repository with:

```bash
git clone --recurse-submodules https://github.com/YOUR_USERNAME/foundry-repo.git
```

If you already cloned it without that flag, fetch the dependencies with:

```bash
git submodule update --init --recursive
```

### Build and test

```bash
forge build
forge test
```