![My GitHub profile image](https://github.com/ruthyankson/ruthyankson/blob/main/mybannergif.gif)
# Hola amigo👋

I'm Ruth. I love building technology for a positive impact on humanity :raised_hands: 

🎯 I’m currently working on [Hymnal App](https://github.com/ruthyankson/hymnal)

<h2>

🛠️ My Toolset:

</h2>

<p >
  
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Git](https://img.shields.io/badge/-git-F1502F?style=for-the-badge&logo=git&logoColor=white)
![Github](https://img.shields.io/badge/-github-161B22?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4EA94B?style=for-the-badge&logo=postgresql&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-00599C?style=for-the-badge&logo=angular&logoColor=722f37)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-E95420?style=for-the-badge&logo=Postman&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

</p>

---

## 📫 Let's connect!: [![Follow on Twitter](https://img.shields.io/badge/--twitter?label=Twitter&logo=Twitter&style=social)](https://twitter.com/adwowaray) [![Connect on LinkedIn](https://img.shields.io/badge/--linkedin?label=LinkedIn&logo=LinkedIn&style=social)](https://www.linkedin.com/in/ruthyankson)


## ⚡ Fun fact: I stress the stressors; that's how I fight stress. 😁

<!--
// Task interface
interface Task {
  id: number;
  task_name: string;
  size: number;
  priority: number;
  stress_percentage: number;
  in_progress: boolean;
  completed: boolean;
}

// Array of tasks (note the commas between array elements)
const work: Task[] = [
  { id: 1, task_name: "Update social media presence", size: 15, priority: 4, stress_percentage: 12, in_progress: true, completed: false },
  { id: 2, task_name: "Personal growth", size: 10, priority: 2, stress_percentage: 25, in_progress: true, completed: false },
  { id: 3, task_name: "Jobs", size: 5, priority: 2, stress_percentage: 30, in_progress: true, completed: false }
];

// Calculate the total stress level of all tasks
function calculateStressLevel(tasks: Task[]): number {
  let totalStressLevel = 0;
  tasks.forEach((task) => {
    totalStressLevel += task.stress_percentage;
  });
  return totalStressLevel;
}
-->
```ts
// Remove stress from tasks
function removeStress(tasks: Task[]): void {
  let stress_level: number = calculateStressLevel(tasks);

  while (stress_level > 0) {
    tasks.forEach((task) => {
      // Complete tasks with no stress
      if (task.stress_percentage === 0) {
        task.completed = true;
        task.in_progress = false;
      } else if (task.in_progress) {
        // Reduce stress for tasks in progress
        task.stress_percentage--;
      }
    });
    // Recalculate the total stress level
    stress_level = calculateStressLevel(tasks);
  }
}

removeStress(work);
```


<!--
**AdwowaRay/AdwowaRay** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
