# TesterGPT

## Key Features and Target Users

The TesterGPT is a powerful tool designed to streamline test case generation and cater to the specific needs of software testers and quality assurance professionals. Here's why it's the ideal choice for them:

### Why Choose the TesterGPT?

- **Extended Character Limits:** Unlike ChatGPT, the TesterGPT supports larger inputs and extended character limits, allowing for comprehensive test case generation. Chunking the input ensures smooth operation even with larger files.
- **PDF and Text File Support:** Unlike ChatGPT, he application seamlessly imports documentation from PDF and text files, enabling users to work with their preferred formats efficiently.

### Target Users

Software testers and quality assurance professionals benefit greatly from the TesterGPT. It revolutionizes their test case generation process by providing:

- **Efficiency:** Automating the test case generation process saves valuable time and effort, allowing testers to focus on critical aspects of testing.
- **Comprehensive Coverage:** The application intelligently generates high-quality test cases, covering various scenarios and edge cases, ensuring thorough test coverage.
- **Productivity:** By streamlining workflows and reducing manual effort, the TesterGPT enhances productivity, enabling testers to deliver high-quality software products.

Discover the efficiency, coverage, and productivity boost offered by the TesterGPT. Experience a seamless test case generation process tailored to the needs of software testers and quality assurance professionals. Try it now and elevate your software testing endeavors.


## Data Collection and User Consent

By using the TesterGPT application, you acknowledge and consent to the collection of certain data for application metrics and debugging purposes. The data collected may include but is not limited to:

- IP address
- Location information
- Host hardware system information like operating system

This data is collected to help us understand the usage patterns of the application, improve its performance, and address any technical issues that may arise.

If you have any concerns about the data collection or would like more information about our data handling practices, please [contact us](mailto:compoundgrowthcoaching@gmail.com).

## Disclaimer: Data Law Compliance

While the TesterGPT is designed to comply with data protection laws in the United States, it is important to note that I assume no liability for the use of this application in jurisdictions outside the United States, such as the European Union (EU) or California, where specific data protection laws and requirements may apply.

If you choose to use the TesterGPT in regions governed by data protection laws different from those in the United States, it is your responsibility to ensure compliance with the applicable regulations. I strongly advise reviewing and understanding the local data privacy laws before using the application.

By using the TesterGPT, you acknowledge that you have been informed about the limitations regarding data protection regulations in specific jurisdictions and that you assume full responsibility for any legal consequences resulting from the use of the application in non-compliant areas.

Please consult legal professionals and adhere to the data protection laws of your respective jurisdiction to ensure compliance and mitigate any potential legal risks.


## Installation

1. Download the application executable file (`TesterGPT.exe`) from the designated source.

2. Obtain a trial license for the application by [contacting us](mailto:compoundgrowthcoaching@gmail.com).

3. Place the executable file in a desired location on your computer.

## OpenAI API Key

To run this application, you need to set up your OpenAI API key in the environment variables. Follow the steps below:

1. Sign up for an OpenAI account at [https://openai.com](https://openai.com) if you don't have one already.
2. Go to your OpenAI account dashboard and navigate to the API keys section.
3. Create a new API key or use an existing one.
4. Set the `OPENAI_API_KEY` environment variable on your system with your API key.

   - **Windows**: Open a Command Prompt as Administrator and run the following command:

     ```
     setx OPENAI_API_KEY "<your-api-key>"
     ```
   - **Mac/Linux**: Open a terminal and run the following command:
     ```
     export OPENAI_API_KEY="<your-api-key>"
     ```
   Make sure to replace `<your-api-key>` with your actual API key.

## Cost of Using GPT-3

Please note that using the GPT-3 language model for generating test cases incurs costs. The specific cost depends on factors such as the number of tokens processed by the model.

As of my last knowledge update in September 2021, the cost per token for the chosen GPT-3 model was $0.000016 / token. Please refer to the official OpenAI documentation or your OpenAI account dashboard for the most up-to-date pricing information.

As an example, I gave a 12MB PDF file as input to this tool and OpenAI charged me $0.03 to generate the test cases using this application. I don't collect this fee as it goes directly to OpenAI and is the cost for using their service.

## Usage

1. Before launching the application, make sure you have a Google account.

2. Double-click on the .exe file to launch the application.

3. A browser window will open, prompting you to authenticate with your Google account. Follow the authentication process and grant the necessary permissions. This step is required to access certain Google services.
   - If you are unable to authenticate using your Google account, please [email us](mailto:compoundgrowthcoaching@gmail.com) for further assistance.

4. Once the authentication process is complete, the application window will open, displaying an empty text area.

5. To input the documentation from which test cases will be generated, click on the "File" menu and select "Open." Choose a text file or PDF file containing the documentation. The contents of the file will be displayed in the text area.

6. Click the "Generate" button to initiate the test case generation process. The application will send the documentation to the GPT-3 model and generate test cases based on it.

7. The generated test cases will be displayed in the text area below the input documentation. Each test case will be labeled with a corresponding number.

8. If any errors occur during the process, error messages will be displayed.

9. Close the application when you are finished.

Please note that the goal is no additional Python libraries or dependencies need to be installed. The application is bundled as an executable file, eliminating the need for users to install any Python packages or set up a Python environment.

## License

This application is distributed with a license file that governs its usage and distribution. By using this application, you agree to the terms and conditions specified in the license file. To obtain a trial license for the application, please [contact us](mailto:compoundgrowthcoaching@gmail.com).