
## Description

Clarity is a tool designed to analyze tweets and provide insights into content reliability, bias, and potential propaganda. It helps users navigate social media with a clearer understanding of the narratives they encounter. Whether it's news, opinions, or discussions, Clarity delivers a more informed, balanced perspective, promoting a healthier digital environment.

By offering diverse viewpoints, Clarity empowers users to critically engage with content and reduce the impact of misinformation. From trending topics to everyday browsing, it equips users to make informed decisions about the information they consume.

## Features

* **Perspective**: Generates an opposing viewpoint using APIs, giving users a broader context for the information presented.
* **Propaganda Rating**: Uses advanced APIs to detect and rate the level of propaganda in a tweet, helping users gauge the trustworthiness of the content.
* **Reliability**: Scores content reliability on a scale from 1 to 10, where 1 indicates low reliability and 10 indicates high reliability. This helps users assess the credibility of the information.


![alt text](image-2.png)
![alt text](image-1.png)
![alt text](image-3.png)

## Tech Stack & APIs

**Frontend:** React, Tailwind CSS, TypeScript  
**Build Tool:** Webpack  
**Integrated APIs:** GPT-3 & GPT-3.5-Turbo, TheNewsAPI

## Getting Started
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/manavkr0710/Clarity-Chrome-Extension.git
   cd Clarity-Chrome-Extension
   ```
   
>
> 2. **Set up your OpenAI API key:**
> - Create a `.env` file in the root directory and add your API key:
> - ```plaintext
>   OPEN_KEY=[your-openai-api-key]
>   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Build the project:**
   ```bash
   npm run build
   ```

5. **Chrome (Only):**
   - Open Chrome and navigate to the extensions page by visiting `chrome://extensions`.
   - Enable "Developer mode".
   - Click "Load unpacked extension" and browse to the `Clarity-Chrome-Extension/dist` directory to select it.

