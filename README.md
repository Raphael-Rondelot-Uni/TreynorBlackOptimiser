# TreynorBlackOptimiser
This repository has two portfolio optimisers that use the Treynor Black Model. 

**Before continuing I would recommend watching some videos to understand what this optimiser is and what it does!**

TBO_Historical.ipynb is the first code file with a working optimiser. This file uses historical alphas, some may call this a backward looking model as it is assuming that past returns are the best indicator of future returns.

This file pulls data from the file All_Raw_Data.xlxs which contains monthly price data (09/30/2022 - 02/28/2026) for our 14 Equities, 6 Bond ETF's and our benchmark the ACWI.O. 

TBO_Predictive.ipynb is the second code file with a working optimiser, this file uses predictive alphas (These predictive alphas were obtained from LSEG Workspace), a forward looking model and assumes that predicted returns from analysts are the best indicator of future returns. 

This file also pulls data from the All_Raw_Data.xlxs and the LSEG_Pred_Alpha.xlxs file. You will need these downloaded and in the right location for these code files to work (I recommend using VS Code and opening your downloads folder). Additionally, If you want to use your data you have pulled from Bloomberg, LSEG Workspace or maybe Yfinance, you will need to edit those xlxs files but ensure they are in the same format.

If getting data is an inssue, drop me an email at: bn833979@student.reading.ac.uk or a message on LinkedIn: https://www.linkedin.com/in/raphaelrondelot/ and I can add a code file to this repo which pulls data in the right format for this files. You will just have to manually enter the ticker. 
