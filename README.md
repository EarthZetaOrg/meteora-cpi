# Meteora CPI

A solana swap token using meteora pool via cpi for calculating and analyzing Consumer Price Index (CPI) data.

# 👋 Contact Me

### 
Telegram: https://t.me/earthzeta
<div style="display:flex; justify-content:space-evenly">
    <a href="https://t.me/earthzeta" target="_blank"><img alt="Telegram"
        src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white"/></a>
    <a href="https://discordapp.com/users/339619501081362432" target="_blank"><img alt="Discord"
        src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>
    <a href="mailto:johncriswick25@gmail.com" target="_blank"><img alt="Email"
        src="https://img.shields.io/badge/Gmail-CE5753?style=for-the-badge&logo=gmail&logoColor=white"/></a> 
</div>

## Installation

```

## Features

- Calculate CPI using various methodologies
- Handle time series data for price indices
- Support for different base periods
- Flexible data input formats
- Statistical analysis tools for CPI components

## Quick Start

```python
from meteora_cpi import CPICalculator

# Initialize calculator
calculator = CPICalculator()

# Add price data
data = {
    'period': ['2022-01', '2022-02'],
    'prices': [100, 102],
    'weights': [0.6, 0.4]
}

# Calculate CPI
cpi = calculator.calculate(data)
print(f"CPI: {cpi}")
```

## Documentation

For detailed documentation, please visit [docs link].

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Project Link: [https://github.com/earthzetaorg/meteora-cpi](https://github.com/earthzetaorg/meteora-cpi)