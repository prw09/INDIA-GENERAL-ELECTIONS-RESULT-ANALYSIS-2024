![Screenshot 2024-09-25 123048](https://github.com/user-attachments/assets/25bb4787-2fc4-44d8-b677-fb86755f9018)

# 📊 **India Elections 2024 - SQL Analysis**

## 🚀 **Project Overview**  
This project offers an in-depth analysis of the India Elections 2024 using SQL queries. It covers various aspects of the election data, focusing on constituency-level and state-level results, party performance, and voting trends. Through optimized SQL queries, the project provides a detailed breakdown of seats won, party alliances, candidate performances, and vote distribution (EVM and postal).

The queries help identify trends and offer insights into how major political alliances like NDA and I.N.D.I.A fared across states.

## 📝 **Key Features & Analysis**

- **Nationwide & Statewide Seat Analysis**:
  - Determine the total number of seats contested in India and in each state.
  - Identify the state-wise seat distribution for political alliances.
  
- **Alliance Performance Insights**:
  - Measure seat wins for major alliances like NDA and I.N.D.I.A.
  - Identify which alliance won the most seats across all states and constituencies.
  
- **Candidate Performance & Vote Margins**:
  - Analyze the winning candidates, their party affiliations, and their margin of victory by state and constituency.
  - Identify the top-performing candidates based on EVM votes and postal votes.
  
- **EVM vs Postal Voting Patterns**:
  - Breakdown of EVM and postal votes for candidates within a constituency.
  - Explore voting trends to understand differences in support through EVM and postal votes.

## 📁 **Project Structure**  
The analysis consists of multiple SQL queries covering key election data areas:

- **Constituency-wise Results**: Information on winning candidates, parties, and vote counts.
- **State-wise Results**: Aggregated results showing total seats won by parties in each state.
- **Party-wise Results**: Breakdown of the performance of each political party, including total seats won and vote shares.
- **States Table**: Contains metadata about Indian states, facilitating easy linking to election results.

## 🛠️ **Technologies Used**

- **Database Management System**: Microsoft SQL Server
- **Concepts Utilized**:
  - SQL JOINs for linking multiple tables.
  - Aggregation Functions such as `SUM`, `COUNT`, and `MAX`.
  - Window Functions and Subqueries to rank candidates and calculate vote margins.
  - String Functions for data cleaning and transformation.
  - Conditional Logic to classify party alliances like NDA, I.N.D.I.A, and OTHER.
  
- **Tools**: MySQL Workbench or any SQL Client (e.g., DBeaver, HeidiSQL).

## 📊 **SQL Queries & Key Insights**

- **Total Seat Calculation**:  
  SQL queries to calculate the total seats in India and state-wise seat allocation for the 2024 elections.
  
- **Alliance Seat Wins**:  
  Queries that aggregate the seats won by alliances NDA, I.N.D.I.A, and OTHER in each state and nationwide.
  
- **Top Candidates**:  
  Identify the candidates who received the highest number of EVM votes and postal votes.
  
- **Vote Distribution**:  
  Breakdown of votes cast through EVM and postal ballots in a specific constituency, allowing a detailed analysis of voting behavior.
  
- **Winning Margin & Runner-Up**:  
  Fetch the winner and runner-up from each constituency, along with their vote margins.

## 🔧 **Usage Instructions**

- **Set Up Database**:
  - Import the SQL schema and dataset provided in the repository into your Microsoft SQL Server database.
  
- **Run Queries**:
  - Execute the SQL queries to extract the insights. Queries are designed to be modular, allowing for custom filters based on states, constituencies, or alliances.
  
- **Customize**:
  - Modify the queries to target specific regions or parties based on your analytical needs.

## 📝 **Key Highlights of the Project**

- **Comprehensive Analysis**: Covers a broad spectrum of election results, from national to constituency levels.
- **Optimized for Performance**: Efficient SQL queries with proper indexing, filtering, and aggregation techniques for faster execution.
- **Actionable Insights**: Provides clear insights on party performances, voting trends, and candidate-level data, which could be valuable for political analysis or research.
- **Flexible**: Easy-to-modify queries to suit different analytical needs or future election data.

## 📊 **Potential Applications**

- **Political Analytics**: Understanding party performance, alliances, and voter patterns.
- **Media & Journalism**: Generating insights and visualizations for election reporting.
- **Research & Policy Making**: Informing data-driven political strategies and policy formulation.

## 🧑‍💻 **Contributors**  
Piyush Wandile  
(Feel free to contribute if necessary)
