- [DevAscend](#devascend)
  - [Overview](#overview)
  - [Mentorship](#mentorship)
  - [Developing](#developing)
  - [Building](#building)
  - [Deployment](#deployment)
  - [FAQ](#faq)
    - [What is a mentor?](#what-is-a-mentor)
    - [What challenges exist?](#what-challenges-exist)

# DevAscend

DevAscend's mission is to provide free mentorship towards developers and provide a platform to aggregate and propagate that information for public consumption.

This must run entirely by donation and volunteers only, forever-more, as a core principle.

> "A society grows great when old men plant trees whose shade they know they shall never sit in."

## Overview

There is no shortage of experienced engineers willing to share their knowledge and patterns with less senior engineers. The current field is saturated with a large swathe of people with a fundamental set of coding skills but no operational background.

We want to provide a seamless process to:
- Register and match a mentee
- Register to become a mentor
- Distribute mentored meetings and exercises publicly (unless otherwise stated)

This is intended to be a highly selective process to coordinate due to the availability of mentors. People who are willing to help volunteer for others are relatively busy. Respecting mentor time is critical for this mission to succeed, so the inflow of mentees must be carefully controlled based on availability.

All mentorship sessions (unless explicitly marked to not save) will be recorded and will be published publicly for consumption *(tbd - some timeframe)* after the meeting.

## Mentorship

Here are some key steps to create a plan for a mentorship:

- **Define the goals**: First, the mentor and mentee should agree on the goals of the mentorship. These might include improving the mentee's coding skills, building a portfolio, or gaining exposure to a new technology.

- **Develop a schedule**: Both parties should agree on a schedule for meetings or communication, whether that be weekly, biweekly, or monthly. The schedule should also include goals or objectives for each meeting.

- **Identify areas of opportunity**: The mentor should identify learning opportunities, such as books, courses, or online resources, that will help the mentee achieve their goals. The mentor may also provide feedback on the mentee's coding projects or review their code.

- **Provide guidance and feedback**: The mentor should be available to answer the mentee's questions and provide guidance on specific coding challenges. The mentor should also provide feedback on the mentee's progress and help them identify areas for improvement.

- **Build a personal relationship**: Building a personal relationship between mentor and mentee is important. This could involve sharing personal experiences and building a rapport that fosters trust and mutual respect.

- **Evaluate progress**: Both parties should regularly evaluate progress and adjust the mentorship plan as necessary to ensure that the mentee is making progress towards their goals.

- **End the mentorship**: Finally, the mentorship should have a clear end point. This could be after a specific amount of time, after the mentee has achieved their goals, or at a natural break point in the mentor-mentee relationship.

By following these steps, a mentor and mentee can create a plan that helps the mentee achieve their goals and develop their skills as a software developer.

## Developing

Install dependencies:
```bash
npm install
```

Run development server:
```bash
npm run dev
# Or start the server and open the app in a new browser tab
# npm run dev -- --open
```

## Building

To create a production version of your app:

```bash
npm run build
```

You can preview the production build with `npm run preview`.

> To deploy your app, you may need to install an [adapter](https://kit.svelte.dev/docs/adapters) for your target environment.

## Deployment

This project is setup with CI/CD in place. We leverage AWS Amplify for simplicity and route to a custom domain hosted with Route53.
In order to merge your changes live, please create a pull request to the `main` branch and the rest will automatically occur.

## FAQ

### What is a mentor?

A software development mentorship is a learning relationship between an experienced software developer (the mentor) and a less experienced developer (the mentee). The purpose of the mentorship is to help the mentee develop the skills and knowledge necessary to become a successful software developer, and to provide guidance and support as they navigate the challenges and opportunities of the field.

The mentorship typically involves regular meetings or communication between the mentor and mentee, during which they may discuss topics such as programming languages, software design principles, project management, career development, and other relevant areas. The mentor may also provide the mentee with feedback on their code, review their projects, or suggest resources and learning opportunities.

A good mentorship requires both parties to be committed to the process and willing to invest time and effort into it. The mentor should have a strong understanding of the software development industry, as well as excellent communication and teaching skills. The mentee should be eager to learn and willing to take feedback, and should be prepared to put in the work required to grow their skills and knowledge.

Overall, a software development mentorship can be an incredibly valuable experience for any developer looking to improve their skills, gain insights into the industry, and advance their career. By providing personalized guidance and support, a mentor can help their mentee achieve their goals and reach their full potential as a software developer.

### What challenges exist?

There are a number of challenges that junior developers may face when trying to get hired, including:

- **Lack of experience**: Many job postings for software developers require a certain level of experience, which can be difficult for junior developers to meet. Without experience, junior developers may struggle to stand out among more seasoned applicants.

- **Limited skills**: Junior developers may not have developed the full range of skills and knowledge required for certain roles. For example, they may be proficient in one programming language but not another, or they may not have experience with a particular software tool or technology that a job posting requires.

- **Limited network**: Junior developers may not have an extensive network of professional contacts to help them find job opportunities. Without the benefit of referrals or recommendations from more experienced developers, they may have a harder time getting their foot in the door.

- **Fierce competition**: The software development industry is highly competitive, with many qualified applicants vying for the same job openings. Junior developers may find it difficult to compete with more experienced candidates who have a proven track record in the field.

- **Limited interview skills**: Junior developers may not have had as much experience with job interviews, which can make them nervous or unprepared. They may struggle to articulate their skills and experience in a way that makes them stand out from other candidates.

With persistence, dedication, and a willingness to learn and improve, junior developers can develop the skills and experience they need to land their first job in the field. Seeking out mentorship, building their skills through personal projects, and networking with other professionals can all help junior developers stand out and get noticed by potential employers.
