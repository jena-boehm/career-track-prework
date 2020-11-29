[**Quantity Always Trumps Quality**](https://blog.codinghorror.com/quantity-always-trumps-quality/)

- Quality over quantity isn't necessarily the best course of action when coding or creating art. 
    - When focusing on quality alone you can get caught up in the perfectionism of it all, which can hinder your actual ability to finish a piece of work. 
    - When churning out a massive amount of work, you are also in the process learning from your mistakes and refining your technique, which in turn leads to a higher quality product. 

- *"Rather than agonizing over whether you're building the right thing, just build it. And if that one doesn't work, keep building until you get one that does."*


[**Clean Code: Chapter 1**](http://ptgmedia.pearsoncmg.com/images/9780132350884/samplepages/9780132350884.pdf)

- Bad code usually happens when you are rushing and don't take the time to clean up your code. Sometimes you just want to get it to work first and then you'll "go back and clean it up later," but that never actually ends up happening. 
- Bad code can significantly slow down a project over time, even if you were moving quickly in the beginning. Every change comes with a new error. 
- As developers, it's our job to defend and maintain the code. No one else is to blame for bad code except the ones who write it. 
    - Managers may stress timelines and move projects along too quickly, but the responsibility is still on the developers. 
    - *"...it is unprofessional for programmers to bend to the will of managers who don't understand the risks of making messes."*
- Clean code is elegant, pleasing, efficient, simple, focused, and direct. 
    - It should read like well-written prose. 
    - Error handling should be complete.
    - It should include tests. 
    - *"Each function, each class, each module exposes a single-minded attitude that remains entirely undistracted, and unpolluted, by the surrounding details."*
    - Clean code should read pretty much as expected. According to Ward Cunningham, *"You can call it beautiful code when the code also makes it look like the language was made for the problem."*
- Bad code only tempts the mess to grow. It's inevitable that it will only get worse. 
- In order to have clean code, it has to be kept clean from the beginning. Ideally, the code will only get better over time, not get so complicated and convoluted that you're not even sure how to move forward. 


[**TDD: Red, Green, Refactor**](https://www.codecademy.com/articles/tdd-red-green-refactor)

- *Test-Driven Development* (TDD) - An approach where you write tests first, then use those tests to drive the development of your app. 

- *Red, Green, Refactor* - a TDD framework used to build a test suite, write implementation code, and optimize the codebase in short development cycles. 
    - **Red**
        - Define *what* you want to implement
        - Write minimal implementation code
        - Run the test, take note of the error message
    - **Green**
        - Think about *how* to make the tests pass
        - Find a solution, without worrying about optimizing your implementation 
    - **Refactor**
        - Think about *how* to improve the existing implementation
            - How to accomplish the same output with more descriptive or faster code
        - Consider the characteristics of a good test suite:
            - MC-FIRE
                - Maintainable
                - Complete
                - Fast
                - Isolated 
                - Reliable
                - Expressive


