# Interactive Heatmaps using D3.js

This project provides an interactive visualization of Hong Kong's monthly temperatures from 1997 to 2017, enabling users to explore historical temperature trends dynamically. The visualizations offer insights into seasonal temperature variations and daily fluctuations, making them valuable for climate analysis and educational purposes.

## Level 1: Year/Month Heatmap
The visualization for Level 1 can be accessed [here](https://observablehq.com/d/ed4cf2f624cad356).  
It demonstrates a heatmap showing monthly maximum and minimum temperatures across years.

## Level 2: Improved Heatmap with Daily Changes
The visualization for Level 2 can be accessed [here](https://observablehq.com/d/ec193d17ea9be76a).  
It includes an improved heatmap with embedded line charts in each cell to show daily temperature variations.

---

### How to Use
- Visit the above links to interact with the visualizations directly on Observable.
- For more details about the implementation, refer to the code in the folders Level 1 and Level 2.

## Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/tanaymehendale/CSCE-679.git
cd CSCE-679
```

### 2. Extract the Archive
```bash
cd Level2  # or Level1
tar -xvzf ec193d17ea9be76a.tgz
cd <extracted-folder-name>  # replace with actual folder name
```

### 3. Run with http-server or python3
```bash
npm install -g http-server
http-server -p 8000
```

```bash
python3 -m http.server 8000
```

Go to http://localhost:8000 to view the results.

Make sure to install python3 /npm / node if not installed already. 

Run the server from the folder that contains the index.js and the index.html files.