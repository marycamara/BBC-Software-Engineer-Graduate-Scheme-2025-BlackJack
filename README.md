# BBC Software Engineer Graduate Scheme 2025 - Blackjack Game

A command-line Blackjack game implementation in Python, developed as part of the BBC Software Engineer Graduate Scheme 2025 pre-assessment.

##  Features

- Complete Blackjack game implementation with scoring system
- Support for multiple players (AI and human)
- Comprehensive unit testing suite

##  Prerequisites

- Python 3.10 or higher
- pip (Python package manager)

##  Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/marycamara/BBC-Software-Engineer-Graduate-Scheme-2025-BlackJack
cd BBC-Software-Engineer-Graduate-Scheme-2025-BlackJack
```

### 2. Set Up Environment

Activate virtual environment:

```bash
# On macOS/Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Game

```bash
python __main__.py
```

##  Testing

The project includes comprehensive unit tests to ensure game reliability. Tests cover:

- Hand scoring calculations (including Ace handling)
- Input validation and error handling
- Edge cases (e.g., empty deck scenarios)

Run tests using:

```bash
pytest
```

Run specific tests using:

```bash
pytest test_card.py
pytest test_deck.py
pytest test_game.py
pytest test_hand.py

```

## 🎥 Demo

Check out these demonstrations of the game in action:

Game Demo - See the gameplay in action

Test Suite - Watch the test suite execution
