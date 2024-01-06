# RizzGPT and FashionGPT Web Service

RizzGPT and FashionGPT Web Service is a web application that allows users to upload videos to receive humorous or fashion-related descriptions and voiceovers. The project integrates OpenAI's GPT-4 for generating descriptions and their text-to-speech engine to produce voiceovers.

## Features

- RizzGPT Mode: Provides a humorous roast of the person in the video focusing on their fashion.
- FashionGPT Mode: Offers fashion advice in a friendly manner to the person in the video.
- Video Upload: Users can upload a video file to be processed.
- Voiceover Generation: Generates an audio file with the voiceover based on the GPT-4 descriptions.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js (at least version 14.x)
- npm (usually comes with Node.js)
- An API key from OpenAI

## Installation

Follow these steps to set up RizzGPT and FashionGPT Web Service on your local machine:

1. Clone the repository:
```sh
git clone [https://github.com/your-username/rizzgpt-fashiongpt-service.git](https://github.com/Arbaaz-Mahmood/Rizz-GPT.git)
```

2. Navigate to the project directory:
```sh
cd Rizz-GPT
```

3. Install the required npm packages:
```sh
npm install
```
### Install FFMPEG (if not already installed)

#### For Windows:

Download the FFMPEG binaries from https://ffmpeg.org/download.html and add the /bin folder to the system's PATH environment variable.

#### For macOS:

You can install FFMPEG using Homebrew:
```sh
brew install ffmpeg
```

#### For Linux:

You can install FFMPEG from the package manager:
```sh
sudo apt update
sudo apt install ffmpeg
```
4. Set your OpenAI API key in `index.js`:
```js
const openaiApiKey = `your-openai-api-key`;
```

5. (Optional) Customize configurations such as the port number in `index.js` if you have specific requirements or are deploying the service.

## Running the Application

To start the application, run the following command in the project directory:
```sh
npm start
```

By default, the server will start on `http://localhost:3000`. You can access the web application through any web browser by visiting this URL.

## Usage

Once the application is running, use it as follows:
- Select either the RizzGPT or the FashionGPT mode by clicking the corresponding button.
- Upload a video file by clicking the "Upload" button.
- Wait for the processing to complete. The progress will be indicated on the web page.
- Once processing finishes, you can listen to the generated voiceover directly on the web page or start a new upload.

## Contributing

Contributions, issues, and feature requests are welcome. 

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or comments about this project, please feel free to contact the maintainer via twitter DMs @hingumtringum or email at: am1381@student.london.ac.uk
