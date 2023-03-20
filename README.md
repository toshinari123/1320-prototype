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
7. sign in with phone number `345` or `678` or there will be errors
8. when u make changes to javascript it auto compiles and reloads for u so cool

# todo

what you should do:
- learn react: https://blog.logrocket.com/react-conditional-rendering-9-methods/
- learn tailwind css
- understand index.js
- make things pretty / add buttons that dont do anything

actual todo:
- add hiring description to the room view instead of like the last message sent (I do)
- currently room dont differentiate which person is the owner which is bad (also I do)
- make room (I do)
- make the grey background fill the whole screen instead of awkwardly being on the side
- add random buttons in filter (will likely not implement actually cuz too hard)
- add tags?
- if mobile app have the orange gradient background is it weird
- differentiate between landscape and portriat?

# q&a

- does it take up space
- yes it does quite a lot after cargo run around 2.3 GB

- what are the folders
- migrations is some database stuff; src is rust code; static is u can ignore; target is where rust puts compiled stuff

# screenshots currently
![image](https://cdn.discordapp.com/attachments/912270605515124766/1087042899419598920/image.png)
![image](https://cdn.discordapp.com/attachments/912270605515124766/1087043302362185799/image.png)
![image](https://cdn.discordapp.com/attachments/912270605515124766/1087043367810109490/image.png)
![image](https://cdn.discordapp.com/attachments/912270605515124766/1087043439331377334/image.png)
![image](https://cdn.discordapp.com/attachments/912270605515124766/1087043502443081758/image.png)
