```python
class Dheeraj:
    def __init__(self):
        self.full_name = 'D Dheeraj'
        self.role = [
            'Founder of istiva.world',
            'Full-stack developer'
        ]
        self.skills = {
            'languages': [
                'Python',
                'JavaScript',
                'Solidity',
                'C/C++',
                'Java',
                'HTML',
                'CSS'
            ],
            'frameworks/libraries': [
                'Django',
                'React js',
                'NumPy',
                'Pandas',
                'scikit-learn',
                'Open CV',
                'Beautiful Soup',
                'Express js',
                'Hardhat'
            ],
            'databases': [
                'MongoDB',
                'Neo4j'
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
            'Playing cricket, basketball, etc',
            'Reading self development books'
        ]
        
    def get_info(self):
        return vars(self)
        

if __name__ == '__main__':
    dheeraj = Dheeraj()
    print(dheeraj.get_info())
```
