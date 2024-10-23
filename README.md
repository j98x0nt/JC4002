java cJoint Institute SCNU - University of Aberdeen
Knowledge Representation (JC4002)
Assessment
The assessment is worth 25% of the overall marks for the course. Each item indicates the number
of marks it is worth, clearly broken down in their speciffcation. Students will provide their answers via
MyAberdeen and receive feedback via MyAberdeen.
Learning outcomes associated with this assessment:
• Students will be able to identify the knowledge base (or lack thereof) of an AI application.
• Students will be able to evaluate the use of knowledge base in real-world scenarios.
• Students will be able to design, implement and evaluate knowledge-intensive AI systems.
Instructions to students:
• Your solution should be one single ZIP ffle (as indicated in the item) that you should upload
to MyAberdeen by the established time/deadline. Any other format (such as RAR, ARJ, 7zip,
or any other format other than ZIP) will result in 0 marks. Do not email us your solution.
• If you submit a scanned/handwritten PDF, you will get 0 marks.
• This is an individual coursework, if you share your solution with a colleague or if you copy an
existing solution, both students will be investigated for collusion and plagiarism; the investigation
can result in both students getting 0 marks or being expelled from the course.
• Your ffle should be named “JC4002-YourSurname-YourName-YourIDNo.zip”. For instance, “JC4002-
Jovan-Ferdian-999999.zip”
1
, where 999999 is your student ID.
About this assessment: You must never share it with anybody in or outside the course, even
after you complete the course. Please do not distribute or post solutions to any of the projects and
notebooks.
Academic Dishonesty: This is an advanced course, therefore we expect full professionalism and
ethical conduct. You must work on this project individually. You are free to discuss high-level design
issues with the people in your class, but every aspect of your actual formalisation/code/answer must
be entirely your own work. Furthermore, there can be no textual similarities in the reports generated
by each person. Plagiarism, no matter the degree, will result in forfeiture of the entire grade of this
assessment. Plagiarism is a serious issue and we take academic misconduct very seriously. Sophisticated
plagiarism detection software will be used to check your code against other submissions in the class as
well as resources available on the web for logical redundancy. Please do not let us down and risk our
trust. If you do, we will pursue the strongest consequences available to us according to the guidelines
provided by the university. For more information, see the Code of Practice on Student Discipline. Use
of automated services to generate submissions for assessment will be treated as academic
misconduct and pursued under the University misconduct procedures.
Late Submissions: You should apply for an extension by emailing your request (using
your UoA email address) to uoa-ji-enquiries@abdn.ac.uk. You should also include any supporting
evidence where possible e.g medical letter. Please familiarise yourself with the University’s guidance
on late submission.
1Do not put the quotation marks in your fflenameJC4002 – Knowledge Representation
Horn-Clauses and Prolog
1. Your assessment is to write a text adventure game in Prolog.
2 You have to use the SWI-Prolog
interpreter for this assessment.
You can copy the ffle “adventure-startercode.pl” (available on myAberdeen along with this PDF)
and use it as a starting point. In this sample game there is one room, one object, and one direction
you can go (north, but going in that direction takes you back to the same room). You can use or
modify this code in any way you like to create your own game. Submitting the same ffle without
any signiffcant changes will merit 0 marks. You do not need to use this ffle as a starting point,
but you must follow these requirements:
(a) (30 marks) Knowledge base facts – Does your knowledge base include all the necessary
facts to play the game? Are there any facts that are neve代 写JC4002、c/c++
代做程序编程语言r being used in the game? Do you
have dynamic facts and are they being managed correctly?
(b) (30 marks) Knowledge base rules – Do you have rules for winning the game? And for
losing the game? Do you have rules to manage the player inventory (assuming you are using
inventory system in your game)? Are the commands that the player can use working properly?
Are you using arithmetic functions to manipulate your knowledge and the rules of the game?
(c) (10 marks) Transcript – See submission instructions for details.
(d) (30 marks) Report – See submission instructions for details.
Total Marks 1: 100 marks
Marking scheme: Your program should work, should satisfy the above requirements, and should be
reasonably formatted. At most 25 marks will be awarded if the program does not run. Submissions
without all the main ffles (“game name.pl”, “report.pdf”, and “transcript.txt”) will merit 0
marks.
You should have a start/0 predicate (similar to the one provided in the starting code) that we can
use to start your game and print out what commands the player can use. Submissions without
this predicate will merit 0 marks. Submissions that do not inform the player the commands
that can be used at the start of the game will receive mark penalties.
We reserve the right for some subjective judgement. If we like your game, we may give you bonus
points for it. If your game seems to lack creativity and interest, you may lose points.
Submission instructions: The following ffles should be included in your ZIP ffle (ZIP only, not
RAR, 7z, or anything else):
• game name.pl – source code. The game name should be a short version of the name of your
game.
• transcript.txt – a transcript of a sample run of your program. This is a walkthrough of the
game, showing the commands entered and the computer’s response to each command. You
can get this by playing the game and copy/pasting the results. You have to show a successful
run of your program (i.e., beating the game).
• report.pdf – game report containing:
– the name of your game;
– one paragraph describing what your game is about;
– an explanation of your knowledge base and what was your reasoning for making the
choices you did;
– an inspiration game that you use (if you use any) and an explanation what differs between
your game and your inspiration game from the gameplay perspective as well as codes
perspective.
2This is inspired by Prolog coursework from David Matuszek.
Assessment 2JC4002 – Knowledge Representation
– there is no speciffc template that you must follow, but here are the things we expect out
of your report (if any of these instructions are not followed, you will get mark penalties):
∗ at most 1500 words (add your word counter in the end of your report, references,
ffgures, tables, and captions do not count);
∗ text alignment justiffed;
∗ no abstract;
∗ section headers (numbers are optional but should be consistent if present);
∗ We expect to see at least a ffgure and/or table to help explain your game;
∗ references should be formatted following the ACM style (if you used any, but remember
 if you took inspiration from something and you do not cite it that is plagiarism).
Hints:
• There are many text adventure games available online (many even in Prolog) to draw inspiration
 from. Just be careful with plagiarism, only use them for inspiration, do not copy any
of the code (remember you will have to explain your game and your code in your report).
• You could push this beyond the scope of the assessment by adding an interface, web server,
learning component, etc. There are many tutorials for using these things in Prolog available
in SWI-Prolog website and on internet forums. This is not required, but you will likely get
bonus marks if you manage to pull it off successfully.
• Your game may have several win and loss conditions, just be careful they are not contradictory.
• The cut operator is your friend to make nice print statements and to make the ffow of the
game more natural.
Assessment 3

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
