# Python AI - Interview Transcript Summarizer

Python developer assessment task for the AI team.

## Scenario

Your team needs a microservice that summarizes interview transcripts. Your service receives an interview transcript that it needs to analyze & assess, and it is expected to return:

- A concise summary
- Matching Tags
- Sentiment analysis

## Requirements

- Write your backend in **FastAPI**
- Use **OpenAI** or **GeminiAPI** for the LLM
- Provide a `Dockerfile` and `docker-compose.yml` to run the service
- Your respository should include a README
- Record a short 5-minute video walking through your codebase, decisions and overall approach

## Submission Guidelines

- Work on your solution inside a **private** GitHub repository and invite `@ivan-instaffo`, `@vincenzo-instaffo` and `@PatrickLerner` as collaborators upon completion
- Provide a link to your short walk-through video (you can use Loom; anything is fine given it is easily accessible)
- Reach out as soon as you are finished and include the repository as well as the video link

## Tags

The tags are used to highlight key qualities demonstrated in the transcript

**Tags to use:** ["confident", "detailed", "collaborative", "analytical", "enthusiastic", "experienced", "curious", "structured", "innovative", "practical"]

## Sentiments

The sentiment helps reviewers quickly understand whether the candidate’s responses and the overall conversation were positive, negative, or neutral in nature.

**Sentiment values to use:** ["positive", "neutral", "negative"]

## Example response

```json
{
  "summary": "The candidate demonstrated strong analytical thinking and was able to break down complex problems effectively. Collaboration skills were evident throughout the interview.",
  "tags": ["analytical", "collaborative", "confident"],
  "sentiment": "positive"
}
```

## What we will assess:

- Overall structure and scalability
- Clean and maintainable code
- Well-defined API
- Simple API tests (minimum effort) enough to showcase your understanding on how unit tests should be written