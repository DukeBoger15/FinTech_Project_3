# FinTech Project 3
This repository contains the code for my FinTech Bootcamp Final Project
<h1>Background</h1>
<li>I am working for an financial planning and investment firm. We are exploring ways to show our clients data representations on investment portfolios that they could choose for retirement. We have a variety of different investment options and strategies. Using this code we will be able to take a portfolio of multiple holdings, and provide a client with multiple different approaches to their investment strategy.</li>
<h2>What I Am Creating</h2>
<li>For my project I will be implementing two coding files. One is a tool to optimize the portfolios and one is a tool to run Monte Carlo simulations to project the returns of the portfolios. Lets look at the portfolio optimization tool first.</li>
<li>The portfolio optimization tool takes multiple analytic tools to evaluate the portfolio holdings and provide recommendations based on the calculations of which ones to drop and which ones to keep. These analytic tools or calculations are the volatility, correlation, and sharpe ratios. By using these different tools or calculations we can then advise the client on what their goals and interests are. If the client is concerned with volatility we can run the code, find the highest volatility holdings and remove those creating a risk optimized portfolio. Using correlation if a client is concerned with being diversified and we calculate the correlation of the portfolio and most of the holdings are near positive one, they are closely correlated and the client is not as diversified as they thought allowing us to help create more diversification in the portfolio. Using the sharpe ratio we can view risk versus return and make changes according to the holdings that are not providing the reward to match the risk involved.</li>
<li>Next is the plannning tool code file. What we will use this code for is to take the portfolio from that we derived from the optimization tool for each client plug those in assign them weights and then use the monte carlo simulation tool to project what the returns and values of their portfolios would be over a set period of time. In this project I used a time period of 10 years. This is due to the younger age of the client and as a financial planner it creates opportunity for us to create a relationship, reevaluate the portfolio, and make changes anadjustments and then rerun the codes for analysis to implement the changes discussed.</li>
<h3>Technologies and Packages Used</h3>
<li>JuypterLab</li>
<li>Yahoo Finance as yfinance</li>
<li>pandas</li>
<li>seaborn as sns</li>
<li>MCForecastTools</li>
<li>Alpaca Trade API</li>
<li>datetime</li>
<h4>Usage</h4>
<li>To use these pieces of code, simply clone the repository, launch the JupyerLab and run each piece of code. To run the code, please use the rn tab at the top of the screen and select run all to run the entire code.</li>
<img width="393" alt="image" src="https://user-images.githubusercontent.com/113187706/224186894-1b404b4c-06b3-4431-bb5c-4437c3b87a70.png">
<h5>Results</h5>
<li>Using the portfolio optimization tool, we were able to evaluate the clients portfolio on a number of metrics. After taking our findings back to the client, they expressed to us that while they are considered an aggressive investor the volalitilty of their portfolio was concerning to them. As a result, we used our volalitity calculations and dropped the most volalitle holdings of the portfolio. Then we carried those over to the monte carlo simulation and ran 2 scenarios one using an equal weight to the portfolio and one using a 90/10 weight of equities to fixed income. After running the simulations we were able to show the client that using one of the two strategies would create the best chance for success.</li>
<img width="719" alt="image" src="https://user-images.githubusercontent.com/113187706/224187248-fa3f269f-7584-43d6-8dbb-05c005d09d01.png">
<img width="578" alt="image" src="https://user-images.githubusercontent.com/113187706/224187309-1697f0c0-e3da-41d1-a576-fdbee33a3196.png">
<img width="563" alt="image" src="https://user-images.githubusercontent.com/113187706/224187469-f0fbcba2-6975-417d-8c3f-e134985f3d0a.png">
