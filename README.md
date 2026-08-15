# Testing Portfolio

A collection of test automation projects — web and mobile, UI and BDD — built while sharpening my QA/SDET skill set. Each project below lives in its own repository and is pulled in here as a git submodule.

## About Me

**Yasser Hawass**
Cairo, Egypt
📞 +20 110 016 5606 · ✉️ [yasser.hawass@gmail.com](mailto:yasser.hawass@gmail.com)
🔗 [GitHub](https://github.com/YasserHawass) · [LinkedIn](https://www.linkedin.com/in/YasserHawass)

R&D Engineer by day, with a background spanning computer vision, digital identity standards, and instructing. This portfolio is where I've been building and practicing test automation — from Selenium and Cucumber BDD suites to Appium mobile testing — as I explore a shift toward QA/SDET work.

## Projects

| Project | Type | Stack | Description |
|---|---|---|---|
| [Appium-Basics](https://github.com/YasserHawass/Appium-Basics) | Mobile | Appium, Selenium, TestNG, Maven | Core Appium concepts and locator/interaction basics against an Android To-Do app (QACart). |
| [Todo-Appium-Project](https://github.com/YasserHawass/Todo-Appium-Project) | Mobile | Appium, Selenium, TestNG, Maven | Mobile UI test suite for a To-Do Android app, driven through Appium. |
| [Cucumber-PHP-Travel](https://github.com/YasserHawass/Cucumber-PHP-Travel) | Web / BDD | Selenium WebDriver, Cucumber, JUnit/TestNG, Maven | BDD automation for a travel booking site, built with the Page Object Model, reusable driver factory, and screenshot-on-failure hooks. |
| [E-commerce-BDD-with-Selenium](https://github.com/YasserHawass/E-commerce-BDD-with-Selenium) | Web / BDD | Selenium WebDriver, Cucumber, JUnit/TestNG, Maven | BDD automation for an e-commerce demo site — search, cart, and UI validations, following the same POM/hooks structure. |
| [cucumber-todo-app-project](https://github.com/YasserHawass/cucumber-todo-app-project) | Web / BDD | Selenium, Cucumber, TestNG, Maven | Cucumber feature-driven automation of a To-Do web app. |
| [TodoSeleniumProject](https://github.com/YasserHawass/Todo-Selenium) | Web | Selenium WebDriver, TestNG, Maven | Straight Selenium suite covering registration, adding, and deleting To-Do items. |
| [QACartRestAssured](https://github.com/YasserHawass/QACartRestAssured) | API | REST Assured, TestNG, Maven, Allure | API test suite built with REST Assured, with an Allure report auto-published to GitHub Pages via a GitHub Actions workflow. |

## Tech Stack

Java · Selenium WebDriver · Appium · Cucumber (BDD) · REST Assured · TestNG / JUnit · Maven · Allure · Page Object Model · Git · GitHub Actions · GitLab CI/CD · Jenkins · Docker

## Getting Started

This repo uses git submodules, so clone it with:

```bash
git clone --recurse-submodules git@github.com:YasserHawass/Testing-Portfolio.git
```

If you've already cloned it without that flag:

```bash
git submodule update --init --recursive
```

Each submodule is a standalone Maven project — `cd` into one and run `mvn test` (or the relevant TestNG/Cucumber runner) to execute its suite.
