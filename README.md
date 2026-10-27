# [Specific Working Project Title]

> **DSA 495 Topic Brief**
>
> Replace the bracketed prompts below with your team’s information. Keep this file at the root of your team’s project repository and name it `README.md`.

## Before You Begin

- Create **one shared project repository per team** and continue using it through the end of the semester. Do not create separate repositories for the Topic Brief and later stages of the project.
- The repository name must begin with the case-sensitive prefix **`DSA495`**, such as `DSA495-news-classification`. After the prefix, feel free to choose a creative and distinctive team name; it does not have to describe your task or topic. A repository whose name does not begin with `DSA495` will receive zero credit for the Topic Brief.
- Complete every required section and item below. Anything labeled optional may be left undecided! If another required item does not apply, write “Not applicable” and briefly explain why. Feel free to add sections as needed, but keep the brief concise.
- Make sure the repository is accessible to the instructor by choosing one of the following options:
  1. **Public repository:** No collaborator invitation is required.
  2. **Private repository:** Add the instructor as a collaborator using the GitHub username `SerenaYKim`.
- Do not upload sensitive or restricted information to GitHub, even in a private repository. If your project uses such data, keep it in a shared team drive and use GitHub for code, documentation, and other materials that can be shared safely.

## Team Members

- Grishma Kuikel 

## One-Sentence Task

Given written patient reviews of medications, we will classify the reviews based on patient satisfaction and analyze common themes related to treatment benefits and side effects.

## Illustrative Input and Desired Output

- **Example input:** "This medication helped my symptoms, but it made me feel tired and dizzy."

- **Desired output:** The system classifies the review as mixed sentiment and identifies common themes such as treatment effectiveness and side effects.

## Background and Starting Point

I became interested in this topic because I often experience random symptoms and sometimes worry that they could be signs of a bigger health problem. This made me curious about how other people experience and describe their symptoms, especially when taking medications. I wanted to explore whether text analysis could help identify common patterns in patient reviews, such as side effects, treatment effectiveness, and overall satisfaction. Using the Drug Reviews dataset from the UCI Machine Learning Repository, I hope to better understand how people describe their experiences with different medications.
## Intended Output and Success

The goal of this project is to analyze patient medication reviews and classify them as positive, negative, or mixed based on their experiences. We also want to identify common themes, such as side effects and how well medications work. The results could help patients better understand other people's experiences with medications and recognize common concerns. My project will be successful if it can accurately classify reviews and identify useful patterns in patient feedback.

**Success statement:** The project will be successful if it can accurately classify patient reviews and identify common side effects and experiences that help people better understand medications.

## Preferred Data

### Corpus

We will use the Drug Reviews (Druglib.com) dataset from the UCI Machine Learning Repository. The dataset contains approximately 4,143 patient medication reviews. Each row represents one patient's experience with a medication. The dataset includes written reviews about medication benefits, side effects, and overall experiences, along with ratings and other information. We will use the text reviews to classify patient experiences as positive, negative, or mixed and identify common patterns in side effects and treatment effectiveness.

### Source and Access

- **Dataset or corpus name:** Drug Reviews (Druglib.com)
- **Original source organization or creator:** DrugLib.com, with the dataset made available through the UCI Machine Learning Repository.
- **Original collection process:** DrugLib.com collected patient reviews submitted by users about their experiences with medications. The reviews include information about benefits, side effects, and overall satisfaction. The exact collection dates are not clearly specified.
- **Direct link:** https://archive.ics.uci.edu/dataset/461/drug
- **Access method:** Download the dataset directly from the UCI Machine Learning Repository.
- **Access, licensing, privacy, or redistribution considerations:** The dataset contains user-submitted health experiences. We will use it for educational purposes, avoid sharing personal information, and check the dataset's usage restrictions before uploading any raw data to GitHub.
- **Backup corpus (optional):** Not needed at this stage.

### Examples

1. **Positive review:** A patient describes how a medication helped improve their symptoms and made them feel better.

2. **Negative review:** A patient explains that a medication caused side effects such as headaches, dizziness, or nausea.

3. **Mixed review:** A patient says the medication worked well for their condition but also caused uncomfortable side effects.

These are hypothetical examples of the types of reviews we expect to analyze from the dataset.

### Fit with the Task

This dataset fits our project because it contains written patient reviews about medications, including their benefits, side effects, and overall experiences. These reviews provide the text needed to identify common themes and classify patient experiences as positive, negative, or mixed. The dataset also includes ratings that could help us evaluate our classifications. However, it does not provide exact sentiment labels, so we may need to create our own labels or use sentiment analysis tools.

## Feasibility and Immediate Next Steps

- **Minimum viable project:** I will analyze a sample of patient medication reviews and use Python to classify them as positive, negative, or mixed. I will also identify common themes related to side effects and treatment effectiveness.

- **Data-access check:** I found the Drug Reviews dataset on the UCI Machine Learning Repository but have not downloaded it yet. My next step is to download and explore the data.

- **Largest current risk:** The biggest challenge may be accurately classifying reviews because some patients describe both positive and negative experiences in the same review.

- **Backup plan:** If classifying reviews into three categories becomes too difficult, I will simplify the project by focusing on positive and negative reviews or identifying common themes.

- **Next two actions:**
  1. Download the dataset and explore its variables using Python — Team members — October 28, 2026.
  2. Clean the text data and begin testing sentiment classification methods — Team members — November 2, 2026.

## Possible Text-Analysis Method and Evaluation (Optional)

[If your team already has ideas, name one or more text-analysis methods you may try. Then explain how you might judge whether the output performs well or is useful—for example, with a baseline, labeled test examples, appropriate metrics, retrieval checks, human review, error analysis, or comparison across approaches. It is acceptable to write “Not yet decided” and ask for guidance below.]

## Questions for the Instructor

- Would sentiment analysis be a good method for classifying patient medication reviews as positive, negative, or mixed?

-Would analyzing common side effects and treatment effectiveness be a manageable scope for this project, or should we focus on just one?

## AI-Use Statement

I used ChatGPT at the beginning of the project to remind myself how to copy the README template into my own GitHub repository because I had forgotten the steps. Before using AI, I had already reviewed the project instructions. For lengthy written answers I used Ai for checking grammar, giving it a prompt like,"don't change the wording but fix my grammar". 
