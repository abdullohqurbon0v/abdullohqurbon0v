# 🚀 Hey there, I'm Abdulloh Qurbonov

> *“Building the web, pixel by pixel. From idea 💡 to deployment 🚀”*

[![Instagram](https://img.shields.io/badge/@abu_developer._-f542e0?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/abu_developer._)
[![Telegram](https://img.shields.io/badge/@abdulloh_qurbonovvv-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/abdulloh_qurbonovvv)
[![Website](https://img.shields.io/badge/My%20Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://abdullohfolio-3.vercel.app/)

---

## 🧠 Who Am I?

I'm a frontend developer who loves turning ideas into interactive, high-performance user experiences.  
Working with modern tech like **Next.js**, **React**, **Tailwind CSS**, and **TypeScript**,  
I craft clean UI with a pinch of magic ✨

```js

const Abdulloh = {
  name: "Abdulloh Qurbonov",
  role: "Frontend Developer",
  location: "🌍 Earth",
  portfolio: "https://abdullohfolio-3.vercel.app",
  contact: {
    email: "abdullohqurnobov@gmail.com",
    telegram: "@abdulloh_qurbonovvv",
    instagram: "@abu_developer._"
  }
}

const skills = {
  frontend: ["HTML", "CSS", "JavaScript", "React", "Next.js", "TypeScript", "Tailwind CSS"],
  backend: ["Node.js", "Express", "MongoDB", "Prisma"],
  stateManagement: ["Redux", "Zustand", "Tanstack Query"],
  uiUX: ["Figma", "Framer Motion", "Styled Components"],
  tools: ["VSCode", "Git", "Postman", "Docker", "Vercel"]
}

const currentlyLearning = [
  "Framer Motion",
  "Advanced Animations",
  "Accessibility (a11y)",
  "Design Systems"
]

const devPhilosophy = [
  "💡 Simple > Complex",
  "🧼 Clean UI = Better UX",
  "📦 Reusable components everywhere",
  "⚙️ Automate where possible",
  "🧠 Never stop learning"
]

const goals2025 = {
  contributeToOpenSource: true,
  buildSaaSProduct: true,
  masterDesignSystems: true,
  speakAtMeetup: false, // maybe soon 😉
  hit100GitHubStars: true
}

function getTechStackMessage(stack) {
  if (stack.includes("Next.js") && stack.includes("Tailwind CSS")) {
    return "🔥 You’re in the modern frontend zone!";
  } else if (stack.includes("React")) {
    return "⚛️ Classic React lover, I see!";
  } else {
    return "🤓 Just exploring all the stacks!";
  }
}

function printGoals(goals) {
  console.log("🎯 2025 Goals:");
  for (const [goal, status] of Object.entries(goals)) {
    console.log(`- ${goal}: ${status ? "✅" : "🔜"}`);
  }
}

function printLearning(list) {
  console.log("📚 Currently Learning:");
  list.forEach((item, index) => {
    console.log(`${index + 1}. ${item}`);
  });
}

function intro(dev) {
  console.log(`👋 Hi, I’m ${dev.name}`);
  console.log(`💼 I'm a ${dev.role} based on ${dev.location}`);
  console.log(`🌐 Check out my portfolio → ${dev.portfolio}`);
  console.log(`📬 Let's connect → Telegram: ${dev.contact.telegram}`);
}

function startReadme() {
  intro(Abdulloh);
  console.log("\n⚙️ Tech Stack:");
  console.log(skills.frontend.join(" | "));
  console.log(getTechStackMessage(skills.frontend));
  printLearning(currentlyLearning);
  printGoals(goals2025);
  console.log("\n💡 My Dev Philosophy:");
  devPhilosophy.forEach(p => console.log(p));
}

// 🟢 Run virtual README startup
startReadme();


