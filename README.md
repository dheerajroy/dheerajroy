```python
class Dheeraj:
    def __init__(self):
        self.full_name = 'D Dheeraj'
        self.age = 20
        self.role = [
            'Full-stack developer'
        ]
        self.achievements = [
            'One of the 40 students selected for the GDC Software Engineering Fellowship Program in India in the year 2021',
            'Certified Python & Machine Learning developer in the year 2019'
        ]
        self.skills = {
            'languages': [
                'Python',
                'JavaScript',
                'TypeScript',
                'Solidity',
                'C/C++',
                'Java',
                'HTML',
                'CSS'
            ],
            'frameworks/libraries': [
                'Django',
                'FastAPI',
                'Flask',
                'React js/Next js',
                'NumPy',
                'Pandas',
                'Scikit-learn',
                'Open CV',
                'Beautiful Soup',
                'Express js',
                'Hardhat',
                'Bootstrap',
                'Tailwind CSS'
            ],
            'databases': [
                'MongoDB',
                'Neo4j',
                'MySQL'
            ],
            'platforms': [
                'FireBase',
                'VS Code',
                'Pycharm',
                'Eclipse',
                'Heroku',
                'DigitalOcean'
            ]
        }
        self.hobbies = [
            'Coding',
            'Analysing businesses/companies',
            'Playing cricket, basketball, etc',
            'Reading self development books'
        ]
        
    def get_info(self):
        return vars(self)
        

if __name__ == '__main__':
    dheeraj = Dheeraj()
    print(dheeraj.get_info())
```
