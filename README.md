# Workout Wizard
This program generates a random bodyweight workout. For any given workout length, create over 6,000 unique workouts so you're always stressing your body in new and exciting ways.


# Usage
```bash
python3 python/main.py
```
Or run with pipenv:
```
pipenv run python3 python/main.py
```

Creates a randomized bodyweight workout, taking these inputs in CLI:

- Workout length in minutes
- Cardio option
- Desired output location of text file containing workout

It samples random exercises from python/options.csv, which you can modify for more variety.

# Prerequisites
- Python 3.8 or higher
- Required libraries: pandas, prompt_toolkit
- CSV file (options.csv) with exercise options and attributes

# Setup
- Clone the repository.
- Install the required Python libraries using pip install pandas prompt_toolkit.
- Update the options.csv file with your preferred exercises and attributes.
- Run the script and follow the prompts to generate your workout plan.

# Example workout

```
Printed: 2024-07-21, Sunday

Workout length: 18.0 mins 
Sets: 6 
Reps: 6 
Rest: 90 seconds 
 
ruck military press
navy seal
ruck push up
3 pump burpee
Push-up
ruck shoulder raise

Set checkbox [1] [2] [3] [4] [5] [6] 
```
