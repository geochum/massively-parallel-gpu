cat << EOF > README.md
# Massively Parallel GPU Programming Exercises

A personal project implementing and experimenting with CUDA/C++ exercises and concepts from
[Programming Massively Parallel Processors](https://www.elsevier.com/books/programming-massively-parallel-processors/hwu/978-0-323-91231-0)
(4th edition) by Wen-mei W. Hwu et al.

## Structure

- \`chapter01/\`, \`chapter02/\`, ... — Exercises, notes, and experiments per chapter.
- \`experiments/\` — Performance tests, benchmarks, and custom experiments.
- \`scripts/\` — Helper scripts for building or running code.
- \`data/\` — Sample inputs, outputs, or benchmark logs.
- \`notes/\` — Additional notes and explanations.

## Getting Started

To build:
\`\`\`bash
nvcc -o chapter01/ex1 chapter01/ex1.cu
./chapter01/ex1
\`\`\`

## License

MIT (see LICENSE file)
EOF
