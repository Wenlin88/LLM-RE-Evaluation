# LLM-RE-Evaluation

Dataset companion to:

> **Benchmarking Requirements Extraction Automation Using a Large Language Model**
> *(under review)*

---

## Files

| Path | What it is |
|------|-----------|
| `product description.md` | Input document — a product specification for an Electric Coffee Mug Heater |
| `RRS/RRS.csv` | Ground-truth requirement set (77 unique IDs, 102 rows with alternatives) |
| `RRS/out of scope set.csv` | 8 items outside product scope (for false-positive checking) |
| `RRS/README.md` | Column definitions, ID scheme, and parsing hints |

## Usage

1. Feed `product description.md` to your extraction pipeline.
2. Match output against `RRS/RRS.csv` (see `RRS/README.md` for the ID convention).
3. Use `out of scope set.csv` to check scope discrimination.

The paper describes the construction process, evaluation metrics, and scoring methodology in detail.

## Citation

```bibtex
@misc{llm_re_evaluation_2024,
  author       = {Anonymous},
  title        = {{LLM-RE-Evaluation}: Benchmark Dataset for Requirements Extraction Automation},
  year         = {2024},
  publisher    = {GitHub},
  url          = {https://github.com/Wenlin88/LLM-RE-Evaluation}
}
```

*(Will be updated upon publication.)*

## License

- **Data** (CSV, Markdown): [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)
- **Code** (scripts): [MIT](https://opensource.org/licenses/MIT)

See [LICENSE](LICENSE) for full text.
