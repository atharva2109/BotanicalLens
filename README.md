# Botanical Lens

## Plant Recognition Web Application

### Project Overview

Botanical Lens is a progressive web application designed to help users record and identify plants. Users can add new plant sightings, view plants added by themselves or other users, and comment on sightings. The application leverages Node.js, Express, MongoDB, and integrates with the DBPedia knowledge graph for plant identification.

### Features

- **View Plants**: Sorted by date/time seen and identification status. Optionally sort by distance.
- **Add Plant Sightings**: Includes date/time, location, description, size, characteristics, identification, photo, and user's nickname.
- **Plant Details & Chat**: Detailed view with public chat for each sighting, allowing real-time discussions.
- **Offline Support**: Create and manage sightings and chats while offline, with data synchronization upon reconnection.

### Demo

Watch the demo video [here](https://drive.google.com/file/d/15Clx2uPqeWGVYGCX3kdyC4Oy_0BfC7rE/view?usp=sharing).

### Initial Wireframe

View the initial wireframe [here](https://drive.google.com/file/d/1eJ5XjPKoRD7nfO5T0QZr3rrd20445CkU/view?usp=sharing).

### Installation and Setup

#### Prerequisites

- Node.js (version 14.x or higher)
- MongoDB (local or remote instance)

#### Steps to Run the Application

1. Clone the repository:

   ```sh
   https://github.com/atharva2109/BotanicalLens.git
   ```

2. Move to the solution folder:

   ```sh
   cd solution
   ```

3. Install the dependencies:

   ```sh
   npm install
   ```

4. Start the application:

   ```sh
   npm start
   ```

5. Access the application:
   Open your browser and navigate to `http://localhost:3000`.

### Code Structure

#### Web Application

- **Frontend**: EJS, JavaScript, HTML5, CSS
- **Backend**: Node.js, Express
- **Real-time Chat**: Socket.io
- **Database**: MongoDB for plant and chat data, IndexedDB for offline storage

#### Key Functionalities

1. **Adding Plant Sightings**: Form to submit plant details, location, photo, and identification status.
2. **Viewing Plant Sightings**: List and detail view with sorting and filtering options.
3. **Chat System**: Real-time chat for each plant sighting, with offline message support.
4. **Offline Functionality**: Store new sightings and chats locally, sync when online.

### DBPedia Integration

- Fetch plant information using SPARQL queries.
- Display common name, scientific name, description, and URI from DBPedia in the UI.

### Documentation and Code Quality

- **Inline Comments**: Descriptions within the code for clarity.
- **Higher-level Documentation**: Detailed comments and documentation files explaining the codebase.
- **GitHub Commit History**: Track the progress and contributions on [GitHub](https://github.com/atharva2109/BotanicalLens/commits/main/).

### Screenshots and Videos

- Include screenshots or a video demo in the `<MainDirectory>/Screenshots` folder.

### License

See the [LICENSE](LICENSE) file for details.

---

Feel free to reach out via the project's GitHub repository for any issues or contributions. Enjoy exploring BotanicalLens!
