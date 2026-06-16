# LIF Threshold Analysis

A spiking neural network experiment exploring how firing threshold affects spike frequency in a Leaky Integrate-and-Fire neuron.

## What It Does

We built a simple LIF neuron using snnTorch and fed it constant input current (0.2 amps) over 50 time steps. We then swept the firing threshold from 0.5 to 2.0 and measured how many spikes the neuron produced at each threshold value.

## Key Finding

Higher threshold = fewer spikes. The relationship is smooth and monotonic: at threshold 0.5 the neuron fires 17 times; at threshold 2.0 it fires only 3 times.

## Files

- `lif_threshold_sweep.ipynb` — the full Colab notebook with code and plots

