# Order Processing & Inventory Automation

I built and tested this workflow from start to finish.

I built this n8n workflow to handle incoming orders, check product availability, update inventory, and notify the customer or team about the order status.

<img width="779" height="238" alt="Order Processing and Inventory workflow demo" src="https://github.com/user-attachments/assets/541f2693-2fe2-4e16-8979-b07dc9c7839d" />

## How it works

1. A customer submits a new order through a form.
2. The workflow checks the available quantity in Google Sheets.
3. If the stock is available, it updates inventory and records the order.
4. The customer receives an email confirmation.
5. If the stock is insufficient, the workflow sends a Telegram alert.

## Technologies

n8n, Google Sheets, Gmail, Telegram, and JavaScript.

## Setup

Import [workflow.json](./workflow.json) into n8n, connect your form, Google Sheets, Gmail, and Telegram credentials, then set your inventory sheet and order details.
