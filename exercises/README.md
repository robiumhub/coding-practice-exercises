# Coding Practice Exercises

This repository contains coding exercises for daily practice.

## Structure

Each exercise is a JSON file with the following structure:

```json
{
  "slug": "unique-identifier",
  "title": "Exercise Title",
  "description": "Markdown description",
  "starterCode": "function solution(input) { }",
  "solutionCode": "Complete solution",
  "testCases": [
    { "input": "...", "expected": "..." }
  ],
  "difficulty": "easy|medium|hard",
  "category": "arrays|strings|dp|..."
}
```

## Adding New Exercises

1. Create a new JSON file in the `exercises/` folder
2. Follow the structure above
3. Sync from the app to import new exercises
