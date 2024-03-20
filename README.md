# Pregnancy Calculator API

![Cover Photo](assets/cover.png)

## ✨ Overview

Welcome to the Pregnancy Calculator API! This API provides endpoints for calculating various aspects related to pregnancy, including the Fertility Window, Pregnancy Due Date, Pregnancy Week, and Pregnancy Weight Recommendation. With this API, you can easily integrate these calculations into your applications, websites, or any other projects.

## 🚀 Features

- **Fertility Window Calculation:** Calculate the fertility window based on menstrual cycle length and date.
- **Pregnancy Due Date Prediction:** Predict the due date of pregnancy based on the last menstrual period or conception date.
- **Pregnancy Week Estimation:** Estimate the current week of pregnancy based on the last menstrual period or conception date.
- **Pregnancy Weight Recommendation:** Calculate recommended pregnancy weight based on pre-pregnancy weight, height, and gestational age.

## 🏁 Getting Started

To get started, you need to subscribe to the API on RapidAPI. Visit [Pregnancy Calculator API on RapidAPI](https://rapidapi.com/kidddevs/api/pregnancy-calculator-api) and subscribe to start using the API in your projects.

## ⚡️ Usage Examples

### Fertility Window:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/fw?cycle_length=28&menstrual_date=2023-06-01' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY' 
```	

### Pregnancy Due Date:

- By Last Menstrual Period:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/dd/lmp?last_period_date=2023-01-01&cycle_length=28' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```

- By Conception Date:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/dd/conception?conception_date=2023-05-01' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```

### Pregnancy Week:

- By Last Menstrual Period:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/pw/lmp?last_period_date=2023-01-01&cycle_length=28' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```

- By Conception Date:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/pw/conception?conception_date=2023-05-01' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```

### Pregnancy Weight Recommendation:

```bash
curl --request GET \
	--url 'https://pregnancy-calculator-api.p.rapidapi.com/pwr?pre_pregnancy_weight=60&height=1.65&gestational_age=20' \
	--header 'X-RapidAPI-Host: pregnancy-calculator-api.p.rapidapi.com' \
	--header 'X-RapidAPI-Key: SIGN-UP-FOR-KEY'
```	
## 🔨 Issues

If you encounter any issues or have suggestions for improvements, please feel free to [open an issue](https://github.com/dakidarts/pregnancy-calculator-api/issues) on GitHub.

## ⚖️ License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/dakidarts/pregnancy-calculator-api?tab=MIT-1-ov-file#) file for details.

## 🌍 Follow Us

- Website: [www.dakidarts.com](https://dakidarts.com/)
- Twitter: [@dakidarts](https://twitter.com/dakidarts)
- Facebook: [@dakidarts](https://www.facebook.com/dakidarts)
- LinkedIn: [company/@dakidarts](https://www.linkedin.com/company/dakidarts)
