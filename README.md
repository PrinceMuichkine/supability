# Supability
The open-source expense and revenue tracker for small businesses.

## How to use it locally
1. Clone the project 
2. In the backend folder run this command:
```./pocketbase serve``` You may need to change the file in the backend folder if you are using MacOS or Windows, see the [`Pocketbase doc`](https://pocketbase.io/docs/).
3. Run ```pnpm install``` in the app folder
4. Create a .env file in the app folder
5. ```pnpm run dev```

This project was created to assist developers who want to start a business but don't have the budget for accounting software. This app can serve as a valuable starting point for organizing your expenses and revenue. Additionally, you can add more functionalities as needed.

## TODO
- Export transactions to Excel format
- Pre-fill fields on PDF imports
- Include administration code on labels for tax reports
- Automatically import your Stripe transactions with one click
- Import invoices from Gmail or Outlook
- Create tax presets based on your country and/or state
- Capture photos of receipts