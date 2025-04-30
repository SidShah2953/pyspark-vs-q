# KDB+/q: Revolutionizing Financial Data Processing

A comprehensive analysis and demonstration of KDB+/q capabilities in financial data processing, comparing its performance with traditional big data frameworks like PySpark.

## Overview

This project examines KDB+/q, a paradigm-shifting technology in financial services that combines:
- A high-performance columnar database
- A vector-oriented programming language
- Specialized time-series data processing capabilities

## Repository Structure

```
.
├── Term Paper.tex       # Detailed technical paper
├── Presentation.tex     # Presentation slides
├── Demos/
│   ├── Q.ipynb         # KDB+/q implementation demos
│   └── Python.ipynb    # PySpark comparison demos
└── kc.lic             # KDB+ license file (required for running demos)
```

## Demonstrations

The project includes two key demonstrations:

### Demo 1: Market Data Ingestion Speed
- Generates 10 million simulated trades
- Compares ingestion performance between KDB+/q and PySpark
- Measures raw storage speed and memory efficiency

### Demo 2: VWAP Calculation Performance
- Implements Volume Weighted Average Price calculations
- Compares query performance between platforms
- Demonstrates real-time analytics capabilities

## Performance Highlights

KDB+/q demonstrates significant performance advantages:
- 20-100× faster for point queries
- 50-100× faster for range queries
- 100-200× faster for aggregations
- 100-300× faster for time-series joins

## Setting Up KDB+/q Environment

1. **Download KDB+**
   - Visit [KDB+ Personal Edition](https://kx.com/kdb-personal-edition/)
   - Register for a free license for non-commercial use

2. **Installation**
   ```bash
   # macOS (using Homebrew)
   brew install q

   # Linux
   wget https://kx.com/download/kdb-personal-edition-linux
   chmod +x kdb-personal-edition-linux
   ./kdb-personal-edition-linux
   ```

3. **Required Python Packages** (for comparison demos)
   ```bash
   pip install jupyterlab
   pip install pyspark
   pip install pandas numpy
   ```

## Additional Resources

1. **Official KDB+ Documentation**
   - [KX Documentation](https://code.kx.com/q/)
   - [Q for Mortals](https://code.kx.com/q4m3/)

2. **Learning Resources**
   - [Learn Q](https://learn.kx.com/)
   - [KDB+ Tutorials](https://code.kx.com/q/tutorials/)
   - [Q by Examples](https://code.kx.com/q/tutorials/examples/)

3. **Community Resources**
   - [KX Community](https://community.kx.com/)
   - [Stack Overflow KDB+ Tag](https://stackoverflow.com/questions/tagged/kdb%2b)
   - [GitHub KX Examples](https://github.com/KxSystems/kdb)

4. **Development Tools**
   - [qStudio](https://github.com/KxSystems/qstudio) - IDE for KDB+/q
   - [Visual Studio Code q Extension](https://marketplace.visualstudio.com/items?itemName=kx.kdb)
   - [JupyterQ](https://github.com/KxSystems/jupyterq) - Jupyter kernel for Q

## Running the Demos

1. **Start KDB+ Server**
   ```bash
   q -p 5000
   ```

2. **Launch Jupyter**
   ```bash
   jupyter lab
   ```

3. Navigate to `Demos/` directory and open the notebooks

## License

- KDB+ requires a license for use (free for personal/academic use)
- Project documentation and demos are under MIT License

## Author

Siddhant Shah, Boston University (Spring 2025)

## Contributing

Feel free to submit issues and enhancement requests. Contributions to examples and documentation are welcome.

## Citation

If you use this work in your research, please cite:
```bibtex
@misc{shah2025kdbplus,
  title={KDB+/q: Revolutionizing Financial Data Processing},
  author={Shah, Siddhant},
  year={2025},
  institution={Boston University}
}
```