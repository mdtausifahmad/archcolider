Date: 2020-10-31

## Status

Proposed

## Context

A subscribed user/occasional user would like to reserve and pay the meal by different payment method available in the system.

## Decision
We will build a payment gateway which integrates with Visa/Mastercard, PayPal and AmzonPay and gives flexible option for the user to choose.

## Consequences

Positive: The Payment will be accepted and user will be able to reserve the meal
Negative: The payment may gets rejected or void and user will not be able to reserve the meal
Risks: Need to be careful while processing the card details from user, as there is a chance of Fraud 
