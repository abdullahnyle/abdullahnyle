# Hey, I'm Abdullah

CS undergrad at UET Lahore. Most of what I build runs on Python and SQL, usually pointed at health data, databases, or some question I actually want the answer to. Outside of that I'm into fashion, supplements and health, fragrances, and working out.

## Projects

### [Label vs. Reality](https://github.com/abdullahnyle/label-vs-reality)

This is my main research project, built around a January 2026 NIH Dietary Supplement Label Database download with 214,780 label records. Using creatine as a case study, I found that the result changed substantially depending on how multiple recorded amounts were handled: 61.0% reached a 3 g reference using the smallest recorded amount per label, compared with 70.7% using the largest.

I then reviewed 44 written serving directions and checked selected records against their original label images. One unresolved discrepancy, DSLD record 337727, was documented and reported to NIH/ODS for clarification rather than being treated as a confirmed error. The repo includes the Python and SQLite workflow, tests, review records, and the case study showing how the analysis changed as the method improved.

### [FragBro](https://github.com/abdullahnyle/FragBro)

I built FragBro because I wanted a better way to track what fragrances I actually wear, not just what I own. The local CLI manages my collection, wishlist, and wear history in SQLite, while a FastAPI backend and React frontend expose the data through a read-only web app.

It started as a simple personal tracker and grew into a small full-stack app. I added validation around wear logging, reproducible checks for the statistics, and consistent date handling across the CLI and API. The public demo is intentionally read-only, while collection and wear updates stay local.

### [Hospital Network Segmentation](https://github.com/abdullahnyle/hospital-network-segmentation)

A Cisco Packet Tracer coursework project where I split a small hospital network into four VLANs and used router ACLs to enforce a simple access policy. The repo includes the router and switch configurations, a Python policy checker, and notes on what was tested, what was corrected, and what remains outside the demonstrated scope.

### [Secure Audit Log Gateway](https://github.com/abdullahnyle/secure-audit-log-gateway)

My module in a 17-part class project for a secure exam system. It uses FastAPI and MongoDB for structured audit logging, authenticated writes and admin queries, and hash-linked entries for integrity checks. The README also explains where those checks stop being trustworthy instead of presenting the hash chain as stronger than it really is.

Label vs. Reality is the kind of work I want to keep doing: working with real data, checking assumptions when the first answer looks too neat, and ending up with something I can actually defend. I'm especially interested in health informatics, applied data science, information systems and decision support.

## Find me

- LinkedIn: [@abdullahnyle](https://linkedin.com/in/abdullahnyle)
- Site: [abdullahnyle.dev](https://abdullahnyle.dev)
- Instagram: [@abdullahnyle](https://www.instagram.com/abdullahnyle/)
