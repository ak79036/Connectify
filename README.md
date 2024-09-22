<p align="center">
  <img alt="Chat-Application" src="https://drive.google.com/file/d/1zErFJRQjIuCKZsra3h_G6IzzR2seFzwt/view?usp=sharing" height="250px">
</p>  

# Chat-Application
### An application made with ❤️ by
* [Aditya Kumar](https://github.com/ak79036)
* Adm No.      - 22JE0054
* Institute    - IIT(ISM)DHANBAD
* Organization - I'mbesideyou



<h2 align="center">Below is the Deployed Link of the Website<h2>
* [Link](https://chat-application-aditiya.vercel.app)

## Table of Contents

- **[About Chat-Application](#about chat-application)**
- **[Application Features](#Application Features)**
- **[Important Points](#Important Points)
- **[Building from Source & Deploy to Hosting Platform](#building from source & deploy to hosting platform)**
- **[End Credits](#end-credits)**



## About Chat-Application

* This Chat Application is a **I'mbesideyou Software Development Project**.[Project Proposal](https://drive.google.com/file/d/1ucovUTp1L8dsihDBzjQsdaEw1C1QizcQ/view?usp=sharing).
This is a modern real-time chatting application built with a powerful tech stack that includes **Next.js**, **Convex**, **Clerk**, **ShadCN**, and **LiveKit**. The platform provides seamless real-time chat, audio/video calls, and friend management functionality.

* Next.js Framework- The application is built with Next.js, providing a robust and scalable frontend with server-side rendering for optimal performance and seamless navigation between the Conversations and Friends sections.
* Real-Time Chatting with Convex- Convex serves as the backbone for our real-time chat functionality. Whether it's a single or group chat, Convex ensures that messages are delivered instantly, with database synchronization that keeps conversations up-to-date for all users.
* Audio & Video Calls via LiveKit- To enrich the chat experience, LiveKit handles audio and video calls directly from the Conversations tab. It provides high-quality, low-latency connections, enabling users to switch seamlessly between text and voice/video communication.It will open when both users tap the video/audio button. 
Authentication with Clerk- Clerk manages user authentication, making sign-ups and logins secure and simple. It integrates seamlessly with the app to handle user sessions, ensuring access to personalized chats and friend lists.
Friends Management-The Friends section allows users to easily add or remove friends, with updates managed by Convex to keep the user’s contact list synced and real-time across devices.

## Application Features:

### 1. Built with Next.js
- Fast, responsive, and scalable frontend using **Next.js** with server-side rendering (SSR) for optimized performance and seamless navigation between different sections of the app.

### 2. Real-Time Messaging
- Real-time single and group chat capabilities powered by **Convex**, ensuring instant message delivery and synchronization across all users.

### 3. Audio and Video Calls
- Integrated **audio and video call** features, provided by **LiveKit**, allowing users to initiate high-quality, low-latency calls directly from the chat interface.

### 4. Secure User Authentication
- **Clerk** manages user authentication and session handling, ensuring secure login and sign-up processes for personalized experiences.

### 5. Friends Management
- Users can **add** and **remove friends** easily in the **Friends** section, with real-time updates to friend lists stored and managed by **Convex**.

### 6. Beautiful and Accessible UI
- A stylish and responsive user interface built using **ShadCN** components, ensuring a smooth, accessible, and visually appealing experience for users.
### 7. API-Driven Architecture
- **Robust API connections** ensure seamless integration between the chat, audio/video calls, and friends management functionalities. This architecture allows for real-time interactions and data synchronization across all services, including **Convex** for messaging, **LiveKit** for calls, and **Clerk** for authentication.

## Important Points:

 <h2 align="center">These are the System Design Diagrams<h2>
* [Link](https://drive.google.com/file/d/1tlwmPvJpgRAsUw6Ktrl_-6HdVAaieNAn/view?usp=sharing)

 <h2 align="center"><h2>
* [Link](https://drive.google.com/file/d/1qgWYFVl-XdfSwdNqwssNl7V6xkKi-IKG/view?usp=sharing)

## for Proper Documentation please take a look at presentation [here](https://drive.google.com/file/d/1ucovUTp1L8dsihDBzjQsdaEw1C1QizcQ/view?usp=sharing).

## To Access the video/Audio Call Feature both User should should tap on Video/Audio Button so that they can able to connect 


## Building from Source & Deploy to Hosting Platform

#### Prerequisites:
* Laptop/Desktop with internet access.

#### Steps:

1. **Clone the Repository**:
   - Clone the project from the GitHub repository:
     ```bash
     git clone https://github.com/your-repo/chatting-app.git
     ```

2. **Install Dependencies**:
   - Navigate to the project directory and install the required packages:
     ```bash
     npm install
     ```

3. **Set up Environment Variables**:
   - Create a `.env` file in the root directory and set up the following environment variables:
     - **Convex** API key
     - **LiveKit** API key
     - **Clerk** API key
     - Example:
     ```bash
     NEXT_PUBLIC_CONVEX_API_KEY=your-convex-api-key
     NEXT_PUBLIC_LIVEKIT_API_KEY=your-livekit-api-key
     NEXT_PUBLIC_CLERK_API_KEY=your-clerk-api-key
     ```

4. **Run the Application**:
   - Start the development server using:
     ```bash
     npm run dev
     ```

5. **Access the Application**:
   - Open your browser and go to [http://localhost:3000](http://localhost:3000) to access the app.

#### For Production:

1. **Build the Application**:
   - To create an optimized build for production, run:
     ```bash
     npm run build
     ```

2. **Run the Production Server**:
   - Start the server for the production environment:
     ```bash
     npm run start
     ```

3. **Building from Source & Deploy to Hosting Platform**:
   - You can deploy the application to a platform like **Vercel**, **Netlify**, or any other Node.js hosting service. For **Vercel**, follow these steps:
     - Sign up for an account at [Vercel](https://vercel.com/).
     - Connect your GitHub repository.
     - Set environment variables in the Vercel dashboard.
     - Deploy your application with a single click.

Now you have successfully deployed your real-time chatting application!
+





## End-Credits
You can find the Project Proposal here please do check it out [here](https://drive.google.com/file/d/1ucovUTp1L8dsihDBzjQsdaEw1C1QizcQ/view?usp=sharing).
We hope you have fun using this application ❤️