# PSGoogle: Institutional Search Engine

PSGoogle (someone pls come up with a better name) is an institutional search engine designed specifically for PSG College of Technology. It combines a robust backend with an intuitive frontend to enable efficient information retrieval from the psgtech.edu website.

## Frontend
The PSGoogle frontend repository houses the Next.js application, which is barebones, but offers a sleek and user-friendly interface for PSGoogle.

Explore the frontend repository: [PSGoogle Frontend Repository](https://github.com/jassuwu/search-psgtech)

## Backend
The PSGoogle backend repository contains the scraper, indexer, and server components. It leverages advanced Information Retrieval (IR) techniques, including Okapi BM25, to process and index data from the PSGTech website. Key features include:
- **Scraper**: Retrieves and preprocesses web pages.
- **Indexer**: Implements Okapi BM25 algorithm to create an inverted index for efficient search.
- **Server**: Provides a fast and responsive interface for querying and retrieving documents.

Explore the backend repository: [PSGoogle Backend Repository](https://github.com/jassuwu/scrape-psgtech)

## Docker Compose Setup
This repository provides a Docker Compose configuration to orchestrate the PSGoogle backend and frontend as separate services. It simplifies deployment and ensures seamless communication between the frontend and backend components.

### Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/jassuwu/psgoogle.git
   cd psgoogle
   ```

2. Configure environment variables if necessary (probably not necessary).

3. Start the PSGoogle services:
   ```bash
   docker compose up -d
   ```

4. Access PSGoogle frontend:
   Open a browser and go to `http://localhost:3000` to use PSGoogle.

5. Stop PSGoogle services:
   ```bash
   docker compose down
   ```

### Contributing
- Contributions are welcome! Fork the repositories, make your changes, and submit a pull request.
- Report any issues or suggestions through GitHub issues.
