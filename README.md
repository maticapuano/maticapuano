# Hi! I'm Matias 👋👋

## 🙎🏻‍♂️ About me

### // About.ts

```ts
  export interface Person = {
    name: string;
    age: number;
    country: string;
    profession: string;
    skills: string[];
    devops: string[];
    testing: string[];
  }  
  const me: Person = {
    name: 'Matías Capuano',
    age: 23,
    country: 'Argentine',
    profession: 'Backend developer',
    skills: ['Typescript', 'Node.js', 'postgres','mysql','mongodb','redis','solid','desing-patterns'],
    devops: ['docker','k8s'],
    testing: ['jest']
  }
  const toString(person: Person): string => {
    const greeting: string = `Hi! I'm ${person.name}, have ${person.age} years old, and I'm ${person.profession}`
    return greeting;
  }
  console.log(toString(me));
  console.log('My main skills are => ', me.skills);
  console.log('Thank you for visiting me!');
```

### 🤝🏻 Contact

[E-mail](mailto:maticapuano97@gmail.com)
[Linkedin](https://www.linkedin.com/in/matias-capuano/)
