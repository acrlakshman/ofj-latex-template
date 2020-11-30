# OpenFOAM Journal LaTeX template

<div align="center">

|                                **Template source**                                |                      **View on Overleaf**                       |
| :-------------------------------------------------------------------------------: | :-------------------------------------------------------------: |
| [on journal website](https://journal.openfoam.com/index.php/ofj/authorGuidelines) | [Rendered template](https://www.overleaf.com/read/xfjpcnvndzyk) |

</div>

---

## Basic usage

```sh
git clone https://github.com/acrlakshman/ofj-latex-template
cd ofj-latex-template
pdflatex ofj-template.tex
```

## Details

### Ubuntu

```sh
sudo apt-get install texlive-full
```

### Arch

If encountered errors related to missing files, please consider the following

```sh
cp ext/listings-1.8d.sty listings.sty
cp ext/booktabs.sty booktabs.sty
cp ext/algorithmic.sty algorithmic.sty
```

## Miscellaneous

- Generated pdf (ofj-template.pdf) from each workflow is being uploaded as artifacts, feel free to check them via `Actions` tab.
