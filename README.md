# OperatingPlatforms-Project

# Project Reflection

## 1. Who was the client, and what software did they want me to design?
The Gaming Room was my client, and they wanted me to take their Android-only app, *Draw It or Lose It*, and turn it into a web-based game that works on multiple platforms. They needed a system where players could join in teams, each game and team had to have unique names, and the game had to handle more users playing at the same time. They also wanted the game to have solid security since it was moving from a mobile app to the web.

## 2. What part of my documentation did I do especially well?
I think I did a really good job on the domain model. By using inheritance with a base `Entity` class for shared stuff like IDs and names, I made sure everything was consistent and avoided duplicate names, which was a big deal for the client. I also explained how patterns like Singleton and Iterator would help keep everything organized and unique, which really connected back to the client’s requirements.

## 3. How did working through the design document help me with coding?
Going through the design document step by step helped me plan out what I actually needed to build before writing any code. Instead of guessing as I went, I already knew what classes I needed, how they should work together, and what challenges I’d need to solve. It made starting the code way less stressful and helped me see the big picture.

## 4. If I could go back and improve one part of my work, what would it be?
I’d spend more time on the System Architecture View section. I talked about the architecture in other places, but I didn’t actually make a diagram showing how the client, server, and database all connect. If I made a clear visual, it would make it easier for other people reading the document (or working on the project later) to understand how the whole system fits together.

## 5. How did I figure out what the user needed, and why is that important?
I paid close attention to what the client said they were struggling with — like needing unique names and a single active game instance — and made sure my design fixed those problems directly. It’s super important to keep the user’s needs in mind when designing software because otherwise, you could spend tons of time building something that doesn’t actually help them or work the way they want it to.

## 6. How did I go about designing the software, and what would I do next time?
I broke the requirements down into smaller parts and then used object-oriented design techniques like inheritance and encapsulation to put together a plan. I also wrote out technical and business requirements so everything stayed organized. Next time, I’d try building quick prototypes earlier in the process so I could test out ideas and get feedback before writing the full design. That would probably save time and make sure the design is really what the client wants.
