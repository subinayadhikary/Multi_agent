# ArguGenCourt: Courtroom Argument Generation using Judicial Multi-agent Large Language Models
In this paper, we consider solely legal cases from the U.S. Supreme Court and evaluate the performance of Large Language Models (LLMs) in generating courtroom arguments utilizing different approaches, including zero-shot, and few-shot within a multi-agent setup called ArguGenCourt.
# 1. Methods of Utterances Selection :
![Image](https://github.com/user-attachments/assets/3a5cea0d-a6d5-433e-8a3e-9d684c77c091)
We show that, for selecting the utterances from the same document, we explore two approaches: random selection (ad-hoc) and score-based selection. In the score-based selection, we provide the case-specific closest utterances as examples in the first round conversation, depending on the similarity score between generated arguments and real-life arguments, termed as guided few-shot. Subsequently, ArguGenCourt produces two sets of arguments: one between judge and petitioner and the other between judge and respondent agent. Finally, we evaluate the generated arguments for both the petitioner and respondent.
