# README

This Python code is for the MSD (mean-squared displacement) data reading and converting from the Lammps log file.
Before use this code, msd compute process should be already addressed in Lammps procedure. details in :https://lammps.sandia.gov/doc/compute_msd.html

The output example may look like this:
![10wt200mpa295k](https://user-images.githubusercontent.com/7994574/106329234-189fdb00-624f-11eb-8104-495b3349bae5.png)

Two black fitting lines in bottom right figure represent MSD slopes, which will be used in the conductivity converting process.

The output lines include the conductivity value calculated from equation σ = Npair * e^2 * (q+^2 * D+ + q−^2 * D−) / V * kB * T

average temp is : 295.025038218
295.025852381
average press is : 1984.12540811
1986.75814064
average volume is : 30393.277
30393.277
msd_slope_na is : 0.3318
self_coff_na is : 0.0553
msd_slope_cl is : 0.3272
self_coff_cl is : 0.0545
36
30393.277
1.60219e-19
1.38065e-23
295.025852381
conductivity is : 8.199
