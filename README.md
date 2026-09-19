# Hey, I'm Abdullah

CS undergrad at UET Lahore. Most of what I build runs on Python and SQL, usually pointed at health data, databases, or some question I actually want the answer to. Outside of that I'm into fashion, supplements and health, fragrances, and working out.

## Projects

### [Label vs. Reality](https://github.com/abdullahnyle/label-vs-reality)

This is my main research project, built around a January 2026 NIH Dietary Supplement Label Database download with 214,780 label records.

Using creatine as a case study, I found that the result changed substantially depending on how multiple recorded amounts were handled: 61.0% reached a 3 g reference using the smallest recorded amount per label, compared with 70.7% using the largest.

I then reviewed 44 written serving directions and checked selected records against their original label images. One unresolved discrepancy, DSLD record 337727, was documented and reported to NIH/ODS for clarification rather than being treated as a confirmed error.

The repo includes the Python and SQLite workflow, tests, review records, and the case study showing how the analysis changed as the method improved.

### [FragBro](https://github.com/abdullahnyle/FragBro)

I wanted to know what I actually wear versus what just sits on the shelf, so I built something to track it. The command-line app records my collection, wishlist, and wear history in SQLite. A FastAPI backend and React frontend provide a read-only public demo of the project.

### [Hospital Network Segmentation](https://github.com/abdullahnyle/hospital-network-segmentation)

A Cisco Packet Tracer build for a networking course, splitting a hospital network into four zones by clinical risk rather than physical layout. It includes the configurations, a Python policy checker, and notes on what I tested and what remains outside the demonstrated scope.

### [Secure Audit Log Gateway](https://github.com/abdullahnyle/secure-audit-log-gateway)

My component of a 17-module class project for a secure exam system. It provides structured audit logging with FastAPI and MongoDB, authenticated writes and queries, hash-linked log entries, and integrity checks. The repository documents what those checks can and cannot establish.

Label vs. Reality is where I want to keep spending my time. Health data has real stakes and real gaps worth investigating. FragBro was a smaller project driven by the same instinct to look past the first easy answer, applied to something lower stakes.

## Find me

- LinkedIn: [@abdullahnyle](https://linkedin.com/in/abdullahnyle)
- Site: [abdullahnyle.dev](https://abdullahnyle.dev)
- Instagram: [@abdullahnyle](https://www.instagram.com/abdullahnyle/)
