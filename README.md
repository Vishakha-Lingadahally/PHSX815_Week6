Simpson rule vs Trapezoidal rule

How to run the code:
For Simpson's rule, run Simpson.py on the command line. Then enter 'simps(lambda x: "any function involving x", "lower limit of the intergral", "upper limit of the integral", "Number of subintervals") to calculate the integral.
For Trapezoidal rule, run Trapezoidal_rule.py on the command line. Then enter 'trapz(lambda x: "any function involving x", "lower limit of the intergral", "upper limit of the integral", "Number of subintervals") to calculate the integral.

Example:

Simpson's rule-Number of subintervals=100-
Input: simps(lambda x: 5*x^3+3*x^2, 0, 1, 100)
Output: 2.25

Trapezoidal rule-Number of subintervals=100-
Input: trapz(lambda x: 5*x^3+3*x^2, 0, 1, 100)
output: 2.2501750000000005


Simpson's rule-Number of subintervals=1000-
Input:simps(lambda x: 5*x^3+3*x^2, 0, 1, 1000)
Output: 2.2500000000000004

Trapezoidal rule-Number of subintervals=1000-
Input: trapz(lambda x: 5*x^3+3*x^2, 0, 1, 1000)
Output: 2.2500017500000005


Simpson's rule-Number of subintervals=10000-
Input:simps(lambda x: 5*x^3+3*x^2, 0, 1, 10000)
Output: 2.2500000000000004

Trapezoidal rule-Number of subintervals=10000-
Input: trapz(lambda x: 5*x^3+3*x^2, 0, 1, 10000)
Output: 2.2500000175

