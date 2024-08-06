
# BuzzChat

**BuzzChat** is a real-time chat application built with modern web technologies, including React.js, Tailwind CSS, Next.js, MongoDB, and Pusher. The application is designed to offer seamless and instant messaging capabilities with a clean and responsive user interface. It is deployed on Vercel for optimal performance and scalability.


## Features

- Real-time messaging
- User authentication and registration
- Responsive and intuitive UI
- Scalable and performant backend
- Deployed on Vercel for high availability

## Technologies Used

- **Frontend:**
  - React.js
  - Tailwind CSS
  - Next.js
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
- **Real-time Functionality:**
  - Pusher
- **Deployment:**
  - Vercel

## Installation

To get a local copy up and running, follow these steps:

1. **Clone the repository:**

```bash
git clone 'https://github.com/sarveshsce/BuzzChat.git'
cd BuzzChat
```

2. **Install dependencies:**

```bash
npm install
```

3. **Set up environment variables:**

Create a `.env.local` file in the root directory and add the following environment variables:

```env
NEXT_PUBLIC_PUSHER_KEY=your_pusher_key
NEXT_PUBLIC_PUSHER_CLUSTER=your_pusher_cluster
MONGODB_URI=your_mongodb_uri
NEXTAUTH_URL=http://localhost:3000
```

4. **Run the application:**

```bash
npm run dev
```

5. **Open your browser and navigate to:**

```
http://localhost:3000
```

## Usage

- Register an account or log in if you already have one.
- Start a new chat or join an existing conversation.
- Enjoy real-time messaging with a responsive and user-friendly interface.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. **Fork the Project:**

```bash
git clone https://github.com/your-username/BuzzChat.git
```

2. **Create your Feature Branch:**

```bash
git checkout -b feature/YourFeature
```

3. **Commit your Changes:**

```bash
git commit -m 'Add some YourFeature'
```

4. **Push to the Branch:**

```bash
git push origin feature/YourFeature
```

5. **Open a Pull Request**
