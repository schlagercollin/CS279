# CS279

### General Project Structure
```
├── SimpleGrayScott.py
├── [...] <other simulation code>
├── requirements.txt
└── simulations
    ├── simple_iterations-100_length-100_feed-0.0545_kill-0.03
    └── [...] <other simulation results>
```

## Requirements

Virtual environment setup
```
virtualenv venv  # create virtualenv named 'venv'
source venv/bin/activate # activate this virtual environment
```

```
pip install -r requirements.txt  # install the requisite files
```

## Example Run

Running the default script will simulate a run of two particles with
`feed=0.0545`, `kill=0.03`, and `length=100`.

It will save the results under 
`simulations/simple_iterations-100_length-100_feed-0.0545_kill-0.03`

```
python SimpleGrayScott.py
```
