# About Me

Hi there! My name is Matías Capuano, and I'm a Backend Developer from Argentina. I have experience working with a variety of technologies, including Node.js, TypeScript, NestJS, PostgreSQL, Docker, Redis, AWS, Kubernetes, Git, Terraform, Serverless, Microservices, and Clean Architecture.

## Skills and Experience

Here's an example of some of the skills I have:

```typescript
export type Person = {
  name: string;
  age: number;
  country: string;
  profession: string;
  skills: string[];
  otherSkills: string[];
};

const person: Person = {
  name: 'Matías Capuano',
  age: 25,
  country: 'argentina',
  profession: 'Backend Developer',
  skills: [
    'Node.js',
    'TypeScript',
    'NestJS',
    'PostgreSQL',
    'Docker',
    'Redis',
    'AWS',
    'Kubernetes',
    'Git',
    'Terraform',
    'Serverless',
    'Microservices',
    'Clean Architecture',
  ],
  otherSkills: ['React', 'Next.js'],
};

const toSentence = (array: string[]): string => {
  const last = array.pop();

  return `${array.join(', ')} and ${last}`;
};

const printPerson = (person: Person): void => {
  const { name, age, country, profession, skills } = person;

  console.log(`
    Hi, I'm ${name} from ${country}. I'm ${age} years old and I work as a ${profession}.
    I have experience working with ${toSentence(skills)}.
  `);
};

printPerson(person);
```

## Contact

If you want to get in touch, you can reach me at:

- [LinkedIn](https://www.linkedin.com/in/matiascapuano/)
- [Email](mailto:maticapuano97@gmail.com)
- [Phone](https://wa.me/542252416161)
