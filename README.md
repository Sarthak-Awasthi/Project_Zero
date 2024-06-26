# Game Development Repository

Welcome to the game development repository! This repository contains all the necessary files and resources for developing our game.

## Getting Started

### Prerequisites

Before you start working with this repository, please ensure you have the following installed:

- **Git**: Version control system for tracking changes.
- **Git LFS (Large File Storage)**: Required for handling large files. You can install it from [here](https://git-lfs.com/).

### Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Install Git LFS**

   If you haven't installed Git LFS yet, download and install it from [https://git-lfs.com/](https://git-lfs.com/).

   After installation, initialize Git LFS in your repository:

    ```bash
    git lfs install
    ```

3. **Pull LFS Files**

   To ensure all large files are correctly pulled from the repository, run:

    ```bash
    git lfs pull
    ```

## Usage

### Branching Strategy

We follow the Git Flow branching strategy:

- **main**: The production-ready code.
- **develop**: The development branch where the latest development changes are available.
- **feature/your-feature**: Feature branches for new features.
- **bugfix/your-bugfix**: Bugfix branches for fixing bugs.
- **release/your-release**: Release branches for preparing new production releases.

### Making Changes

1. Create a new branch for your feature or bugfix:

    ```bash
    git checkout -b feature/your-feature-name
    ```

2. Make your changes and commit them with a meaningful message:

    ```bash
    git add .
    git commit -m "Add feature: your feature description"
    ```

3. Push your branch to the repository:

    ```bash
    git push origin feature/your-feature-name
    ```

4. Open a Pull Request (PR) to merge your changes into the `develop` branch.


## License

This project is will be licensed in future

## Acknowledgments

- Thanks to all the contributors who have helped in the development of this project.

---

Happy Coding!
