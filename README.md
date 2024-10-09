# Trello Categorization Automation

This project automates the categorization of Trello cards based on their names and labels. It is designed to help teams efficiently organize and prioritize tasks on their Kanban boards and product roadmaps.

## Features

- **Automated Categorization**: Automatically categorize Trello cards into predefined categories such as "High Priority", "Current Development", and "Future Features" based on labels and keywords in card names.
- **Real-time Updates**: Continuously update categories as new cards are added or existing cards are modified.
- **Customizable Rules**: Easily adjust categorization logic to fit your team's workflow and priorities.

## Installation

1. **Clone the Repository**:
   
   git clone https://github.com/yourusername/trello-categorization-automation.git
   cd trello-categorization-automation
   
2. Install Dependencies:
   Ensure you have Python installed, then install required packages:
   pip install -r requirements.txt

3. Set Up Environment:
  Create a .env file to store your Trello API key and token:
  
  TRELLO_API_KEY=your_api_key
  TRELLO_TOKEN=your_token

## Usage
1. **Run the Script**:
  Execute the main script to start categorizing cards:

  python categorize_cards.py

2. **View Results**:
The script will output categorized cards to the console or save them to a specified file for further analysis.

## Customization
Modify the categorize_cards.py script to change categorization rules based on your team's needs.
Adjust label names and keywords in the script to match your Trello board's setup.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Questions or Feedback?
If you have any questions or feedback, please open an issue on GitHub or contact me directly at jamesdlee77@gmail.com
