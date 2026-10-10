# AI Image Generator

An AI-powered image generation web application that turns text prompts into images using the Hugging Face Inference API. Users can describe an image they want to create and submit the prompt to an AI image generation model.

🔗 **Live Demo:** https://cheerful-flan-f7ff5b.netlify.app/

## Features

* Generate images from text prompts
* Connect to an AI image generation model through the Hugging Face Inference API
* Simple prompt input interface
* Display generated images
* Loading and error feedback during generation
* Responsive user interface

*Features may vary depending on the current implementation.*

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Hugging Face Inference API

## How It Works

1. The user enters a descriptive text prompt.
2. JavaScript sends the prompt to the configured Hugging Face Inference API endpoint.
3. The selected image generation model processes the prompt.
4. The application receives the generated image and displays it to the user.

## Getting Started

### Prerequisites

* A modern web browser
* A Hugging Face account and API access, if required by your chosen model
* A Hugging Face access token with the appropriate permissions, if required

### Run Locally

1. Clone this repository:

   ```bash
   git clone [https://cheerful-flan-f7ff5b.netlify.app/]
   ```

2. Open the project folder in Visual Studio Code.

3. Configure the model endpoint and API authentication according to your implementation.

4. Run the application using the Live Server extension or your configured local development server.

## Environment Variables and API Security

If your application requires a Hugging Face access token, **do not commit the token to GitHub or expose it in frontend JavaScript**. Browser-based applications cannot securely hide API secrets.

For a public deployment, use a backend server or serverless function to store the token securely and make authenticated API requests. Keep secret values in environment variables.

## What I Learned

* Integrating a third-party AI API
* Working with asynchronous JavaScript and `async/await`
* Sending HTTP requests using `fetch()`
* Handling API responses and errors
* Displaying generated image results
* Understanding API authentication and secret management

## Future Improvements

* Add image dimensions and generation settings
* Display generation progress and clearer error messages
* Allow users to download generated images
* Improve prompt guidance and the user experience
* Add secure backend-based API authentication

## Author

**Amish Ban**

* GitHub: [@amishban7](https://github.com/amishban7)
* Portfolio: [amishban7.github.io/Portfolio](https://amishban7.github.io/Portfolio/)

---

*Built as a practical project exploring frontend development and AI integration.*
