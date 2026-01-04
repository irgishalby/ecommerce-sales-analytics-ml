# E-Commerce Pricing Health Inspection

## Project Goal

I started this project to understand whether a product’s price is actually reasonable when compared to the market. In e-commerce, pricing often relies on intuition or static rules, so my original idea was to build a system that could look at competitor prices and tell me if a product was overpriced, underpriced, or priced fairly.

## How I Approached the Problem

Rather than focusing on raw prices, I focused on *positioning*. A low price does not always mean a good price, and an expensive item is not automatically overpriced. I decided to compare our price against the broader market by measuring how far it deviated from the typical competitor price. This allowed me to think in terms of pricing behavior instead of price magnitude.

Before modeling anything, I spent time cleaning and preparing the data so that prices and weights were consistent and usable. After exploring the data, I realized that most products were priced very close to the market average, with very little variation between platforms. Because of this, the original three-class idea was not realistic, and I reframed the task into a simpler question: **Is the price healthy or not?**

## Outcome and What I Learned

The final model performed perfectly on evaluation, not because it was especially powerful, but because nearly all products in the dataset were already priced within a healthy range. This result highlighted an important lesson for me: sometimes the most valuable insight is realizing that a dataset does not support aggressive optimization or prediction.

This project helped me learn how to validate a business problem before forcing machine learning onto it, and how to adjust goals based on what the data can realistically answer. It reflects my learning process and my focus on making data-driven decisions honestly, rather than chasing complex
