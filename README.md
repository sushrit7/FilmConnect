# FilmConnect

## Overview
FilmConnect is a Python project designed to analyze relationships between actors based on their shared appearances in movies. The project utilizes a dataset of actor and movie information to construct a graph representation of these relationships, allowing users to explore the connections between different actors.

## Getting Started
Before you begin, ensure you have Python 3.x installed on your system.

### Installation
1. Clone the FilmConnect repository:
```bash
  git clone https://github.com/sushrit7/FilmConnect.git
```

2. Navigate to the project directory:
```bash
  cd FilmConnect
```

3. Download Dataset:

   [IMDb Datasets](https://datasets.imdbws.com/)

   You will need to download the `name.basics.tsv.gz` and the `title.basics.tsv.gz` files to the project directory.


### Usage
Follow these steps to use FilmConnect:

1. **Split Dataset**: Run `splitdataset.py` to split the main dataset into smaller files for efficient processing.
  ```bash
    python splitdataset.py
```

2. **Graph Construction**: Run `graph.py` to build the graph representation of actor relationships based on movie appearances.
```bash
python graph.py
```

3. **Main Program**: Finally, execute `main.py` to interact with the FilmConnect program and explore the relationships between actors.
```bash
python main.py
```
Make sure to run these scripts in the specified order to ensure proper functioning of the FilmConnect project.


Enjoy exploring the connections between actors with FilmConnect!
