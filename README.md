<h1>SEASONAL FORECASTING BASED ON PROPHET TOOL FOR PERIODIC CASES</h1>

<h2>Description of Weather forecasting tool</h1>
<p1>A weather forecasting tool built using Machine learning tools (Prophet) which predicts the weather data and hence finds the flights routes as its linked with flight API.</p1>

<p2>
  <h3><u>Facebook Prophet</u></h3>
  <a href="https://facebook.github.io/prophet/docs/quick_start.html">Prophet</a> is an open soruce forecasting tool by Facebook. It can be used for forecasting
time series data based on an additive model where non-linear trends are fit with yearly,
weekly, and daily seasonality, plus holiday effects. It works best with time series that
have strong seasonal effects and several seasons of historical data. The smoothening
parameters for seasonality in prophet enable adjustment of historical cycles. It is fully
automated and we are using it with LSTM (Long Short Term Memory) in order to
predict the weather data.
</p2>
<br>

<p3>
  <h4>FLIGHT API</h4>
  <br>
We are using FLIGHTLOOKUP API for building flight connection. It is a better choice
as it has the dynamic multi connection engine and has trusted partner of airlines. Also
the multi linguistic support and comprehensive metadata like air craft codes and airport
station information are provided by this API which can be very useful for our system.
  </p3>
