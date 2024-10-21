This repository contains the software design document for "Draw It or Lose It," a web-based game designed for The Gaming Room. The client requested a digital version of the classic TV game show where teams compete to guess what is being drawn. Instead of live drawing, pre-made images will be used, and the game must handle multiple teams and players, ensuring unique names for each team and game. A key requirement was that only one game instance runs at a time, which we implemented using the singleton design pattern. The game is also web-based, meaning it needs to be efficient in handling a multi-user environment.

In developing this documentation, I was particularly proud of how I outlined the system architecture and constraints. I ensured that the key features, like unique team names and the singleton pattern, were clearly described, making it easy for both developers and non-technical stakeholders to understand.

The process of working through a detailed design document before coding was incredibly useful. It helped me anticipate challenges, such as how to ensure only one game runs at a time, and how to handle multiple users without conflicts. This foresight made coding more structured and efficient.

If I were to revise any part of the document, I would focus on the scalability section. While I briefly touched on scalability, I think I could have expanded on how we would manage performance under heavy user loads, especially with large numbers of teams and players.

Understanding the client's needs was essential to shaping the software design. For instance, they required an easy to use web interface that supports multiple teams and unique names for each team and game. Keeping the user's experience in mind ensured that the software would meet their practical needs, from a smooth user interface to reliable performance.

In approaching the design, I relied on established design patterns like the singleton pattern to address specific problems, such as limiting the game to one active instance. In the future, I plan to continue using these techniques, along with incorporating more testing into the design phase to ensure the system is scalable and robust under real-world conditions.

