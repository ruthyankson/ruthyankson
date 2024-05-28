![My GitHub profile image](https://github.com/ruthyankson/ruthyankson/blob/main/mybannergif.gif)
### Hola amigo👋

I'm Ruth. I love building technology for a positive impact on humanity :raised_hands: 

🎯 I’m currently working on [Hymnal App](https://github.com/ruthyankson/hymnal)

📫 Let's connect!:

[![Follow on Twitter](https://img.shields.io/badge/--twitter?label=Twitter&logo=Twitter&style=social)](https://twitter.com/adwowaray) [![Connect on LinkedIn](https://img.shields.io/badge/--linkedin?label=LinkedIn&logo=LinkedIn&style=social)](https://www.linkedin.com/in/ruthyankson)

⚡ Fun fact: I stress the stressors; that's how I fight stress. 😁

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

---

### 👩‍💻 Recent Activity
<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---
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
