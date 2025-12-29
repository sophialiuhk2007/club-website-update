### Download

- **Docker:** [Download here](https://www.docker.com/products/docker-desktop/)
- **Node.js & npm:** [Download here](https://nodejs.org/)

### Setup

1. **Clone:**

   ```sh
   git clone https://github.com/sophialiuhk2007/club-website-update.git
   cd club-website
   ```

2. **Backend (Supabase):**

   ```sh
   cd supabase/docker
   docker compose up -d
   ```

   - The Supabase database and dashboard are at [http://localhost:8000](http://localhost:8000).

3. **Frontend (Epsilon):**

   ```sh
   cd ../../epsilon
   npm install # only need it for the first time
   npm run start
   ```

4. **Open the website:**
   - Visit [http://localhost:3000](http://localhost:3000)
