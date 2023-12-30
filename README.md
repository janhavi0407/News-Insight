# News-Insight
A news summarizer

# News Summarizer

![Screenshot (297)](https://github.com/janhavi0407/News-Insight/assets/100830653/b28c244e-c042-4d09-85ee-5abc40924a1a)


## Overview

The News Summarizer is a Python application designed to simplify the process of fetching, summarizing, and analyzing news articles from URLs. Built using the Tkinter graphical user interface framework, the application provides users with a user-friendly interface to interact with.

## Features

1. **Article Summarization**: Users can input the URL of a news article they wish to summarize. The application uses the `newspaper` library to download and parse the article's content. It then generates a concise summary of the article, which is displayed in the summary text field.

2. **Metadata Display**: The application extracts metadata from the article, including the title, author, and publishing date. These details are presented to the user in separate read-only text fields, offering quick insights into the article's context.

3. **Sentiment Analysis**: Leveraging the power of the `TextBlob` library, the application performs sentiment analysis on the article's content. The sentiment analysis result includes a polarity score and a sentiment classification (positive, negative, or neutral), which are displayed in a dedicated text field.

4. **User-Friendly Interface**: The graphical user interface (GUI) is built using Tkinter, a standard Python library for GUI development. The interface is designed to be clean and intuitive, allowing users to easily input URLs, trigger summarization, and access the generated results.

5. **Read-Only Fields**: The application uses read-only text fields with a gray background to display extracted information. This ensures that users can easily view the results without accidentally modifying them.

## How to Use

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `news_summarizer.py` script using Python.
4. Enter the URL of the news article you want to summarize in the "URL" text field.
5. Click the "Summarize" button to initiate the summarization process.
6. The application will display the title, author, publishing date, summary, and sentiment analysis results in their respective text fields.

## Dependencies

The application relies on the following libraries:

- `tkinter`: Python's standard GUI library for building the graphical interface.
- `nltk`: Natural Language Toolkit library for natural language processing tasks.
- `newspaper`: A Python library for web scraping and article extraction.
- `textblob`: A library for processing textual data, including sentiment analysis.

## Future Enhancements

1. **Multi-URL Summarization**: Enable users to summarize multiple articles in one session.
2. **Customizable Summaries**: Allow users to customize the length of the generated summary.
3. **Export Functionality**: Implement options to export summarized content and analysis results.
4. **Graphical Sentiment Visualization**: Incorporate graphical visualization of sentiment analysis results.
5. **Interactive Web Application**: Transform the desktop application into a web-based tool for broader accessibility.

## Contribution

Contributions are welcome! If you have ideas for improvements, enhancements, or new features, feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---


