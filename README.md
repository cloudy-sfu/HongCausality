# Hong Causality

The GUI tool to calculate Hong causality between the future (financial noun) and spot price

## Install

If you have MATLAB runtime or the full software, you can click it to run. Otherwise, it will automatically download a MATLAB runtime.

Reference: [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html)

## Usage

1. Click "Select File" to import the price of future and corresponding spot, where the columns are as follows.

| date | spot | future |
| ---- | ---- | ------ |
|      |      |        |

2. Select "Figure Content", and the corresponding figure will be indicated on the canvas.
3. According to the ACF/PACF figure, decide the p, q and M of an ARIMA regression, and input them to corresponding fields.
4. Click "Calculate", and results are indicated on the right.