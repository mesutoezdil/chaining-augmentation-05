# Chaining Augmentation 05

## Project Description
This project is designed to fetch content from a specified website, chunk the content, and perform vectorization. It also integrates with a language model (LLM) to provide context-based answers to user queries.

## Features
- Fetch content from a specified website.
- Split content into chunks for processing.
- Vectorize text for similarity searches.
- Respond to user questions using context from the fetched content.

## Getting Started

### Prerequisites
- Go programming language installed on your machine.
- An API key for the PredictionGuard service, set in your environment as `PGKEY`.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mesutoezdil/chaining-augmentation-05.git
   cd chaining-augmentation-05
   ```

2. Initialize Go modules:
   ```bash
   go mod init chaining-augmentation-05
   ```

3. Install the required packages:
   ```bash
   go get github.com/JohannesKaufmann/html-to-markdown
   go get github.com/predictionguard/go-client
   ```

### Usage
Run the application and provide a website URL as a command-line argument:
```bash
go run main.go "http://example.com"
```

You can then interact with the application by typing your questions. Type "exit" to close the application.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements or suggestions.
