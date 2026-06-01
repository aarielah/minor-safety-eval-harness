# Minor Safety Model Evaluation Harness

This is a weekend portfolio project designed for a TikTok Minor Safety model strategy / operations internship. It demonstrates the full loop of dataset standards, model evaluation, vulnerability analysis, and improvement recommendations.

## What It Shows

- A synthetic evaluation dataset with 120 policy-labeled teen-safety cases
- Labels for `allow`, `age_gate`, `needs_review`, `escalate`, and `remove`
- Coverage across bullying, grooming, self-harm, privacy, exploitation, misinformation, age-inappropriate content, and benign teen content
- Adversarial tags such as coded slang, emoji masking, multilingual phrasing, sarcasm, and benign lookalikes
- Simulated model profiles for baseline, optimized, and strict moderation behavior
- Metrics for accuracy, high-risk recall, false negatives, false positives, and confusion matrix analysis
- Actionable model improvement recommendations based on observed failures

## How To Use

Open `index.html` in a browser.

No API key or server is required. The model output is simulated so the dashboard can be reviewed instantly by a recruiter or hiring manager.

## Why This Matches The Role

The role asks for someone who can support model strategy and operations for minor safety, participate in data production, define dataset standards, execute model evaluations, identify vulnerabilities, and propose improvements. This project gives a concrete artifact for each of those responsibilities.

## Suggested Resume Bullet

Built a minor-safety model evaluation harness with 120 synthetic policy-labeled cases, adversarial coverage tags, simulated classifier profiles, confusion matrix analysis, and model improvement recommendations for high-risk teen-safety categories.

## Suggested Interview Talking Points

- I chose high-risk recall as a primary metric because missed grooming, exploitation, or self-harm cases carry higher safety cost than ordinary false positives.
- I separated `age_gate`, `needs_review`, `escalate`, and `remove` because content governance needs more than a binary safe/unsafe label.
- I included adversarial tags to reflect real-world moderation weaknesses, including coded language, emojis, sarcasm, multilingual phrasing, and context-dependent teen safety signals.
- I designed the project so it can later be connected to a real LLM API or moderation model without changing the evaluation schema.
