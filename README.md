# Matrixx CLI Bot

A production-ready Matrix bot using `matrix-nio`, implementing the Command Pattern and asynchronous event loop.

## Features
- **Command Pattern**: Easy to extend with new commands.
- **Asynchronous**: Built on `asyncio` for high performance.
- **Secure**: Uses `.env` for credential management.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kernelpanic700/matrixx-cli-bot.git
   cd matrixx-cli-bot
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Configuration

Create a `.env` file in the root directory:
```text
MATRIX_HOMESERVER=https://matrix.org
MATRIX_USER_ID=@your_bot:matrix.org
MATRIX_PASSWORD=your_password_here
```

## Running the Bot

```bash
python bot.py
```
