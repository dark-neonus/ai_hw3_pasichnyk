# For Agents

## Goals

1. Full points for tasks(ai_hw3_paasichnyk/Context/Task.md)
2. Highest score on leaderboard with prudent effort and without violating other goals
3. Full user understanding of homework, data, approaches, models and final pipeline

## Style

Style of text in notebooks and report should priore follow task requirements.

When it doesnt violate task requirement:

1. Write text convenient and easy to understand, still with full related vocabularly
2. If you use some metrics, acrevations, models, etc, state their full name and explanation in relevant places, so if user forget abbrevation or what does metric mean, they can recall it in text
3. Use visualizations to explain concepts and how models work under the hood. When relative, do this in notebooks. If not relevant, use this in separate file for defence prep.
4. When drawing charts or diagrams, draw them readable and meanigfull with short explanations each
5. Follow all basic and best practises in AI/ML field, e.g. avoid and check for data leakage, use cross validation, use meanighfull metrics, etc.

## Structure

Follow recomendations from task description.

You can get reference from previous homework structure, but only file structure:
```
dark-neonus@NeonMachine /m/D/u/a/hw2_ai_bugir_pasichnyk (main)> tree -L 1
.
├── assets
├── Context
├── data
├── download_data.sh
├── images
├── index.html
├── kernels
├── notebooks
├── prep
├── pyproject.toml
├── README.md
├── report.md
├── requirements.txt
├── results
├── runs
├── src
└── wandb
```

## Prep for defence

Notebooks should be as self explanatory as possible, but still them laconic without huge text explanations.
Since full explanations are too big for notebooks and report, notebooks should be good to recall things learned from defence prep files and define standalone things(like mentioned earlier, scores, avrreviations, etc)

There should be files to prepare for defence. Format is preffered to be HTML. Do not generate a bunch of slop. Core things, explanations how things work under the hood, keep it simple stupid. Short-Medium size files for prep, estimate time to process them is 1 hour.

This files should be introduced as milestones. So when you done basic implementation, you write prep explanation for that, for metrics, for each individual simple approach(like basic models). When done final pipeline(e.g. choosen stronger model of my choise, not from basic sts of previous models), create prep explanation for it, its models, etc. When done final strongest pipeline, create prep for it.

## Interaction with Kaggle

Interaction with Kaggle is on you. Create scripts for that, e.g. script to upload prediction/model/whatever. Take in mind that there is the limit of 5 submission per day, so use them thoughtfull, only after validated that model is strong locally. If you need, you can ask to enter Kaggle PAT(say how to create one if needed), but in VS Code protected store or something liek that. If you know better way to interact with kaggle(e.g. official mcp) suse it.

