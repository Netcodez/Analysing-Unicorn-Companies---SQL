# Analysing-Unicorn-Companies---SQL

## Analysing Unicorn Companies using SQL

### Investment Trends Analysis
Investment firms are constantly seeking insights into trends among high-growth companies to make informed decisions about their portfolios. Investment firms can leverage this information to gain a competitive edge in understanding industry trends and structuring their portfolios strategically. This project involves analyzing a PostgreSQL database containing information about unicorn companies, their valuations, funding, industries, and other relevant details.

### Database Structure
The PostgreSQL database consists of the following tables:

- **dates**
  - company_id: A unique ID for the company.
  - date_joined: The date the company became a unicorn.
  - year_founded: The year the company was founded.

- **funding**
  - company_id: A unique ID for the company.
  - valuation: Company value in US dollars.
  - funding: The amount of funding raised in US dollars.
  - select_investors: A list of key investors in the company.

- **industries**
  - company_id: A unique ID for the company.
  - industry: The industry in which the company operates.

- **companies**
  - company_id: A unique ID for the company.
  - company: The name of the company.
  - city: The city where the company is headquartered.
  - country: The country where the company is headquartered.
  - continent: The continent where the company is headquartered.

### Results
The SQL query results provide valuable insights into the trends among high-growth companies (unicorns) across different industries for the years 2019, 2020, and 2021. Here's an interpretation of the key information:

#### Industries with the Highest Number of Unicorns:
**E-commerce & Direct-to-Consumer:**
- In 2019, there were 12 unicorn companies in this industry.
- In 2020, the number increased to 16.
- By 2021, there are 47 unicorn companies.

**Fintech:**
- 2019 saw 20 unicorn companies in the fintech sector.
- In 2020, the number remained high at 15.
- However, in 2021, there is a significant surge to 138 unicorn companies, indicating substantial growth in this industry.

**Internet Software & Services:**
- In 2019, there were 13 unicorn companies in this industry.
- The number increased to 20 in 2020.
- In 2021, it remains a strong industry with 119 unicorn companies.

#### Average Valuation (in Billions) of Unicorn Companies:
**Fintech:**
- Fintech companies had the highest average valuation of $6.80 billion in 2019.
- In 2020, the average valuation was $4.33 billion.
- In 2021, it decreased to $2.75 billion, but it remains a lucrative industry.

**Internet Software & Services:**
- This industry had a notable average valuation of $4.23 billion in 2019.
- In 2020, the average increased to $4.35 billion.
- By 2021, the average valuation decreased to $2.15 billion, but it continues to be a significant player.

**E-commerce & Direct-to-Consumer:**
- E-commerce had an average valuation of $2.58 billion in 2019.
- In 2020, the average increased to $4.00 billion.
- By 2021, the average valuation slightly decreased to $2.47 billion.

#### Key Observations:
- **Fintech Dominance:** Fintech emerged as a dominant industry in terms of the number of unicorn companies and high average valuations. The significant increase in the number of fintech unicorns in 2021 suggests a robust and growing sector.

- **Internet Software & Services Stability:** While the number of companies in this industry increased, the average valuation remained relatively stable. It indicates a consistent presence and valuation within this sector.

- **E-commerce & Direct-to-Consumer Growth:** The e-commerce industry witnessed substantial growth in the number of unicorn companies, particularly in 2021. Despite a slight decrease in average valuation, the industry remains dynamic.

These insights are crucial for investment firms, providing a comprehensive understanding of industry trends and assisting in strategic decision-making for portfolio structuring.
