Sliding Window Method, Lag method
- Previous time steps is called the window width or the size of the lag
- Turns our problem into supervised learning problem

Simple and Classical Forecasting
- Simple
    -- Baseline
        --- Naive - Persistent forecast
        --- Average
- Classical
    -- ARIMA / SARIMA (Seasonal)
        - ARIMA caters to suite of standard structures in time series
        - AR - Autoregressive - p
        - I - Integrated - d
        - MA - Moving Average - q
        Seasonal not supported
    -- SARIMA
        - Parameters (p, d, q, period of seasonality)
        - Parameters 
            -- P Seasonal autoregressive order
            -- D Seasonal difference order
            -- Q Seasonal moving average order
            -- m The number of time steps for a single seasonal period
            -- SARIMA (p,d,q)(P,D,Q)m