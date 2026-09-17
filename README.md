# firstf
combines Linux commands 'grep' and 'head'

## How the command works
- called by node (user must have node installed), your js file (denotated by PATTERN), then your actual file name you pass to the command line (denotated by FILENAME), and the number of lines you want to look for (denotated by NUMBER_OF_LINES) 
- imports the fs and path module
- makes sure that we have exactly 4 arguments
- checks if file exists
- checks if PATTERN is an empty string
- checks if a valid number of lines was entered
- checks number of lines
- reads the file, splits line, and prints all the cases of the pattern a user entered
## AI assisted programming reflection
AI helped by giving us use/test cases. It also gave us edge cases that we did not previously think of as a class. It also explained the head and grep command in greater detail and provided sample logs for us to use for testing purposes. It also explained any errors that we made while programming, and offering multiple alternative, which I found very helpful. The AI companion I used, chatGPT, has also talked to me about cybersecurity related terms in the past, and also gave me examples about how head/grep/tail commands are used in the field. Overall, AI was very helpful in assisting with things that me and my classmates originally overlooked and is a great tool for programming.
