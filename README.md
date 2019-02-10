# Blockvote
Winner at the Princeton Hackathon

<h2>Inspiration</h2>
To introduce the most impartial and ensured form of voting submission in response to controversial democratic electoral polling following the 2018 US midterm elections. This event involved several encircling clauses of doubt and questioned authenticity of results by citizen voters. This propelled the idea of bringing enforced and much needed decentralized security to the polling process.

<p align="center"> 
<img src="https://github.com/Subhanc/BlockVote/blob/master/Screenshots/Screenshot1.jpg" alt="home screen">
</p>

<h2>What it does</h2>
Allows voters to vote through a web portal on a blockchain. This web portal is written in HTML and Javascript using the Bootstrap UI framework and JQuery to send Ajax HTTP requests through a flask server written in Python communicating with a blockchain running on the ARK platform. The polling station uses a web portal to generate a unique passphrase for each voter. The voter then uses said passphrase to cast their ballot anonymously and securely. Following this, their vote alongside passphrase go to a flask web server where it is properly parsed and sent to the ARK blockchain accounting it as a transaction. Is transaction is delegated by one ARK coin represented as the count. Finally, a paper trail is generated following the submission of vote on the web portal in the event of public verification.

<h2>How we built it</h2>
The initial approach was to use Node.JS, however, Python with Flask was opted for as it proved to be a more optimally implementable solution. Visual studio code was used as a basis to present the HTML and CSS front end for visual representations of the voting interface. Alternatively, the ARK blockchain was constructed on the Docker container. These were used in a conjoined manner to deliver the web-based application.

<h2>Challenges ran into</h2>
Integration for seamless formation of app between front and back-end merge
Using flask as an intermediary to act as transitional fit for back-end
Understanding incorporation, use, and capability of blockchain for security in the purpose applied to
Accomplishments that I'm proud of
Successful implementation of blockchain technology through an intuitive web-based medium to address a heavily relevant and critical societal concern
What I learned
Application of ARK.io blockchain and security protocols
The multitude of transcriptional stages for encryption involving pass-phrases being converted to private and public keys
Utilizing JQuery to compile a comprehensive program
What's next for Block Vote
Expand Block Vote’s applicability in other areas requiring decentralized and trusted security, hence, introducing a universal initiative.


