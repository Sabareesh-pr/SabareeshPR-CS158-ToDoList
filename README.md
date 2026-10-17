# To Do List — Daily Grove



Features: add, edit, complete, delete, and filter tasks. All tasks are saved through Express to MongoDB.

## Run

1. Open a terminal in this folder.
2. Run `npm install`.
3. Start local MongoDB, or set `MONGO_URI` in `backend/.env` to your MongoDB connection string. The default uses a separate `to_do_list` database on localhost.
4. Run `npm start`.
5. Open http://localhost:5174.

The API uses port 5001, so this version can run alongside the original app.

## Checks

- `npm run build` builds the React frontend.
- `npm test` runs the backend API tests without requiring MongoDB.
