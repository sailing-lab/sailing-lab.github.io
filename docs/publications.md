# Instructions: Adding Publications
Simply create a `bib` entry to one of the following three files.
- `_bibliography/dissertations.bib` for dissertations.
- `_bibliography/papers.bib` for published papers.
- `_bibliography/preprints.bib` for preprints.

The format is almost identical to a standard `bib` entry, but with a few additional fields:
- `abbr` (required)

- `arxiv` (optional, but encouraged)
- `code` (optional, but encouraged)

- `abstract` (optional)
- `bibtex_show` (optional)
- `html` (optional)
- `pdf` (optional)
- `supp` (optional)
- `blog` (optional)
- `poster` (optional)
- `slides` (optional)
- `talk` (optional)
- `website` (optional)

Here's an example,
```
@inproceedings{deng2021compression,
  abbr={EMNLP},
  arxiv={https://arxiv.org/abs/2109.06379},
  code={https://github.com/tanyuqian/ctc-gen-eval},
  title={Compression, Transduction, and Creation: A Unified Framework for Evaluating Natural Language Generation},
  author={Deng, Mingkai and Tan, Bowen and Liu, Zhengzhong and Xing, Eric P and Hu, Zhiting},
  booktitle={EMNLP},
  year={2021}
}
```
