## quality control
# look at what comes in and goes out of the solver

modified so that it uses the same argschema and json inputs as the solver.

usage:
```
EM_aligner_python >ipython

In [1]: %pylab
In [2]: import EMaligner.qctools.CheckPointMatches as cpm
In [3]: f = cpm.CheckPointMatches(args=["--input_json","path/to/this.json"])
In [4]: f.run(1241,1241)

```
