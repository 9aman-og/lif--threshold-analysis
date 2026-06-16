# LIF Threshold Analysis

A spiking neural network experiment measuring how firing threshold affects spike count in a Leaky Integrate-and-Fire neuron.

## What I Did

I built a simple LIF neuron using snnTorch and fed it constant input current (0.2 amps) over 50 time steps. I then swept the firing threshold from 0.5 to 2.0 and measured how many spikes the neuron produced at each threshold value.

## Key Finding

Higher threshold means fewer spikes. At threshold 0.5 the neuron fires 17 times; at threshold 2.0 it fires only 3 times. The relationship is smooth and monotonic.

## Files

- `lif_threshold_analysis.ipynb` — the full Colab notebook with code, results, and plots
