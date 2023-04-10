# Video Summary Generator

This Python script allows users to generate a summary of any YouTube video 
by providing the video's URL. The summary is generated using an AI model, 
and the transcript of the video is fetched using the 
youtube_transcript_api.

# Prerequisites

To run this script, you need the following libraries installed:

    os
    dotenv
    youtube_transcript_api
    marvin (a custom library that contains the ai_fn decorator)

Additionally, an API key for OpenAI is required. This key should be stored 
in a .env file under the variable name MARVIN_OPENAI_API_KEY.

## How to Use

Ensure that you have a .env file in your project directory with the 
OpenAI API key stored as MARVIN_OPENAI_API_KEY.

Run the script using a Python interpreter.

When prompted, enter the URL of the YouTube video you want to 
summarize.

The script will fetch the transcript of the video and process it.

The summary of the video will be displayed on the screen.
