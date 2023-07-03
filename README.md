# cliGPT

A command-line interface (CLI) tool built with Go that allows users to interact with ChatGPT, a powerful language model developed by OpenAI. This tool utilizes modules like Cobra, Viper, and [go-gpt3](https://github.com/PullRequestInc/go-gpt3) to provide an intuitive and efficient way to communicate with ChatGPT.<br><br>
The directory strcuture is as follows:

- `main.go`: The entry point of the CLI tool, containing the main function and command execution logic.
- `response.go`: The file that defines the `getResponse` function, responsible for interacting with the ChatGPT API.


## Prerequisites

Before running cliGPT, make sure you have the following prerequisites:

- Go programming language installed (version 1.16 or higher)
- An OpenAI API key for ChatGPT
- Git installed (for dependency management)

## Installation

1. Clone the repository:
   ```shell
   git clone https://github.com/RishabhKodes/cliGPT.git
   cd cliGPT
   ```

2. Create a `.env` file in the root directory and add your OpenAI API key:
   ```shell
   echo "API_KEY=YOUR_API_KEY" >> .env
   ```

3. Build the project:
   ```shell
   go build .
   ```
   This will create a `cliGPT` executable in the same directory that will be used to run the CLI tool.

## Usage

To use the ChatGPT CLI tool, follow these steps:

1. In the root directory of the project, run the CLI tool with the following command:
    ```shell
    ./cliGPT
    ```
1. The CLI tool will prompt you to enter a question or command. Type your input and press Enter.

2. The ChatGPT CLI tool will communicate with the ChatGPT API and provide a response based on your input.

3. To exit the CLI tool, type `quit` and press Enter.

<br>

<!-- CONTRIBUTING -->
## Contributing

Contributions make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<br>
<br>

<!-- CONTACT -->
## Contact Me

[Website](https://rishabhbhandari.me/)
[LinkedIn](https://www.linkedin.com/in/rishabh-bhandari-ba5778168/)
[Email](rishabhbhandari6@gmail.com)
