# Fence Challenge for ScaDS.AI/MPS MiS

### DONE

- Python WHL Demo loaded in JavaScript
- Graphics Loaded and Rendered
- Python CV Detects Pentominos & Calculates Area
- Web App works on Laptop & Mobile
- Camera Resolution is Constrained on Mobile
- Basic Structure for CV & WebGame Modes
- Prerendering/static-serving correctly (vercel)
- Add Loading Bar on Site Loading
- Load and Initiate Pyodide on site loading
- Setup and connect to Supabse Database
- Basis setup of webgame component
- Raycaster for pentomino selection and movement
- Board Occupancy Matrix filled
- Weird pentominos (2x4) aligned
- Rotate, flip functions added
- press Spacebar to rotatePentomino and press Enter to flipPentomino

### BUGS

- Miguel - spec out macbook camera bug
- Pentominos still fall off the board very occasionally -
- I pentomino seems to use too big a space sometimes
- If you add a pentomino then remove it, then click post-result, python still thinks there is a pentomino on the board

### TODO

- **(by end of Feb)**
  - **Make WebGame Work Properly**
    - empty
  - **Make python CV Arrange Fence & Display Calculated Area**
    - Display calculated area in the game mode in a nice way
  - **Upload Fence Area to Database & Get and Show Leaderboard**
    - send GET request for order/leaderboard
      - ALFREDO - Upload previously calculated areas, plus is_maximal field
    - render leaderboard
    - newLeadboardEntry modal (input name etc.)
    - send POST request to upload new leaderboard entry
    - ThankYou modal (post-submit)
  - **Misc Tasks**
    - Startup/Info Modal (renders on siteload or via. info button to give instructions, and project details)
  - Make Website/Tablet/Mobile Fully Responsive
- **(by march 14th)**
  - FULLY TEST ACROSS A WIDE RANGE OF DEVICES AND SCREENS
  - FULLY TEST THE PYTHON CV ON AS MANY EDGE CASES AS YOU CAN THINK OF
  - Set up a long-term solution for the backend
    - Backend - Supabase provisionally, to be rebuilt by Alfredo
    - Frontend - Vercel
  - Make Website work in Multiple Languages
  - Add Map of where people have uploaded results from

### DOCS

- Front-End
  - The front-end is hosted and served on vercel.
  - Email (d.humphries@ucl.ac.uk) for access
  - Vercel Project Link: https://vercel.com/citizen-science/fence-challenge
  - Vercel Docs: https://vercel.com/docs
- Python
  - TODO (Leaving to Miguel)
- Database
  - The back-end is managed by Alfredo
  - Email (alfredogc05@protonmail.com) for access
