# Contributing to Awesome Vision-Language Navigation

Thanks for your interest in contributing! 🎉

## How to Contribute

### Adding a New Paper

1. Fork this repository
2. Add your paper to the appropriate category in `README.md`
3. Follow the format:
   ```
   | YYYY-MM-DD | [Paper Title](link) | `task-tag` | Venue or - | resources |
   ```
4. Submit a pull request

### Categories

- **Foundation & Benchmark**: Datasets, benchmarks, surveys, and early works (before 2022)
- **Understanding the Decision**: Action prediction, decision making, policy learning
- **Understanding the Error**: Error recovery, safety, collision avoidance
- **Understanding the Future**: World models, diffusion, prediction
- **Understanding the History**: Memory, continual learning, experience replay
- **Understanding the Reality**: Sim-to-real, deployment, real robots

### Task Tags

- Use task-specific tags when the paper clearly belongs to a concrete navigation setting, e.g. `instruction-based`, `obj-goal`, `uav-nav`, `social-nav`.
- Use `foundation` as the fallback tag for general benchmarks, simulators, platforms, surveys, evaluation papers, and broad embodied-navigation resources that are not tied to a single task family.

### Guidelines

- Only include LLM/VLM-related navigation papers
- Papers should be peer-reviewed or from arXiv
- Ensure the paper fits the category theme
- Use the exact source link format
- In the `Venue` column, write the accepted or published venue only; if a paper is only submitted, under review, or unconfirmed, write `-`

## Questions?

Feel free to open an issue if you have any questions!
