# credit-scoring-project
Credit Scoring Model with Machine Learning

# Credit Scoring Application

## Overview
This is a full-stack credit scoring application that uses machine learning to predict an individual's creditworthiness based on various financial parameters.

## Technology Stack
- **Backend**: Python, Flask, Scikit-learn
- **Frontend**: React, Tailwind CSS, Shadcn UI
- **Machine Learning**: Random Forest Classifier

## Features
- Predict credit worthiness
- Dynamic feature input
- Model training capabilities
- Responsive and intuitive UI
- Synthetic data generation

## Project Structure
- `backend/`: Flask application with credit scoring model
- `frontend/`: React application with modern UI components

## Setup and Installation

### Backend Setup
1. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the Flask server
```bash
python app.py
```

### Frontend Setup
1. Install dependencies
```bash
npm install
```

2. Run the development server
```bash
npm start
```

## How It Works
The application uses a Random Forest Classifier to predict credit worthiness based on:
- Annual Income
- Credit History Length
- Number of Credit Cards
- Total Debt
- Payment Consistency
- Age

## Model Training
The model uses synthetic data generation with predefined rules to simulate credit scoring scenarios.

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License
MIT License

## Disclaimer
This is a demonstration project using synthetic data and should not be used for actual credit decisions.
