Variable names and meanings:
N = “Number of Periods”: the number of months or the number of years.
I = “Interest Rate”: interest per month or interest per year; period must match that of N.
PV = “Present Value”: the value of the first transaction.
PMT = “Payment”: the value of each regular, periodic payment.
FV = “Future Value”: the value of the last transaction.

Different inputs for tvm.c:
set N number_of_periods ← set the value of N (N must be a positive integer)
set I interest_rate ← set the value of I (I must be positive)
set PV present_value ← set the value of PV
set PMT payment ← set the value of PMT
set FV future_value ← set the value of FV
compute N ← compute N and print it to 0 decimal positions: %.0f
compute I ← compute I and print it to 6 decimal positions: %.6f
compute PV ← compute PV and print it to 2 decimal positions: %.2f
compute PMT ← compute PMT and print it to 2 decimal positions: %.2f
compute FV ← compute FV and print it to 2 decimal positions: %.2f
clear ← clear all financial variables (N, I, PV, PMT, and FV) to 0
test ← run simple tests of four of your functions
blank line ← ignore a blank line
