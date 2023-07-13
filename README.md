# Curriculum Vitae & Cover Letter

Personal curriculum vitae and cover letter written in LaTeX.

## External resources
- [awesome-cv](https://gitlab.nakim.be/fork/awesome-cv): fork of posquit0's [Awesome-CV](https://github.com/posquit0/Awesome-CV).
- [latex-fontawesome](https://gitlab.nakim.be/nakim/latex-fontawesome): bindings for [Font Awesome](https://fontawesome.com) icons to be used in XeLaTeX.

## Build

### From linux

```bash
docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc texlive/texlive:latest xelatex -output-directory=outputs cv.tex
```

## License

This project is licensed under the terms of the **MIT License**. See [LICENSE](LICENSE) for more details.
