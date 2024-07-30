# OptionsApplication

### Statement of Problem
An options contract is a complex financial instrument that gives the right to investors to buy or sell an underlying asset at a certain price on a specific expiration date. An options contract is also a derivative product that requires some expertise to calculate the profit or loss when adding it to the investment portfolio. Knowing the estimate of the fair value of an option, investors could adjust their trading strategies and portfolios. However, many trading platforms and financial news providers give limited or unexplicit information about each past contract. In addition, for investors who are looking for advice on investing in options, the platforms and news providers do not provide the corresponding information. Therefore, in our project, we want to create an application for investors so that they can retrieve a visual representation of a single-option strategy. 

### Approach to the Problem
In this section, we will discuss our approach to solving the problem stated in the previous part. Figure 1 shows a general system design of the creation for the application. 
The scope of our project is to provide suggestions about an option on the stock at its expiration date. 

In order to provide a concise and clear result for the users, we first need to understand some basic concepts about options and explore different Python packages that best tailor the needs of the user. After doing research, we found the “yahoo_fin” package that supports us in retrieving relevant options information and “opstrat” package that allows us to graph the payoff diagrams for various strategies. Once we decided on the tools and general idea, we wrote a Python script to retrieve stock information, calculate option prices, and display the corresponding visualizations. Furthermore, we tested the code in the terminal to see whether Streamlit is feasible. Last but not least, when users open the webpage using the terminal, they can input the stock ticker, select strike price and expiration date, and get a profit/loss table and payoff diagrams with three strategies as a result. 

![image](https://github.com/user-attachments/assets/240491c5-8b62-46d0-96f6-289d78198a2b)

Figure 1: Web Application Architecture

### References 
- https://sanketkarve.net/automating-option-pricing-calculations/ 
- https://corporatefinanceinstitute.com/resources/derivatives/option-pricing-models
- https://docs.streamlit.io/library/get-started/installation 
- https://pypi.org/project/opstrat/ 

