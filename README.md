# Correlation between Market Capitalizaion and Net Income of NASDAQ-100 companies

## What is the NASDAQ-100?
The NASDAQ-100 is probably the most well-known stock market index. It's made up of 100 of the largest non-financial companies that you probably heard of -  Amazon, Apple, Google, Intel, Starbucks, Pepsi, etc.
<br>
## What data are we using?
1. Market cap of all NASDAQ-100 companies during every quarter (ex: Q1 1986, Q2 1986... till Q2 2022)
2. Net income of all NASDAQ-100 companies during every quarter
Market cap means the market value of a company. It is calculated by multiplying the price of a stock by its total number of outstanding shares. For example, a company with 20 million shares selling at $50 a share would have a market cap of $1 billion. Net income is the pure amount of money a company has gained over a certain period of time (in our case, during a quarter). Net Income equals total revenues minus total expenses. We're trying to find if these two data have a strong correlation or not. We wanted to see the market cap value actually reflects the net income of these companies.
## How are we going to measure the correlation?
We will be calculating the Perason correlation coefficient to find out the correlation between the two data.

![image](https://user-images.githubusercontent.com/79275984/223246650-b04fa0ea-f809-4542-b35e-84ad97a2d780.png)

<img width="482" alt="image" src="https://user-images.githubusercontent.com/79275984/223246600-1e574a9b-184d-4bdd-9e4e-6ca75b08ce5f.png">
As the absolute value of r falls close to 1, it shows that the two quantitative variables establish a perfect positive or negative correlation. Below is a table that shows how strong the correlation is depending on the r value.
<br>
<img width="486" alt="image" src="https://user-images.githubusercontent.com/79275984/223255403-7a0cdac6-bb3a-4b69-ad56-b94204bfa181.png">
We will use the table as reference later once we get the results.<br>

## Analysis Results
### Comparing Market Cap & Net Income trends since 1985 (each "date" indicates a quarter):<br>
<img width="504" alt="image" src="https://user-images.githubusercontent.com/79275984/223258566-590c5f43-7285-494d-b6a0-6d1cc2e8a595.png">
The red line indicates the net income and the blue line indicates the market cap. We can see they are very similar movements between the two.

### Pearson Correlation between Market Cap & Net Income since 1985 (each dot indicates each quarter):<br>
<img width="466" alt="image" src="https://user-images.githubusercontent.com/79275984/223261085-1c59a368-faa8-4e5e-a0d8-568428a37889.png">
The dots draw a diagonally, linear shape - which indicates a positive correlation. Our Pearson r-value here was 0.94 which is a nearly perfect positive correlation. Square that value (0.94^2=0.89) and we can say in statistical terms, "the market cap value movement follows the movement of net income 89% of the time."
