# 1320-prototype

frontend (ui folder): next.js, react.js, tailwind css;
backend (outermost): rust, sqlite, diesel

The main thing to edit is ui/pages/index.js; other js files are in ui/components and hooks are in ui/libs

the backend is on localhost:8080 and handles the database of currently rooms and messages; 
the frontend is on localhost:3000 and handles all the ui

frontend can be exported to mobile app using next.js capacitor; maybe for the final prototype upload the backend 
to some random server

# how to run

1. git clone
2. https://www.rust-lang.org/tools/install
3. in terminal go to the directory (outermost) and run `cargo run`
4. open another terminal, go to ui directory and run `npm run dev`
5. open localhost:3000 in preferably firefox
6. press ctrl shift m to view mobile

# todo

- learn react: https://blog.logrocket.com/react-conditional-rendering-9-methods/
- learn tailwind css
- understand index.js
- make things pretty / add buttons that dont do anything

# q & a

# screenshots currently
