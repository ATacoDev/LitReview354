# How do programming language features impact the development of artificial intelligence (AI) in games?
## By Jaden Johnson | CPCS-354 LLM Literature Review
LLM Used: ChatGPT

**Topic:**
`The choice of programming language can significantly impact the development of AI in games, influencing everything from performance and concurrency to the ease of integration and availability of libraries. Developers often choose languages based on their specific needs, such as real-time performance, ease of development, or integration with game engines and tools. Understanding how these language features affect AI development helps developers make informed decisions about the tools and technologies best suited for their projects.`

## References
[AI for Games, Third Edition by Ian Millington](https://www.taylorfrancis.com/books/mono/10.1201/9781351053303/ai-games-third-edition-ian-millington)

[Describing Artificial Intelligence in Real-Time Video Games, by IEEE](https://ieeexplore.ieee.org/abstract/document/6632583))


## History

### 50s - 60s
AI in video games dates back to the 50s with simple AI in games such as `Tennis for Two`, `Spacewar!`, and `The Adventures of Zork.` These games all exhibited some form of simple AI in which AI opponents or characters would play checkers against you, follow pre-defined patterns and rules, or just be there to proved appropriate responses and help integrate the player into the world that the game developer was trying to create.

### 80s - 90s
Later down the line in the 80s however, these AI began evolving into more complex and dynamic forms. This includes the all-popular `Pac-Man` in which the AI has Pac-Man wandering the level in an attempt to attack the player. This can also be seen in games like `Starcraft` where the AI opponents have to actually makes moves to outmaneuver the player, with difficulties ranging all the way from easy to extremely difficult. This is also proves in `Chess`! Sure you may think you're good at chess, but you don't always have the best possibly move at every point in the game like chess AI does.

### Current Day
Now, there is WAY more modern AI with NPCs being able to have full-on conversations with the player; some games even involve deep learning in order to truly immerse the player into the video game.

## Discussion Questions with ChatGPT

I asked ChatGPT a set of questions, and here is what it thought about the following:

### How do rapid development languages (e.g., Python) compare to performance-oriented languages (e.g., C++) in terms of prototyping and final implementation of AI in games?

ChatGPT essentially told me that the context of prototyping and final implementation of AI in games involves various factors such as development speed, performance, ease of use, and just the overall nature of the task at hand.

#### Python

- Has great readability and is overall a simple language, which is great because it can be written and shared easily by many developers
- Due to it being so easy to read and write, developers can quickly iterate on existing AI algorithms to create game mechanics that fit their projects without being "bogged down by complex syntax or compilation issues"
- While it is easily interpreted, it is much slower than languages like C++, and even if a final implementation is written in Python, it's often converted to C++ afterwards in order to take advantage of its higher performance, especially for more high-performance games
- Great for initial AI research and experimentation, but not great for the final implementation and when trying to send something to production

#### C++
- Much faster than Python, but due to it being a much more complex language, it's hard to experiment with AI with this language
- AI experimentation in video games will often be written in Python first and then translated to C++ later
  - Often however, this process can take a long time
- Preferred for final implementation

The choice between Python and C++ often comes down to the stage of development and the specific needs of the project. Many game development teams find success using both languages: Python for early development and experimentation and C++ for final, performance-oriented implementation.


### What are the advantages and limitations of using visual scripting languages (e.g., Unreal Blueprints) for AI development compared to traditional text-based languages?


### How are advancements in AI technology, such as reinforcement learning and neural networks, being incorporated into game development through programming languages?


### What impact does the programming language community and ecosystem have on the development of AI tools and libraries for game development?


