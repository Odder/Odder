### Hi there 👋

What's up? I hope you find what you are looking for here! 

<details>
<summary>Curriculum Vitae</summary>
  
**Request**

```graphql
{
  me {
    name
    positions(first: 3, orderBy: RECENT) {
      data {
        title
        startDate
        company {
          name
        }
      }
    }
    languagesOfExpertise(first: 3 orderBy: EXPERIENCE)
  }
}
```


**Response**

```json
{
  "me": {
    "name": "Oscar Roth Andersen",
    "positions": {
      "data": [
        {
          "title": "Technological Lead",
          "startDate": "2020-05-01",
          "company": {
            "name": "Clio ApS"
          }
        },
        {
          "title": "Full stack developer",
          "startDate": "2019-08-01",
          "company": {
            "name": "Clio ApS"
          }
        },
        {
          "title": "Backend Developer",
          "startDate": "2015-02-01",
          "company": {
            "name": "Loyalty Key"
          }
        }
      ],
    },
    "languagesOfExpertise": [
      "PHP",
      "Python",
      "JavaScript"
    ]
  }
}
```

</details

<!--
**Odder/Odder** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
