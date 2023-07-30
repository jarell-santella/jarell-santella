# Hello there!

You have made it to my GitHub profile! Let's query some more information about me...

```js
githubDB> db.users.find({ githubUsername: 'jarell-santella' }, { _id: 0, githubUsername: 0 })
[
    {
        name: 'Jarell Santella',
        email: 'jarell_santella@sfu.ca',
        occupation: 'software engineer',
        industry: 'software development',
        yearsOfExperience: 2,
        skills: [
            'software engineering',
            'data engineering',
            'backend development',
            'full stack development',
            'web application development',
            'mobile applicaton development',
            'desktop application development',
            'data science'
        ],
        education: [
            {
                university: 'Simon Fraser University',
                degree: 'Bachelor of Science',
                major: 'Computer Science',
                specializations: ['artificial intelligence', 'information systems'],
                currentlyPursuing: true
            }
        ],
        hobbies: [
            'coding',
            'building computers',
            'video games',
            'video editing',
            'traveling'
        ],
        socialAccounts: {
            linkedin: 'https://linkedin.com/in/jarell-santella',
            github: 'https://github.com/jarell-santella'
        }
    }
]
```
