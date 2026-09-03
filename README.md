# Resume Skill Extraction using NLP

## Project Overview

This project focuses on extracting skills and keywords from resumes using Natural Language Processing (NLP).

A rule-based keyword matching approach is used to identify skills from resume text and compare the extracted skills with the skills provided in the dataset.

## Objectives

- Extract skills from resume text.
- Preprocess and normalize skill data.
- Compare extracted skills with the actual skills in the dataset.
- Evaluate the performance using Precision, Recall and F1-score.

## Dataset

The dataset contains 220 resumes stored in JSON format.

Each resume contains:
- Resume ID
- Resume text
- Skill information

## Methodology

The project follows these steps:

1. Load the resume dataset.
2. Extract resume text and skill information.
3. Preprocess the skill vocabulary.
4. Normalize and filter skills.
5. Perform keyword-based skill matching.
6. Extract skills from each resume.
7. Compare predicted skills with actual skills.
8. Calculate Precision, Recall and F1-score.

## Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)

## Results

The system was evaluated on all 220 resumes.

- Precision: 52.77%
- Recall: 52.58%
- F1-score: 52.68%

Average actual skills per resume: 58.25

Average extracted skills per resume: 58.03

## Limitations

The rule-based approach depends on the available skill vocabulary and may miss skills when different wording is used. It may also identify some general words that are not considered skills in the dataset.

## Future Scope

The system can be improved using more advanced NLP techniques such as TF-IDF, similarity-based approaches, machine learning, or transformer-based models.

## Project Files

- `Resume_Skill_Extraction_NLP.ipynb` – Complete project implementation
- `resume_skill_extraction_results.csv` – Extracted skill results

## Conclusion

This project demonstrates how NLP and rule-based keyword matching can be used to extract skills from resumes and evaluate the extraction performance using standard classification metrics.
