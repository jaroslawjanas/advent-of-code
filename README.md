# Advent of Code Solutions

This repository contains my personal solutions to [Advent of Code](https://adventofcode.com/) challenges.

## About Advent of Code

Advent of Code is an annual programming event created by Eric Wastl. It features an Advent calendar of small programming puzzles released daily throughout December. These puzzles are designed for a variety of skill levels and can be solved in any programming language.

The challenges vary in difficulty and subject matter, generally becoming harder as the event progresses. You don't need a computer science background to participate - just some programming knowledge and problem-solving skills. Every puzzle is designed to have solutions that complete within 15 seconds on decade-old hardware.

People use Advent of Code for interview preparation, corporate training, university coursework, competitive speed-solving, and friendly competitions via private leaderboards.

## Why I Do This

I participate in Advent of Code because it's genuinely fun to challenge myself with these puzzles. I love the creative problems and the charming stories woven into each year's event.

When programming became my profession, some of that initial spark and joy faded into the background of deadlines and requirements. Advent of Code has become my way of rekindling that excitement I felt when I first started coding - the thrill of solving a puzzle just because it's interesting, not because it's a ticket or a feature request.

More recently, these challenges have taken on another purpose: they're my opportunity to practice coding manually, without AI assistance. As AI tools have become increasingly integrated into my daily work, Advent of Code gives me a space to keep my problem-solving skills sharp and maintain the ability to think through solutions from scratch.

## About This Repository

This repository contains my solutions implemented in **Python** using **Jupyter notebooks**. Each year's solutions are organized in separate directories with individual notebooks for each day's challenge.

Starting from 2024, each puzzle's input is stored in a separate text file alongside the notebooks.

### Repository Structure

```
advent-of-code/
├── 2023/
│   ├── AoC 2023 - Day 1.ipynb
│   ├── AoC 2023 - Day 2.ipynb
│   ├── environment.yml
│   └── ...
├── 2024/
│   ├── AoC 2024 - Day 1.ipynb
│   ├── input - Day 1.txt
│   ├── environment.yml
│   └── ...
└── 2025/
    ├── AoC 2025 - Day 1.ipynb
    ├── input - Day 1.txt
    ├── environment.yml
    └── ...
```

## Setup

### Prerequisites

- [Conda](https://docs.conda.io/en/latest/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

### Installation

1. Clone this repository:
   ```bash
   git clone <repository-url>
   cd advent-of-code
   ```

2. Create the Conda environment for the desired year:
   ```bash
   cd 2025  # or 2024, 2023
   conda env create -f environment.yml
   ```

3. Activate the environment:
   ```bash
   conda activate aoc-2025  # or aoc-2024, aoc-2023
   ```

4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

## Usage

1. Navigate to the year directory you want to explore
2. Open the corresponding day's notebook (e.g., `AoC 2025 - Day 1.ipynb`)
3. Run the cells to see the solution and results

## Note

These are my personal solutions created for learning and problem-solving practice. If you're participating in Advent of Code, I encourage you to attempt the puzzles yourself before looking at solutions!

## Links

- [Advent of Code Website](https://adventofcode.com/)
- [About Advent of Code](https://adventofcode.com/2025/about)
