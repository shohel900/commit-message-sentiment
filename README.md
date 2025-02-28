# commit-message-sentiment
Commit Message Sentiment is a project dedicated to publishing a comprehensive dataset of commit messages, enriched with sentiment analysis. The dataset includes commit data from various open source projects, categorized by sentiment, issue type, and other relevant metadata.
## Dataset Origin

The dataset is derived from the 20-MAD (20-Year Massive Software Artifact Data) dataset, which integrates commit and issue data from Mozilla and Apache projects spanning over 20 years. Our dataset builds upon this foundation by adding sentiment analysis annotations to commit messages.

## Overview

The dataset includes:
- Commit messages from various open-source projects.
- Sentiment analysis of each commit message using a fine-tuned seBERT model.
- Metadata such as commit times, contributor categories, and issue types (bug/non-bug).

## Dataset Details

- **Projects Covered**: 113 Apache projects
- **Total Commits**: 630,164
- **Sentiment Analysis**: Each commit message is annotated with the sentiment (positive, negative and neutral).
- **Metadata Included**:
  - Commit messages
  - Commit times
  - Contributor categories
  - Issue types (bug/non-bug)
  - "Part of the day" based on commit time

## Usage

The dataset is provided in excel format. Due to large file size we split the dataset into five different parts. You can combine those and use it for various research purposes, including but not limited to:
- Sentiment analysis in software development
- Analyzing the relationship between commit sentiment and project outcomes
- Studying contributor behavior and patterns in open-source projects

## Contact

For any questions or inquiries, please contact a.shohel@gmail.com


