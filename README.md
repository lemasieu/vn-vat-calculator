# VN VAT Calculator

A simple, interactive web tool that calculates Value Added Tax (VAT) for goods and services in Vietnam. It supports both forward calculation (adding VAT to a base price) and reverse calculation (extracting VAT from a total price).

## 🚀 Live Demo

Check out the live demo: [https://www.xn--msiu-goa8b.vn/github/vn-vat-calculator](https://www.xn--msiu-goa8b.vn/github/vn-vat-calculator)

## ✨ Features

- **Forward Calculation** – Add VAT to a pre-tax price to get the total amount
- **Reverse Calculation** – Extract VAT from a VAT-inclusive price to find the base price and tax amount
- **Multiple Tax Rates** – Supports the some popular tax rates
- **Real-Time Results** – See the calculation instantly as you type
- **Clear Breakdown** – Displays the base price, VAT amount, and total price separately
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📁 Project Structure

```
vn-vat-calculator/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript calculation logic
└── README.md       # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/vn-vat-calculator.git
   ```
2. **Navigate to the project folder**   
   ```bash
   cd vn-vat-calculator
   ```
3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

## 📝 How It Works

1. **Choose the calculation direction** – Select whether you want to:
   - **Add VAT (Forward)** – Enter a pre-tax price to calculate the total price including VAT
   - **Extract VAT (Reverse)** – Enter a VAT-inclusive price to calculate the base price and the VAT amount
2. **Enter the amount** – Type the price (in VND) into the input field
3. **Select the VAT rate** – Choose the applicable rate
4. **View the results** – The tool displays:
   - Pre-tax price (Giá chưa VAT)
   - VAT amount (Tiền thuế VAT)
   - Total price (Tổng thanh toán)

### Formula:

- Forward: `VAT = Pre-tax Price × (Rate / 100) and Total = Pre-tax Price + VAT`
- Reverse: `Pre-tax Price = Total / (1 + Rate / 100) and VAT = Total - Pre-tax Price`

### Example:

- Pre-tax price: 32,000,000 VND at 10% VAT
- VAT amount: 3,200,000 VND
- Total price: 35,200,000 VND

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is open-source and available under the MIT License.
