# py-draw-simple-simplicial-complex

A Python script to visualize 2D simplicial complexes from a list of simplices.

## Features

- Draws 2D simplicial complexes from input simplices.
- Supports Google Colab execution.
- Simple and easy to use.

## Requirements

- Python 3.x
- Matplotlib
- NumPy
- NetworkX

## Installation

No installation required if using Google Colab. If running locally, install dependencies with:

```bash
pip install matplotlib numpy networkx
```

## Usage

Run the script in Google Colab or a local Python environment.

### Example

```python
# Example with 4 simplices
simplices = [[0,1],[1,2,3],[2,4],[4,5,6,7],[4,0],[0,2],[0,9,10],[9,10,11,12]]
dict = extract_simplices(simplices, 7)
draw_k_simplex(dict)
```

## Running in Google Colab

1. Open `k-simplex.ipynb` on Google Colab (clicking on it will show an option to open it in Colab).
2. Execute all the cells.

## License

This project is licensed under the MIT License.
