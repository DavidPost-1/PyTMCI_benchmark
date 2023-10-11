# PyTMCI Benchmark

## Running the Notebook
This example uses [PyTMCI](https://github.com/stfc/PyTMCI). First install it with
```
pip install PyTMCIVlasov
```

Optionally, you can install the numba dependencies to use a JIT that can make PyTMCI run faster
```
pip install numba
pip install git+https://github.com/numba/numba-scipy.git
```
The example should still work without these commands.


This notebook has some additional dependencies for plotting and running PyTMCI in multiple processes
when doing sweeps of particles-per-bunch
* matplotlib - for plotting
* tqdm - for progress bars in the notebook 
* joblib - for parallel processing
* loky - for joblib

To install these, run
```
pip install matplotlib tqdm joblib loky
```

Afterwards, it should be possible to run the notebook. 