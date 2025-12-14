# 🎶 Queue FM: Your Personalized Spotify Radio Station 🎶

![Queue FM Logo](https://example.com/logo.png)

Welcome to **Queue FM**, a Spotify-powered radio station that offers a smart playlist feature. You can let the playlist update itself or take control and curate your own listening experience. This project combines music, technology, and user preferences to create a unique auditory journey.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Smart Playlists**: Enjoy playlists that adapt to your listening habits.
- **User Control**: Take the reins and create your own playlists.
- **Spotify Integration**: Seamlessly connect with your Spotify account.
- **Next.js Framework**: Built using Next.js for a fast and responsive user experience.
- **PostgreSQL Database**: Utilizes PostgreSQL for reliable data storage.
- **TypeScript Support**: Ensures type safety and better developer experience.

## Getting Started

To get started with Queue FM, follow these steps:

1. Clone the repository.
2. Install the necessary dependencies.
3. Set up your environment variables.
4. Start the development server.

## Installation

To install Queue FM, you need to download and execute the latest release from our [Releases page](https://github.com/Paganessi/queue-fm/releases). 

```bash
git clone https://github.com/Paganessi/queue-fm.git
cd queue-fm
npm install
```

### Environment Variables

Create a `.env` file in the root directory and add your Spotify API credentials:

```
SPOTIFY_CLIENT_ID=your_client_id
SPOTIFY_CLIENT_SECRET=your_client_secret
DATABASE_URL=your_database_url
```

## Usage

After setting up the project, you can start the development server:

```bash
npm run dev
```

Open your browser and go to `http://localhost:3000` to see Queue FM in action. Log in with your Spotify account to start enjoying personalized playlists.

## Technologies Used

Queue FM leverages a variety of technologies to deliver a smooth user experience:

- **Next.js**: A React framework for server-side rendering and static site generation.
- **PostgreSQL**: A powerful relational database system for data storage.
- **Prisma**: An ORM for TypeScript and Node.js, making database interactions easy.
- **TypeScript**: A typed superset of JavaScript that enhances code quality.

## Contributing

We welcome contributions to Queue FM! If you want to help improve the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your branch and create a pull request.

Please ensure your code adheres to our coding standards and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Releases

To download the latest release of Queue FM, visit our [Releases page](https://github.com/Paganessi/queue-fm/releases). Be sure to check the release notes for updates and new features.

---

Queue FM combines the joy of music with smart technology. Whether you want a hands-off listening experience or prefer to create your own playlists, Queue FM has you covered. Enjoy your musical journey!