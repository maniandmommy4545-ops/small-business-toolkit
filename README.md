# Small Business Toolkit

A polished, private-use collection of **20 practical mini apps** for everyday small-business work. It is designed for people of all skill levels, with plain-language instructions, helpful field descriptions, responsive navigation, and local data storage.

## The 20 Tools

### Money and Pricing

1. **Sales Tax Calculator** - Adds a sales-tax percentage to a subtotal.
2. **Markup and Margin Calculator** - Calculates selling price, gross profit, markup, and margin.
3. **Profit Calculator** - Compares revenue with expenses and reports profit or loss.
4. **Discount Calculator** - Calculates customer savings and the final sale price.
5. **Break-Even Calculator** - Estimates how many units must be sold to cover fixed costs.
6. **Loan Payment Estimator** - Estimates monthly payment, total repayment, and interest.
7. **Cash Flow Snapshot** - Calculates net cash flow and estimated ending cash.

### Sales and Customers

8. **Quote Builder** - Creates a clear printable customer quote.
9. **Invoice Builder** - Creates a printable invoice with an invoice number and due date.
10. **Receipt Maker** - Creates a printable payment receipt.
11. **Customer Contact List** - Stores names, phone numbers, email addresses, and notes locally.
12. **Follow-Up Message Writer** - Drafts quote follow-ups, reminders, thank-you notes, and review requests.

### Operations and People

13. **Inventory List** - Tracks stock quantity, reorder level, SKU, and unit cost.
14. **Timesheet Calculator** - Calculates worked hours after an unpaid break and estimates pay.
15. **Payroll Estimator** - Estimates regular pay, overtime, deductions, and net pay.
16. **Mileage Log** - Records business trips and calculates their mileage value.
17. **Meeting Agenda Builder** - Creates an organized agenda with attendees and action items.

### Productivity

18. **Task List** - Stores tasks with due dates, priorities, and completion status.
19. **Quick Notes** - Automatically saves notes on the current device.
20. **Focus Timer** - Runs a simple work-session countdown.

## How to Use It

1. Open `index.html`, or start the desktop edition with `npm start`.
2. Use the left menu or search box to find a tool.
3. Read the short explanation and numbered instructions shown above each tool.
4. Enter your information and select the main action button.
5. Review the result. Printable documents include **Print / Save PDF** and **Copy** buttons.
6. Lists and notes save automatically on the current device.
7. Use **Settings** to choose your currency and business name.
8. Use **Backup Data** and **Restore Data** to move saved local records between devices.

## Privacy and Local Data

The app works locally and does not send business information to an external server. Saved contacts, inventory, mileage, tasks, settings, and notes remain in the app's local browser storage.

Back up important data regularly. Clearing browser or application data can erase locally stored records. Do not use the app for passwords, payment-card details, government identifiers, health information, or other highly sensitive data.

## Run in a Browser

Download the repository and open `index.html` in a current browser. No server or package installation is required.

```bash
git clone https://github.com/maniandmommy4545-ops/small-business-toolkit.git
cd small-business-toolkit
```

## Run as a Desktop App

Install a current Node.js release, then run:

```bash
npm install
npm start
```

Create a Windows installer with:

```bash
npm run build:win
```

The generated installer is placed in `dist/`. An unsigned installer may trigger a Microsoft Defender SmartScreen warning. Public distribution should use a trusted code-signing certificate.

## Project Files

```text
small-business-toolkit/
├── index.html       # Complete web application
├── package.json     # Desktop scripts and packaging settings
├── electron-main.js
├── LICENSE          # Private proprietary-use terms
├── README.md
└── .gitignore
```

## Compatibility

- Windows, macOS, and Linux desktop browsers
- Recent Chrome, Edge, Firefox, and Safari releases
- Responsive layouts for tablets and phones
- Electron desktop packaging for Windows

## Important Limitations

This toolkit provides general estimates and organizational aids. It is not accounting, tax, payroll, legal, lending, or financial advice. Tax, payroll, mileage, overtime, interest, and recordkeeping rules vary by location and situation. Verify important calculations with a qualified professional.

## License

**Private and proprietary. All rights reserved.** See `LICENSE`. No permission is granted to copy, modify, redistribute, sell, sublicense, publish, or publicly host this software without the copyright holder's prior written permission.

## Author

Created and maintained by [maniandmommy4545-ops](https://github.com/maniandmommy4545-ops).
