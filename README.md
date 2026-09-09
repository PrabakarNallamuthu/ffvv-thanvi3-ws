# ffvv-thanvi3-ws

A Spring Boot microservice repository for the `ffvv` backend service, created for the Engineering team under the PrabakarNallamuthu organization.

## Tech Stack

- **Language:** Java
- **Framework:** Spring Boot

> See `pom.xml` or `build.gradle` for full dependency details.

## Quick Start

### Prerequisites

- Java Development Kit (JDK) 17 or higher
- Maven or Gradle (whichever is configured in the project)

### Clone the Repository

bash
git clone https://github.com/PrabakarNallamuthu/ffvv-thanvi3-ws.git
cd ffvv-thanvi3-ws


### Install Dependencies & Build

**Maven:**
bash
./mvnw clean install


**Gradle:**
bash
./gradlew build


### Run the Service

**Maven:**
bash
./mvnw spring-boot:run


**Gradle:**
bash
./gradlew bootRun


## Project Structure


ffvv-thanvi3-ws/
├── .github/
│   └── workflows/
│       └── java-template.yml       # CI/CD pipeline
├── src/
│   ├── main/
│   │   ├── java/                   # Application source code
│   │   └── resources/              # Application configuration
│   └── test/
│       └── java/                   # Test source code
├── pom.xml / build.gradle          # Build configuration
└── README.md


## CI/CD

This repository uses a GitHub Actions pipeline defined in:


.github/workflows/java-template.yml


The pipeline is based on the `java-template` workflow. Refer to the workflow file for details on build, test, and deployment steps.

## Contributing

- **Branch naming:** Use descriptive branch names, e.g. `feature/<short-description>`, `fix/<short-description>`, `chore/<short-description>`.
- **Pull Requests:** Ensure all checks pass before requesting a review. Provide a clear description of the changes in your PR.
- **Team:** Engineering

## License

This project is licensed under the [MIT License](LICENSE).
