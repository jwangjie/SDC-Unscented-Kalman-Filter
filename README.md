# Unscented Kalman Filter 

In this project utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. 

![UKF](https://github.com/jwangjie/jwangjie.github.io/blob/master/files/UKF.gif)


* Why: sensor measurement & physical model are not perfect

* How: assuming sensor measurements & physical model are Gaussian distributions
     * Predict states based on physical models
     * Update states based on sensor measurements 
* KF / Extended KF / Unscented KF
  * Physical Model
    * Linear: KF
    * Non-linear: EKF / UKF
      * Linearization approximation
        * One point using Taylor expansion: EKF
        * Multi-points using Sigma points method: UKF 
        
 ## Personal Notes: [ukf reference](https://github.com/jwangjie/SDC-Unscented-Kalman-Filter/blob/master/ukf%20reference.pdf)







