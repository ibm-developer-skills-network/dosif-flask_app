# Flask Transaction Application
This is a simple Flask application that allows users to manage transactions. It provides basic CRUD (Create, Read, Update, Delete) operations for transactions. Users can view a list of transactions, add new transactions, edit existing transactions, and delete transactions.
![ezgif com-video-to-gif](https://github.com/ibm-developer-skills-network/flask_app/assets/90204593/a7bb7b33-be64-44e9-9982-69ba522917f4)


## Installation
1. Clone the repository:
```
git clone https://github.com/ibm-developer-skills-network/flask_app.git
```

2. Navigate to the project directory:
```
cd flask_app
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```
The following dependencies will be installed:

Flask==2.3.2

Flask_Testing==0.8.1

## Usage
1. Run the Flask application:

```
flask run
```
The application will be accessible at http://localhost:5000.

2. The following routes are available:

/: View a list of all transactions.

/add: Add a new transaction.

/edit/<transaction_id>: Edit an existing transaction.

/delete/<transaction_id>: Delete a transaction.

3. To run the tests, execute the following command:
```
python test.py
```
The test results will be displayed in the console.

## License
This project is licensed under IBM Skills Network.
