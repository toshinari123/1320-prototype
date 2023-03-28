# rust react chat++

based on tutorial https://blog.logrocket.com/real-time-chat-app-rust-react/ by Ahmad Rosid; improved a few things (see below)

frontend (ui folder): next.js, react.js, tailwind css;
backend (outermost): rust, sqlite, diesel

The main thing to edit if you want to edit UI is ui/pages/index.js; other js files are in ui/components and hooks are in ui/libs

the backend is on localhost:8080 and handles the database of currently rooms and messages; 
the frontend is on localhost:3000 and handles all the ui

frontend can be exported to mobile app using next.js capacitor

# how to run

1. git clone
2. https://www.rust-lang.org/tools/install
3. in terminal go to the directory (outermost) and run `cargo run`
4. https://nodejs.org/en/download
5. open another terminal, go to ui directory and run `npm run dev`
6. open localhost:3000 in preferably firefox
7. (press ctrl shift m to view mobile)
8. (install dbbrowser ans open chat.db)

# improvements made 

- can connect to the websocket server (in order for the typing... to show)
- stores conversation (messages) to database
- can create a new room (group)
- rooms have a description
