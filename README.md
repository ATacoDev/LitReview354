# How do programming language features impact the development of artificial intelligence (AI) in games?
## By Jaden Johnson | CPCS-354 LLM Literature Review
LLM Used: ChatGPT

**Topic:**
`The choice of programming language can significantly impact the development of AI in games, influencing everything from performance and concurrency to the ease of integration and availability of libraries. Developers often choose languages based on their specific needs, such as real-time performance, ease of development, or integration with game engines and tools. Understanding how these language features affect AI development helps developers make informed decisions about the tools and technologies best suited for their projects.`

## References
[AI for Games, Third Edition by Ian Millington](https://www.taylorfrancis.com/books/mono/10.1201/9781351053303/ai-games-third-edition-ian-millington)

[Describing Artificial Intelligence in Real-Time Video Games, by IEEE](https://ieeexplore.ieee.org/abstract/document/6632583))

[Deep Reinforcement Learning for General Video Game AI, by IEEE](https://ieeexplore.ieee.org/abstract/document/8490422)

[Ugla, Alexander. Improving the User Experience of Visual Scripting Languages](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1621764&dswid=-7671)


## History / Background

### 50s - 60s
AI in video games dates back to the 50s with simple AI in games such as `Tennis for Two`, `Spacewar!`, and `The Adventures of Zork.` These games all exhibited some form of simple AI in which AI opponents or characters would play checkers against you, follow pre-defined patterns and rules, or just be there to proved appropriate responses and help integrate the player into the world that the game developer was trying to create.

### 80s - 90s
Later down the line in the 80s however, these AI began evolving into more complex and dynamic forms. This includes the all-popular `Pac-Man` in which the AI has Pac-Man wandering the level in an attempt to attack the player. This can also be seen in games like `Starcraft` where the AI opponents have to actually makes moves to outmaneuver the player, with difficulties ranging all the way from easy to extremely difficult. This is also proven in `Chess`! Sure you may think you're good at chess, but you don't always have the best possibly move at every point in the game like chess AI does.

### Current Day
Now, there is WAY more modern AI with NPCs being able to have full-on conversations with the player; some games even involve deep learning in order to truly immerse the player into the video game.

### Modern day researchers in the subject

After asking ChatGPT, here are some of the most influential names that have contributed to the research of this topic:

**John Carmack** - Known for his work on game engines and real-time graphics, Carmack's insights into programming languages and performance are influential in game development.

**Jesse Schell** - An expert in game design and author of The Art of Game Design: A Book of Lenses, Schell’s work often touches on the technical aspects of game development, including AI.

**Ian Bogost** - A game designer and professor, Bogost has written extensively about game development and the impact of technology on games.

**Mark Cerny** - As a game designer and lead architect for several PlayStation consoles, Cerny's work involves understanding how programming languages and tools affect game development.

**David Eberly** - Known for his work on game programming and 3D graphics, Eberly’s contributions to the field include insights into how different programming languages impact game performance and AI.

**Tom Forsyth** - An experienced game developer and researcher, Forsyth has written about game development practices, including programming languages and their effects on AI.

**Chris Hecker** - Co-creator of the game SpyParty and an expert in game development, Hecker's work often explores the technical aspects of AI and game programming.

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

After asking some questions to chatGPT like the one above, it concluded that:

visual scripting languages like Unreal Blueprints offer a more accessible and intuitive way to develop AI, especially for rapid prototyping and collaborative work. However, they may face limitations in performance, scalability, and flexibility compared to traditional text-based languages. The choice between the two often depends on the specific needs of the project and the skill sets of the team involved. Specifically,

**Advantages**
- Visual scripting languages provide a friendlier user interface so it's better especially for those who may be less experienced with coding
    - These visual scripting languages also give back immediate feedback unlike some traditional text-based programming languages. They are "used as alternatives to text programming to make coding easier. Visual programming languages provide a structure and a guidance that does not exist in text programming, which should make them easier to code with." ([Ugla, Alexander. Improving the User Experience of Visual Scripting Languages](https://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1621764&dswid=-7671))
    - Given that these visual scripting languages are more friendly to the eye, complex AI behaviors can be visualized more clearly, furthermore helping with the developers understanding of whatever they are trying to accomplish
 - These can be often integrated with game engines which is well, incredibly beneficial especially if you are trying to design AI or AI logic for a piece of a video game
 - These visual languages as well allows for easier collaboration with people who are not as coding experienced, for example letting you work with someone who is more proficient in art. Though they don't code, they will still be able to get some sort of understanding from your AI implementation through visual works instead.

**Disadvantages**
- These visual languages can produce more overhead, especially with more complex AI systems.
  - Given this, this can become a situation like converting python scripts to C++ scripts before final production.
- Each visual language tool is unique, and therefore there can be a bit of a learning curve that isn't necessarily there when using a language of your choice. While there is still a learning curve when you are using a regular text-based language, those same skills can be transfered to every other language, just with a little bit different of syntax each time.

### Example with Unreal Engine and Blueprints

- Fortnite was made with Unreal Engine and its blueprints, allowing developers to quickly tweak AI to test different strategies and interaction, which is especially crucial with how fast of development is needed for that title
    - HOWEVER, since Fortnite grows more and more complex, and constant needing new AI logic/tools, some of it will instead need to be written in python or C++ first, before getting it settled into the visual programming language

`In summary, depending on the type and complexity of the AI you are developing for your game, at times it may just be easier to develop it in some form of visual language. However, if you need more complex logic, developing it first using both Python and C++ may be smarter, and then you can further integrate that into some form of visual programming model.`


## Summary
The choice of programming language in AI development for games has significant effects on performance, development speed, and integration capabilities. Python, Known for its  ease of use, is often favored for rapid prototyping. Its straightforward ecosystem allows developers to quickly test and iterate on AI concepts. However, Python's slower execution speed can be a limiting factor for final implementations, especially when performance is critical. As a result, many developers transition to C++ for the final product. C++ excels in performance and efficiency, making it a preferred choice for production-ready AI systems where execution speed and resource management are paramount.

Visual scripting languages, such as Unreal Blueprints, provide an intuitive, node-based interface that facilitates quick adjustments and collaboration, especially with non-programmers. This can be particularly useful in the early stages of development or in teams where diverse skill sets are involved. Nevertheless, visual scripting languages can introduce overhead and face scalability challenges when dealing with complex AI systems. As a project scales, developers often find it necessary to switch to text-based languages to optimize and refine their implementations. Overall, the programming language you pick has a big determination on how you decide to go about developing and producing AI material. This is especially true in video games, where the industry moves fast, and you're always finding yourself in a situation to find new and interesting strategies to interest your customers.



