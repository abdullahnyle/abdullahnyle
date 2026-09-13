# Hey, I'm Abdullah

CS undergrad at UET Lahore. Most of what I build runs on Python and SQL, usually pointed at health data, databases, or some question I actually want the answer to. Outside of that I'm into fashion, supplements and health, fragrances, and working out.

## Projects

### [Label vs. Reality](https://github.com/abdullahnyle/label-vs-reality)

Do supplement labels actually add up? I pulled 214,780 label records from the NIH's dietary supplement database and used creatine as the test case, since it's well studied and usually labelled honestly. Turns out the answer depends a lot on how you ask the question: just choosing the smallest vs. the largest recorded amount per label swings the result by almost 10 percentage points. So I went back to the actual serving directions, checked some of them against the label images directly, and wrote up how the numbers moved as I dug deeper. Python, SQLite, real tests, and a case study that shows the work rather than just the conclusion.

### [FragBro](https://github.com/abdullahnyle/FragBro)

I wanted to know what I actually wear versus what just sits on the shelf, so I built something to track it. Started as a command-line tool for my own collection, grew into a small web app with a FastAPI backend and a React frontend. Handles collection records, wishlists, and wear logs, and tells me which bottles are getting real use.

### [Hospital Network Segmentation](https://github.com/abdullahnyle/hospital-network-segmentation)

A Cisco Packet Tracer build for a networking course, splitting a hospital network into four zones by clinical risk rather than physical layout, so a compromised guest laptop can't reach a medical device. Includes the configs, a Python checker, and honest notes on what I tested and what I didn't have time to confirm.

### [Secure Audit Log Gateway](https://github.com/abdullahnyle/secure-audit-log-gateway)

My piece of a 17-module group project for a secure exam system: an audit log that's hard to quietly tamper with. Each entry is chained to the one before it with a hash, and I wrote two independent verifiers, one in Python and one in JavaScript, so the check doesn't just trust the server it's checking.

Label vs. Reality is where I want to keep spending my time, health data has real stakes and real gaps worth digging into. FragBro was a smaller detour into the same instinct, not trusting the first easy answer, just aimed at something lower stakes.

## Find me

[LinkedIn](https://linkedin.com/in/abdullahnyle)
[Site](https://abdullahnyle.dev)
[Instagram](https://www.instagram.com/abdullahnyle/)
