Massive MIMO with Multi-Antenna Users
==================

This is a code package is related to the follow scientific paper:

Xueru Li, Emil Björnson, Shidong Zhou, Jing Wang, “[Massive MIMO with Multi-Antenna Users: When are Additional User Antennas Beneficial?](http://arxiv.org/pdf/1603.09052),” Proceedings of International Conference on Telecommunications (ICT), Thessaloniki, Greece, May 2016.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the paper. *We encourage you to also perform reproducible research!*


##Abstract of Article

We analyze the performance of massive MIMO systems with N-antenna users. The benefit is that N streams can be multiplexed per user, at the price of increasing the channel estimation overhead linearly with N. Uplink and downlink spectral efficiency (SE) expressions are derived for any N, and these are achievable using estimated channels and per-user-basis MMSE-SIC detectors. Large-system approximations of the SEs are obtained. This analysis shows that MMSE-SIC has similar asymptotic SE as linear MMSE detectors, indicating that the SE increase from having multi-antenna users can be harvested using linear detectors. We generalize the power scaling laws for massive MIMO to handle arbitrary N, and show that one can reduce the multiplication of the pilot power and payload power as 1/M where M is the number of BS antennas, and still notably increase the SE with M before reaching a non-zero asymptotic limit. Simulations testify our analysis and show that the SE increases with N. We also note that the same improvement can be achieved by serving N times more single-antenna users instead, thus the additional user antennas are particular beneficial for SE enhancement when there are few active users in the system.


##Content of Code Package

The article contains 3 simulation figures, numbered from 1 to 3. These are respectively generated by the Matlab scripts simulationFigure1.m, simulationFigure2.m, and simulationFigure3.m. The package also contains the Matlab script BSofHexagonNetwork.m, DropUEinHexagonCell.m, and SystemPlot.m which are used by the scripts to setup the simulation scenario.

See each file for further documentation.


##Acknowledgements

The work is supported by National Basic Research Program (2012CB316000), National S&T Major Project (2014ZX03003003- 002), National High Technology Research, Development Program of China (2014AA01A704), National Natural Science Foundation of China (61201192), T singhua-Qualcomm Joint Research Program, Keysight Technologies, Inc., Key grant Project of Chinese Ministry of Education, ELLIIT and FP7-MAMMOET.

##License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.
