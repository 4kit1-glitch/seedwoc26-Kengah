# 🌱 Seed Worldwide of Code (SeedWOC)

A comprehensive, community-driven learning platform covering everything from version control to advanced software development, machine learning, cybersecurity, and embedded systems.

## 📚 Program Overview

SeedWOC is a yearly program designed to transform aspiring developers into true software engineers. This repository provides a structured curriculum covering:

- **Version Control & Git** - Foundation for collaborative development
- **Programming Languages** - JavaScript, Python, Dart
- **Web Development** - React, Angular, modern frontend practices
- **Backend Development** - Node.js/Express, Django
- **Machine Learning & AI** - Core concepts, deep learning, computer vision, generative AI
- **Cybersecurity** - Security fundamentals, cryptography, secure coding
- **Embedded Systems** - Arduino programming, IoT projects
- **System Programming** - C, C++, low-level development

## 🎯 Structure

```
seedwoc/
├── chapters/                          # Main curriculum chapters
│   ├── chapter-1-version-control/
│   ├── chapter-2-javascript-fundamentals/
│   ├── chapter-3-javascript-advanced/
│   ├── chapter-4-python-fundamentals/
│   ├── chapter-5-dart-fundamentals/
│   ├── chapter-6-web-development-react/
│   ├── chapter-7-web-development-angular/
│   ├── chapter-8-backend-nodejs-express/
│   ├── chapter-9-backend-django/
│   ├── chapter-10-machine-learning-basics/
│   ├── chapter-11-deep-learning/
│   ├── chapter-12-computer-vision/
│   ├── chapter-13-generative-ai/
│   ├── chapter-14-cybersecurity-basics/
│   ├── chapter-15-embedded-systems-arduino/
│   ├── chapter-16-system-programming-c/
│   └── chapter-17-system-programming-cpp/
├── assignments/                       # Student submission area
│   └── {github_username}/
│       └── {chapter}/
│           └── {module}/
│               └── {part}/
│                   └── exercise_1.html, exercise_2.py, etc.
├── resources/                         # Shared resources
├── docs/                              # External documentation
└── .github/workflows/                 # CI/CD pipelines
```

## 📖 Chapter Structure

Each chapter is organized as:

```
chapter-{n}-{name}/
├── README.md                          # Chapter overview and learning objectives
├── modules/
│   ├── module-1-{topic}/
│   │   ├── README.md                 # Module guide
│   │   ├── parts/
│   │   │   ├── part-1-{subtopic}/
│   │   │   │   ├── README.md         # Part details
│   │   │   │   ├── lecture.md        # Lecture notes
│   │   │   │   ├── examples/         # Code examples
│   │   │   │   └── exercise-1.md     # Exercises
│   │   │   └── part-2-{subtopic}/
│   │   └── quiz.md                   # Module quiz
│   └── module-2-{topic}/
└── final-project.md                  # Chapter capstone project
```

## 🚀 Getting Started

### For Learners

1. **Clone this repository:**
   ```bash
   git clone https://github.com/yourusername/seedwoc.git
   cd seedwoc
   ```

2. **Choose your path:**
   - Start with Chapter 1 (Version Control) - essential foundation
   - Progress through chapters sequentially for optimal learning
   - Each chapter builds on previous knowledge

3. **Working on Exercises:**
   ```bash
   # Create your assignment directory
   mkdir -p assignments/{your_github_username}/chapter-1-version-control/module-1-git-basics/part-1-introduction
   
   # Solve the exercises in this directory
   # Commit frequently with clear messages
   ```

4. **Submit Your Work:**
   - Follow the contribution guidelines below
   - Create a Pull Request to the main repository
   - Ensure all exercises are complete and tested

### For Instructors/Contributors

See [CONTRIBUTING.md](./docs/CONTRIBUTING.md) for detailed guidelines on:
- Creating new chapters and modules
- Formulating effective exercises
- Setting up assessments
- Maintaining code quality

## 📝 Best Practices for Contributors

### 1. **Commit Messages**
Use clear, descriptive commit messages following conventional commits:
```
feat: add chapter 2 module 1 exercises
fix: correct solution for chapter 1 exercise 3
docs: update readme for module 2
refactor: reorganize assignment structure
```

### 2. **Directory Naming Conventions**
- Use lowercase with hyphens: `chapter-1-version-control`
- Be descriptive: `module-1-git-basics`
- Avoid spaces and special characters

