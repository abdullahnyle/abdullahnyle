# Hey, I'm Abdullah

I'm a CS student at UET Lahore, interested in health informatics: how people make sense of health information, and how it could be made clearer for them. I mostly work in Python and SQL, but the part I enjoy most is finding out what's really going on, whether that's in a dataset or in how people use it. Outside of that I'm into fashion, supplements and health, fragrances, tech and working out.

## Projects

### [Label vs. Reality](https://github.com/abdullahnyle/label-vs-reality)

My main project. I took a January 2026 download of the NIH Dietary Supplement Label Database (214,780 labels) and asked a simple question: how often do creatine labels reach a 3 g daily amount? The answer depended on one choice. Using the smallest recorded amount on each label, 61.0% did. Using the largest, 70.7%.

So I went back to the source, read 44 sets of serving directions and checked original label images by hand. One record didn't match its printed label, so I documented it and reported it to the NIH's Office of Dietary Supplements instead of calling it an error. The repo has the full Python and SQLite workflow, tests, and every review record.

Next, I'm taking it to the people side: talking to creatine users in different countries about how they read labels and decide how much to take.

### [FragBro](https://github.com/abdullahnyle/FragBro)

I built FragBro because I wanted a better way to track what fragrances I actually wear, not just what I own. The local CLI manages my collection, wishlist, and wear history in SQLite, while a FastAPI backend and React frontend expose the data through a read-only web app.

It started as a simple personal tracker and grew into a small full-stack app. I added validation around wear logging, reproducible checks for the statistics, and consistent date handling across the CLI and API. The public demo is intentionally read-only, while collection and wear updates stay local.

### [Hospital Network Segmentation](https://github.com/abdullahnyle/hospital-network-segmentation)

A Cisco Packet Tracer coursework project where I split a small hospital network into four VLANs and used router ACLs to enforce a simple access policy. The repo includes the router and switch configurations, a Python policy checker, and notes on what was tested, what was corrected, and what remains outside the demonstrated scope.

### [Secure Audit Log Gateway](https://github.com/abdullahnyle/secure-audit-log-gateway)

My module in a 17-part class project for a secure exam system. It uses FastAPI and MongoDB for structured audit logging, authenticated writes and admin queries, and hash-linked entries for integrity checks. The README also explains where those checks stop being trustworthy instead of presenting the hash chain as stronger than it really is.

## What I'm working towards

The work I want to keep doing sits between health information and the people using it: checking what the data really says, finding out what people actually take from it, and designing something clearer. I'm especially interested in health informatics, consumer health and user research.

## Find me

- LinkedIn: [@abdullahnyle](https://linkedin.com/in/abdullahnyle)
- Site: [abdullahnyle.dev](https://abdullahnyle.dev)
