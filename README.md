This code develops a continuous-time real options model to evaluate investment decisions and optimal restart triggers under uncertainty during asset decommissioning. 
The model utilizes a Markov-chain approximation finite differences scheme to find the boundary line which shows when a Decision Maker should repair and restart a project once decommissioning has begun. 
There is also then an optimal restart trigger calculated for the mothballing phase where a project is paused, but decommission is yet to begin. 
The Davy Oil Field is used and it is shown that it is almost never optimal to repair and restart once decommission has begun, which is reflected in the common real world decision to keep large oil rigs idle for as long as possible.
The main 2D boundary calculation was optimized with numpy vectorisation. Other attempts with Numba were slower.
