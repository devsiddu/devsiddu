```ts
class About extends Me {
  getName() {
    return {
      name: "Siddu Mokhasi",
      github: "devsiddu",
      location: "Gokak, Karnataka, India",
    };
  }

  getCurrentWorkplace() {
    return {
      workplace: {
        company: "Gokak Textiles Ltd",
        position: "Software Engineer",
        since: "Aug 2025",
      },
    };
  }

  getSummary() {
    return "I build reliable, scalable web and business applications.";
  }

  getWhatIBuild() {
    return [
      "Enterprise Applications",
      "Full-Stack Applications",
      "Database Systems",
      "Mobile Applications",
    ];
  }

  getDailyKnowledge() {
    return {
      languages: ["Java", "JavaScript", "PHP", "Python", "C", "C#"],
      frontend: ["React", "HTML", "CSS", "Bootstrap", "Tailwind CSS"],
      backend: ["PHP", "Java", "Node.js", "REST APIs"],
      databases: ["SQL Server", "MySQL", "MongoDB", "Oracle"],
      mobile: ["React Native", "Android"],
      tools: ["Git", "GitHub", "VS Code", "Eclipse", "NetBeans", "Figma"],
    };
  }

  getProjects() {
    return [
      {
        name: "GEPMS",
        about: "Power generation and sales entry/management system",
        status: "Production, used daily at Gokak Textiles",
      },
      {
        name: "Smart Attendance + Payroll",
        about: "PHP attendance system with integrated payroll",
        repo: "github.com/devsiddu/smart-attendence-php",
      },
      {
        name: "Farmers Cafe",
        about:
          "Agricultural e-commerce with shop switching and approval workflows",
      },
    ];
  }

  getContact() {
    return {
      portfolio: "https://spirestack.vercel.app",
      email: "user.codespire@gmail.com",
      linkedin: "https://www.linkedin.com/in/siddudev",
    };
  }

  getFutureGoal() {
    return "To keep building practical software that solves real problems.";
  }
}
```
