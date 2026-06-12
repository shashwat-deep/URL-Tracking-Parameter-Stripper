## My 4 week browser extension plan

### Prep work

I need to install Firefox and VS Code this weekend. I will make a public GitHub repo and just pick a random name so I do not waste time overthinking it. I am sticking to GitHub Desktop for now because the command line interface always slows me down. I also need an account on Hashnode or dev.to to post my updates. I will just dump this whole plan into a PLAN.md file for my first commit. I will draft and upload the first post on Sunday.

### Week 1 javascript basics and first post

I want to write basic string manipulation functions and publish my first blog post this week. I will read the javascript.info chapters on variables, data types, operators, conditionals, loops and functions. I have to actually code the exercises because just reading documentation never sticks. I will write a function to check if a string has trackers like fbclid or utm since that is the main logic for the extension.

### Week 2 advanced js and extension skeleton

I need to get a Firefox context menu working that logs a URL when someone clicks it. I will study objects, arrays and promises in JS. I will only learn enough async code to use the clipboard API. I also need to figure out URL and URLSearchParams objects.

I will follow the MDN borderify tutorial to see how Firefox loads extensions. Then I will set up my manifest.json for Manifest V3, configure the permissions for the context menu and clipboard, and write the background script. I need to remember the background script console is different from the regular webpage console. My Sunday post will cover how extension manifests work.

### Week 3 core features and submission

I plan to finish the extension and submit it to the Firefox store. I will code the main URL cleaner function to strip tracking parameters while keeping normal ones and the hash fragment. Modifying URL parameters during a loop usually causes bugs, so I will watch out for that.

I will use the clipboard API to copy the clean link. I will test the logic manually using messy URLs from Twitter and Facebook. I will draw a basic icon and submit the project to AMO. The extension requires zero host permissions, which is good for privacy. Sunday's post will explain tracking parameters and how my code removes them.

### Week 4 typescript and networking

I will rewrite the codebase in TypeScript and start messaging people online. I will install Node and TypeScript, configure tsconfig in strict mode, and translate my background script. Fixing the compiler errors will probably take a few hours. I will update the AMO submission after the code compiles. The final Sunday post will document the TS migration and the errors I faced.

I will update my Twitter and LinkedIn bios to say I am a 3rd year CSE student building privacy tools. I plan to reply to DevRel engineers from Appwrite and Postman and join their Discord servers to answer beginner questions.

### Daily schedule

I will spend 2 hours reading docs and coding on weekdays. I will keep a short log of my progress and bugs to make writing the Sunday post easier. If I get stuck on a bug for more than 20 minutes, I will note it down and move on so I do not waste my whole evening.

I will put in 3 hours on weekends. I will code and outline the blog post on Saturday. Sunday is just for drafting the post, doing one edit pass, and publishing it.

### Blog post 1 outline

My outline for the first blog post covers how annoying it is to copy a link and get 300 characters of tracking junk. I will explain what utm and fbclid actually do. I will introduce the extension I am building to fix this and explain why I am keeping the project small. I will mention I am starting from scratch with JS and link to swyx's learn in public post. Finally, I will list my plan for the next 4 weeks.

### People to study

I will study how a few specific people handle content and community building. I want to look at Shawn Wang for his learn in public framework and Salma Alam-Naylor for her tech blog structure. I will check Cassidy Williams to see how she adds personality to tutorials. I also want to study Troy Hunt for his privacy explanations and Kunal Kushwaha because he built a massive developer community in India and shows the exact DevRel path I want to take.

### Networking tasks

I will update my bio to say I am a 3rd year CSE student building in public. I will follow the creators I mentioned and DevRel engineers at companies I like. I will reply to their posts with real questions or thoughts rather than just saying nice post. I will share my blog posts as Twitter threads with screenshots of the extension working. I will also join the Postman and Appwrite Discords and answer beginner questions.
