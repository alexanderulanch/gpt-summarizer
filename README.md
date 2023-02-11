# GPT3 Summarizer

This Python script leverages the OpenAI GPT-3 language model to generate summaries for large text files that would otherwise exceed GPT-3's maximum input size. By splitting the input file into smaller chunks and summarizing each chunk individually, the script is able to generate a complete summary for the entire file. The resulting summary is more comprehensive than what is possible with GPT-3 alone, and it can be easily customized to fit your specific needs.

## Requirements

- Python 3.x
- An OpenAI API key

## Installation

1. Clone this repository to your local machine.
2. Install the required Python packages by running `pip install -r requirements.txt`.
3. Set the `OPENAI_API_KEY` environment variable to your OpenAI API key.

## Usage

1. Open the `summarize_text.py` file and modify the `filename` and `chunk_size` variables to fit your needs.
2. Run the script using `python summarize_text.py`.
3. The script will output the final summary to the console and write it to a file named `output.txt`.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

If you have any questions or feedback, please contact Alex Ulanch at alexulanch@gmail.com.