### 3. **File Organization**
```
part-{n}-{topic}/
├── README.md              # Part objectives and resources
├── lecture.md             # Detailed notes
├── examples/              # Working code examples
│   ├── example-1.js
│   ├── example-2.js
│   └── solution.html
├── exercises/             # Assignment folder
│   ├── exercise-1.md      # Problem statement
│   ├── exercise-2.md
│   └── SOLUTIONS.md       # Solutions (hidden in main repo)
└── resources.md           # Links to external resources
```

### 4. **Code Standards**
- Use consistent formatting and linting
- Include comments for complex logic
- Provide clearly named variables and functions
- Test your code before committing
- Include example inputs/outputs in documentation

### 5. **Documentation**
- Every chapter must have a clear README
- Include learning objectives
- Provide resource links
- Explain prerequisites
- Include difficulty level indicators

### 6. **Exercise Quality**
- **Start simple** → Progress to complex
- **Provide context** → Real-world applications
- **Include hints** → But not full solutions
- **Test thoroughly** → Ensure solutions work
- **Provide rubrics** → Clear grading criteria

## 📊 Learning Path Recommendations

### Path 1: Full-Stack Web Developer
```
1. Chapter 1 - Version Control (2 weeks)
2. Chapter 2 - JavaScript Fundamentals (3 weeks)
3. Chapter 3 - JavaScript Advanced (3 weeks)
4. Chapter 6 - React (4 weeks)
5. Chapter 8 - Node.js/Express (4 weeks)
Total: ~16 weeks
```

### Path 2: Python Backend Developer
```
1. Chapter 1 - Version Control (2 weeks)
2. Chapter 4 - Python Fundamentals (3 weeks)
3. Chapter 9 - Django (4 weeks)
4. Chapter 10 - Machine Learning Basics (3 weeks)
Total: ~12 weeks
```

### Path 3: ML/AI Specialist
```
1. Chapter 1 - Version Control (2 weeks)
2. Chapter 2 - JavaScript Fundamentals (1 week - overview)
3. Chapter 4 - Python Fundamentals (3 weeks)
4. Chapter 10 - ML Basics (4 weeks)
5. Chapter 11 - Deep Learning (4 weeks)
6. Chapter 12 - Computer Vision (3 weeks)
7. Chapter 13 - Generative AI (3 weeks)
Total: ~20 weeks
```

### Path 4: Cybersecurity Specialist
```
1. Chapter 1 - Version Control (2 weeks)
2. Chapter 4 - Python Fundamentals (3 weeks)
3. Chapter 14 - Cybersecurity Basics (4 weeks)
4. Chapter 16/17 - System Programming (4 weeks)
Total: ~13 weeks
```

### Path 5: Embedded Systems Engineer
```
1. Chapter 1 - Version Control (2 weeks)
2. Chapter 16 - C Programming (4 weeks)
3. Chapter 15 - Arduino (3 weeks)
Total: ~9 weeks
```

## ✅ Assignment Submission Checklist

Before submitting your pull request, ensure:

- [ ] All files are in correct directory structure
- [ ] Code follows style guidelines
- [ ] All exercises are completed
- [ ] Code is tested and working
- [ ] Commit messages are clear and descriptive
- [ ] README files are updated
- [ ] No merge conflicts
- [ ] At least 5 meaningful commits for the work

## 🔄 Git Workflow

1. **Create a feature branch:**
   ```bash
   git checkout -b feat/chapter-1-exercises
   ```

2. **Make small, focused commits:**
   ```bash
   git add assignments/{username}/chapter-1/module-1/part-1/
   git commit -m "feat: add git basics exercises"
   ```

3. **Push to your fork:**
   ```bash
   git push origin feat/chapter-1-exercises
   ```

4. **Create a Pull Request:**
   - Include clear description
   - Reference any issues
   - Describe what you've learned

## 📞 Community & Support

- **Discussions**: Open an issue for questions
- **Discord/Chat**: [Add community link]
- **Office Hours**: [Add schedule]
- **Code Reviews**: All PRs will be reviewed within 48 hours

## 🎓 Certification

Upon completion of:
- **Tier 1** (5 chapters): Foundation Certificate
- **Tier 2** (10 chapters): Developer Certificate
- **Tier 3** (All chapters): Master Developer Certificate

## 📜 License

This project is licensed under the MIT License - see [LICENSE](LICENSE) file for details.

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository
2. Create a feature branch
3. Submit a pull request
4. Follow our [contributing guidelines](./docs/CONTRIBUTING.md)

## 🌟 Acknowledgments

SeedWOC is built by and for the developer community. Special thanks to all contributors who make this possible.

---

**Start your learning journey today! Pick a chapter and never stop growing!** 🚀

