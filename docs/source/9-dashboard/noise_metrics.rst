.. list-table:: Metrics for assessing data quality (Noise levels)
   :header-rows: 1

   * - Metric
     - Formula
     - Description
     - Threshold
     - Label
   * - Average value
     - `A(t) = \frac{1}{(m - p + 1)} \sum_{i=p}^{m} a_i`
     - The average or mean of a set of data points is simply the sum of all the data points divided by the total number of data points.
     - ?
     - 
   * - Max value
     - max(s(t))
     - 
     - <3fT
     - 
   * - Variance
     - `\text{Variance} = \frac{1}{(m - p + 1)} \sum_{i=p}^{m} (a_i - A(t))^2`
     - It is calculated by finding the average of the squared differences from the mean.
     - ?
     - 
   * - FFT (Fast Fourier Transform)
     - 
     - FFT is used to convert from time to frequency domain.
     - <= 10 fT
     - 
