These are some schematics for a [Spa Quip SP500](http://www.spa-quip.co.nz/shop/Controllers/Spa+Power+500/Spa+Power+500+2kW.html) controller board manufactured by [Spa Quip/Davey](http://www.spa-quip.co.nz/) in New Zealand.

These are **NOT** design files and are **NOT** associated in any way with Davey. **Water + Electricity = DEATH** ... mkay?

These files are provided as reference for my [spaduino](https://github.com/tinybrain/spaduino) project.

The schematics and symbols are for [gEDA/gaf](http://geda-project.org/). Because mainly weirdos and space monkeys use these tools, I've also included the combined EPS outputs as a pdf.

The `.sch` files reference symbols in the local `symbols` directory, including several which override standard symbols. Running `gschem` from the project directory will load them properly via the `gafrc` file.
