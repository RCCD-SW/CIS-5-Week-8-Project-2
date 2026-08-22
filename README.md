# Practice 8 · Weather week

**Week 08 · Arrays**  
**Theme:** Many values, one name


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:** _add your link here_


## What to build
Seven temperatures in one array. Print each day. Report the average and the hottest **index** (and its value). Count how many days were “hot” by a rule you name.

## Requirements
- `double temps[7]` (or `const int N = 7`)
- Print day index + temp
- Average + hottest day index
- A filtered count (for example days ≥ 80)
- README lists the seven numbers

## Sample output
```
[0] 72
[1] 75
[2] 81
[3] 88
[4] 77
[5] 90
[6] 69
Avg: 78.8571
Hottest index: 5 (90)
Hot days (>= 80): 3
```

## Starter
`main.cpp` — or continue from the lab with N = 7.

## Deliverables
1. Course-visible GitHub repo
2. README with the data listed
3. Short demo video (tool + code + run)
4. Canvas links

## Scope fence
1D only. No sorting required. No pointers or files.

## Integrity
- AI = tutor, not ghostwriter
- Fake ownership → zero
- Due: Monday night (not Sunday)
- Discussions (every week): first post Friday, replies Sunday
- Late: course policy (−10%/day unless stated otherwise)

## Rubric
Graded on: it runs, it meets the prompt, output is labeled, and the GitHub repo plus demo video are there.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
