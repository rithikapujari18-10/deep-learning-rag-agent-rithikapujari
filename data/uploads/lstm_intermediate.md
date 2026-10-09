# LSTM

## Forget Gate

The forget gate in an LSTM controls which information from the previous cell state should be discarded. It uses a sigmoid activation to produce values between 0 and 1.

## Input Gate

The input gate determines which new information should be added to the cell state. It uses a sigmoid gate to control the update and a candidate cell state to provide new information.

## Cell State

The cell state carries information through the sequence and allows LSTM networks to preserve important information over long sequences.

# Long Short-Term Memory (LSTM) Networks

## What Is an LSTM Network?

A Long Short-Term Memory (LSTM) network is a type of recurrent neural network (RNN) designed to learn long-term dependencies in sequential data. It is commonly used for time series forecasting, natural language processing, and sequence prediction.

Unlike a traditional RNN, an LSTM has a cell state and gates that regulate how information is stored, updated, and discarded over time.

## Vanishing Gradient Problem in Traditional RNNs

The vanishing gradient problem occurs when gradients become extremely small as they propagate backward through many time steps during training. As a result, traditional RNNs struggle to learn relationships between events that are far apart in a sequence.

## How LSTM Addresses the Vanishing Gradient Problem

LSTMs use a cell state and specialized gates to help preserve information over longer sequences. The cell state provides a pathway for information and gradients to flow through time. The gates regulate which information is retained, added, or discarded.

This design helps reduce the vanishing-gradient problem, although it does not eliminate it in every situation.

