# Loan Calculator

A simple, responsive web-based loan calculator that helps users calculate monthly payments and total interest for loans. Built with vanilla HTML, CSS, and JavaScript.

## 🚀 Live Demo

Visit the live application: [https://parthsharma30.github.io/project-loan-calculator/](https://parthsharma30.github.io/project-loan-calculator/)

## ✨ Features

- **Easy-to-use Interface**: Clean and intuitive design for quick calculations
- **Real-time Calculations**: Instant results as you input loan details
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Input Validation**: Ensures all fields contain valid numeric values
- **Detailed Results**: Shows both monthly payment amount and total interest

## 🛠️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- GitHub Pages (for hosting)

## 📊 What It Calculates

The calculator computes:
- **Monthly Payment**: The amount you'll pay each month
- **Total Interest**: The total interest you'll pay over the life of the loan

## 🔧 How to Use

1. Enter the **Loan Amount** (principal amount you want to borrow)
2. Input the **Interest Rate** (annual percentage rate)
3. Specify the **Loan Term** (number of months for repayment)
4. Click **Calculate** to see your results

## 💻 Local Development

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/ParthSharma30/project-loan-calculator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd project-loan-calculator
   ```

3. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

## 📁 Project Structure

```
project-loan-calculator/
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript logic
└── README.md           # Project documentation
```

## 🧮 Calculation Formula

The calculator uses the standard loan payment formula:

```
M = P * [r(1 + r)^n] / [(1 + r)^n - 1]
```

Where:
- M = Monthly payment
- P = Principal loan amount
- r = Monthly interest rate (annual rate ÷ 12)
- n = Total number of payments (loan term in months)

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🐛 Known Issues

- Minor typo in button text ("Caculate" instead of "Calculate")
- CSS border property syntax issue in `#result` selector

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Parth Sharma**
- GitHub: [@ParthSharma30](https://github.com/ParthSharma30)

## 🔮 Future Enhancements

- Add amortization schedule display
- Include loan comparison feature
- Add support for different payment frequencies
- Implement dark/light theme toggle
- Add currency formatting options