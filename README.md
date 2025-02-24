# text_to_image

Text-to-Image Generation using MonsterAPI

Overview

This project uses MonsterAPI to generate images from text prompts. The tool takes a user-defined text description (prompt) and creates highly detailed images using AI-powered models. The generated images are downloaded and displayed using PIL (Pillow).

Features

Generates images based on a text description.

Allows customization with negative prompts, guidance scale, and sampling steps.

Downloads the generated image automatically.

Displays the image using the PIL library.

Technologies Used

Python

MonsterAPI (for AI image generation)

Requests (for downloading images)

PIL (Pillow) (for opening and displaying images)

How It Works

Initialize the API Client: Connect to MonsterAPI using an API key.

Set Up Model Parameters:

Define the text prompt and negative prompt.

Choose the number of images, resolution, and sampling steps.

Generate Image: Send the request to MonsterAPI.

Download and Save the Image: Retrieve the generated image URL and save it.

Display the Image: Open the downloaded image using PIL.
