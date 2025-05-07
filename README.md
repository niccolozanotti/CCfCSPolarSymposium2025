Poster for [Cambridge Centre for Climate Science Polar Symposium 2025](https://polarnetwork.org/events/ccfcs-polar-symposium-2025/).

## Build locally
Assuming you have a $\LaTeX$ [distribution](https://www.latex-project.org/get/) installed on your machine, you can build the pdf from source with
```shell
chmod +x scripts/compile.sh scripts/cleanup.sh
make poster
```
which should cleanup auxiliary files (`make clean` gets rid of them).