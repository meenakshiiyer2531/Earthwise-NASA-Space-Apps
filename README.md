# EarthWise: AI-Powered Learning for SDGs

EarthWise is a sophisticated full-stack web application designed to educate users about the United Nations' 17 Sustainable Development Goals (SDGs) through AI-driven, interactive learning experiences. With multilingual support, text translation, and advanced Text-to-Speech (TTS) services, the platform ensures accessibility and inclusivity for a global audience of over 1,000 users.

At the heart of EarthWise lies its AI Tutor, an intelligent and engaging virtual assistant powered by cutting-edge AI technologies. This tutor delivers interactive lessons using real-time TTS and Lip Sync technology to simulate life-like interactions, making the learning journey captivating and highly impactful.

## Features

**1. AI-Powered Tutor**

The platform leverages OpenAI's GPT-3 to deliver personalized, interactive lessons on the 17 SDGs, responding intelligently to user queries and simulating dynamic interactions within an AR/VR environment.

It integrates the ElevenLabs API for natural, human-like Text-to-Speech output, enhancing auditory engagement and creating a more immersive experience.

Rhubarb Lip Sync technology is used to synchronize lip movements with spoken words, ensuring a lifelike and visually interactive experience with the virtual tutor.

*Unreal Engine* is incorporated to power the AR/VR model, enabling realistic, immersive simulations that bring the AI tutor to life in a fully interactive 3D environment.

**2. Text Translation**

Uses the Google Translate API to translate content into multiple languages in real time, ensuring accessibility to a global user base.

Supports localization to cater to cultural and linguistic preferences, expanding the platform's reach and inclusivity.

**3. Text-to-Speech (TTS)**

Delivers audio narration of lessons using advanced Text-to-Speech capabilities from Web Speech API and ElevenLabs API.

TTS ensures users with visual impairments or learning differences can fully participate in lessons, breaking accessibility barriers.

**4. Lip Sync Technology**

Powered by Rhubarb Lip Sync and FFmpeg, ensuring seamless synchronization of the virtual tutor's lip movements with audio output.

The result is a realistic, life-like avatar interaction that enhances the learning experience, particularly for visual learners.

**5. Multilingual Support**

Supports a diverse audience by providing lessons in multiple languages, ensuring inclusivity and equitable learning opportunities for all.

Can cater to more than 1,000 active users globally, offering a robust infrastructure for real-time translation and lesson delivery.

## Technologies Used

### Frontend

- Next.js: Provides server-side rendering and fast loading times for a seamless user experience.

- React.js: Forms the foundation for building a dynamic and interactive user interface.

- Tailwind CSS: Enables rapid and consistent styling with a modern, responsive design.

- Three.js & React-Three-Fiber: Adds immersive 3D visualizations for lessons, making complex concepts easier to understand and visually appealing.

- Leva: Used for managing and tweaking UI parameters dynamically, particularly during the integration of 3D assets.

### Backend

- Node.js & Express.js: Handle API management, server-side logic, and user authentication seamlessly.

- OpenAI API: Powers the AI Tutor, enabling intelligent dialogues and lesson generation.

- ElevenLabs API: Provides cutting-edge TTS services for lifelike voice outputs.

- Rhubarb Lip Sync & FFmpeg: Facilitate the synchronization of audio and lip movements, making the tutor's interactions realistic.

### Database

**MongoDB:**

Stores flexible, schema-less data such as student profiles, lesson progress, and user interactions.

Efficiently handles a large volume of data, ensuring scalability as the platform grows.

### Authentication

**Firebase Authentication:**

Ensures secure login and user tracking with a simple, intuitive interface.

Facilitates easy management of student-teacher accounts, enhancing user experience while maintaining data protection.

## AI Tutor Interaction

The AI Tutor is designed to teach lessons interactively, with support for both voice and text inputs.

Lessons are complemented with real-time TTS outputs and lip-synced animations to simulate a human-like teaching experience.

Users can ask the tutor questions at any time, with the AI responding intelligently using GPT-3’s contextual understanding.


## Why EarthWise is Not Open Source

EarthWise is a proprietary platform designed to maintain the integrity, security, and quality of its educational content and AI-driven features. By keeping the code in a private repository, we ensure:

User Data Security: Sensitive information such as user profiles and learning progress remains protected.

Feature Integrity: Cutting-edge technologies like AI, TTS, and Lip Sync are utilized responsibly to prevent misuse.

Scalability: Controlled development allows us to deliver the best experience to our users without compromising on quality.

## Video Demonstration
Check out a video demonstration of EarthWise in action:
[![Video Demo](https://github.com/user-attachments/assets/f1d3231a-a5bb-405e-b3d6-fabf4ff02fa9)](https://www.youtube.com/watch?v=tTb7bpY6oPw)


