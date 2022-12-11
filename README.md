# Multistep Multiappliance Load Prediction

A digital companion to the preprint 

```
Alona Zharova and Antonia Scherz (2022). 
Multistep Multiappliance Load Prediction.
arXiv preprint.
```

## Summary 

A well-performing prediction model is vital for a recommendation system suggesting actions for
energy-efficient consumer behavior. However, reliable and accurate predictions depend on informative
features and a suitable model design to perform well and robustly across different households
and appliances. Moreover, customers’ unjustifiably high expectations to accurate predictions may
discourage them from using the system in the long-term. In this paper, we design a three-step forecasting
framework to assess predictability, engineering features, and deep learning architectures to
forecast 24 hourly load values. First, our predictability analysis provides a tool for expectation management
to cushion customers’ anticipations. Second, we design several new weather-, time- and
appliance-related parameters for the modeling procedure and tests their contribution to the model’s
prediction performance. Third, we examine six deep learning techniques and compare them to
tree- and support vector regression benchmarks. We develop a robust and accurate model for the
appliance-level load prediction based on four datasets from four different regions (US, UK, Austria,
and Canada) with an equal set of appliances. The empirical results show that cyclical encoding of
time features and weather indicators alongside a long-short term memory (LSTM) model offer the
optimal performance.

**Keywords:** Multivariate · Multistep · Time Series · Prediction · Appliance Level · Electricity Load
