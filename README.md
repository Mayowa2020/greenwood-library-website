# Greenwood Community Library Website

The **Greenwood Community Library Website** is a simple website that aims to provide visitors with information about the library, upcoming events, and community book reviews. This project involved enhancing the website by adding a new "Book Reviews" section and updating the "Events" page to reflect upcoming community events. The task was completed by simulating the contributions of two team members, "Morgan" and "Jamie."

## Table of Contents

- [Background](#background)
- [Project Objectives](#project-objectives)
- [Technology Stack](#technology-stack)
- [Repository Structure](#repository-structure)
- [Contributors and Workflow](#contributors-and-workflow)
  - [Morgan's Contribution](#morgans-contribution)
  - [Jamie's Contribution](#jamies-contribution)
- [How to Run the Project](#how-to-run-the-project)
- [GitHub Workflow](#github-workflow)
- [Contributing](#contributing)

---

## Background

The **Greenwood Community Library** website initially had basic sections like **Home**, **About Us**, **Events**, and **Contact Us**. The project’s aim was to enhance the website by:
1. Adding a new "Book Reviews" section where the community can find reviews of recent books.
2. Updating the "Events" page to include upcoming community events hosted by the library.

## Project Objectives

- Gain experience with GitHub workflows, including cloning, branching, committing, and creating pull requests.
- Simulate collaboration between two developers (Morgan and Jamie).
- Learn how to manage feature additions and updates through separate branches and merge them into the main branch.

## Technology Stack

- **HTML**: Used to build the structure of the web pages.
- **Git & GitHub**: Version control system to manage project files and collaboration between developers.

## Repository Structure

The repository is structured as follows:

```
├── README.md              # Project documentation
├── home.html              # Home page of the website
├── about_us.html          # About Us page
├── events.html            # Events page, updated by Jamie
├── contact_us.html        # Contact Us page
├── book_reviews.html      # New Book Reviews section added by Morgan
```

## Contributors and Workflow

This project simulates the contributions of two developers: **Morgan** and **Jamie**.

### Morgan's Contribution

Morgan was responsible for adding a new "Book Reviews" section. The steps included:
1. Creating a new branch named `add-book-reviews`.
2. Adding a new file, `book_reviews.html`, to the project.
3. Populating the file with random content related to book reviews.
4. Committing the changes with the message `"Add book reviews section"`.
5. Creating a pull request (PR) to merge the new section into the `main` branch.
6. Once approved, merging the `add-book-reviews` branch into the `main` branch.

### Jamie's Contribution

Jamie was tasked with updating the "Events" page. The steps included:
1. Creating a new branch named `update-events`.
2. Modifying the existing `events.html` file to reflect new community events.
3. Committing the changes with the message `"Update events page with upcoming community events"`.
4. Pulling the latest changes from the `main` branch to ensure compatibility.
5. Creating a pull request to merge the changes into the `main` branch.
6. Resolving any conflicts and merging the `update-events` branch into the `main` branch.

## How to Run the Project

To view the website locally:

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/greenwood-library-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd greenwood-library-website
   ```
3. Open the `.html` files in a browser of your choice to view the content.

## GitHub Workflow

Here’s a brief overview of the GitHub workflow followed for this project:

1. **Cloning the repository**:  
   Developers cloned the project from the remote repository using `git clone`.

2. **Creating branches**:  
   Each contributor worked on separate branches:  
   - Morgan: `add-book-reviews`  
   - Jamie: `update-events`

3. **Committing changes**:  
   After making the necessary updates to their files, the contributors staged, committed, and pushed their changes using:
   ```bash
   git add .
   git commit -m "Commit message"
   git push origin branch-name
   ```

4. **Raising Pull Requests**:  
   Both contributors raised PRs to merge their changes into the `main` branch. Once the PRs were reviewed and approved, they were merged.

5. **Pulling latest changes**:  
   Before raising a PR, Jamie pulled the latest changes from the `main` branch using:
   ```bash
   git pull origin main
   ```

## Contributing

If you would like to contribute to this project:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "description of your changes"`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.
