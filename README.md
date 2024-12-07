# 1. Project Title
Franchise Connect Platform by Senan Otsuka 

# 2. Project Overview

Many Japanese restaurant owners have a positive attitude towards franchising and would do so given the opportunity. There is demand from foreign investors to franchise Japanese restaurants. However, only the large corporations who have an abundance of capital and power are currently franchising abroad. This platform gives the opportunity for smaller Japanese businesses and foreign investors to connect while being provided professional insight from experts who have experience in the franchising industry. Further, investors are able to begin a Japanese restaurant with a pre- established brand, instead of having to start from the beginning

# 3. Problem Statement
What is the real problem being addressed?
Brief summary of past attempts to solve this problem. Competitors?
How does this problem affect the customer, and how do they currently solve it?
Quantify wasted time, money, or other resources.

# 4. ISBA Subfields
The ISBA subfields that applied to this project were application development, IT project management, and business analytics. 

## Application Development 
Application development has been a cornerstone of this project, beginning with the creation of a website as a primary application. The process started with gathering information and developing flowcharts to outline the required functionalities and capabilities, providing a clear roadmap for the website’s design and features. This structured approach ensured alignment with project goals from the initial stages through testing and deployment. Utilizing JIRA for project management and organizing development stages into sprint goals allowed for efficient tracking and iterative progress. CRUD operations were integrated and tested throughout various stages of the project to ensure robust functionality, particularly for features like managing user profiles, handling data submissions, and maintaining database integrity. By focusing on these core principles, I was able to deliver a website that was not only fully functional and user-focused but also scalable and reliable, meeting the diverse needs of its users. 

## IT Project Management

IT project management was a critical component of this project, facilitated through the use of the no-code application development platform, Bubble. The process began with meticulous planning of user flows for both investors and restaurant owners to ensure the platform met their needs effectively. This step involved mapping out functionalities and capabilities, such as account management, seamless user interfaces, and visualization, to guide the platform's design and development. As the project progressed, I engaged in continuous iterations to update and enhance the website based on testing and seeding the website with fake data, ensuring a high-quality final product.

To manage the project effectively, I utilized JIRA as a central tool for organizing tasks and tracking progress. The workflow was divided into two-week sprints, during which specific issues and challenges were addressed methodically. This iterative approach allowed for the identification and resolution of technical problems and the consistent improvement of platform features. By implementing structured IT project management, I successfully developed a user-focused, functional website that aligned with the project’s goals and stakeholders' expectations. Further, since this website is still at a foundational stage which serves as a minimal viable product, IT project management allows me to identify points that I can continue to enhance and improve. 

## Business Analytics 
Business analytics played a pivotal role in the success of the Franchise Connect platform, guiding the project through its various stages. At the outset, I conducted extensive research on successful franchises in Japan, gathering quantitative data to understand key factors contributing to their success. This included market trends and customer preferences, providing a solid foundation for the platform's development. Additionally, competitive analysis allowed me to identify gaps and opportunities in the existing market, ensuring the website would offer unique and valuable features.

Beyond quantitative data, qualitative research was equally important. By conducting surveys and interviews with Japanese restaurant owners, I gained critical insights into their needs and challenges. This research revealed essential services and functionalities that needed to be incorporated into the platform, such as tools for managing franchise applications, communication, and performance tracking. By leveraging business analytics to synthesize data from multiple sources, I was able to design a user-focused, data-driven website that effectively addresses the demands of both franchisors and franchisees, ensuring its relevance and success in the competitive market.

# 5. Solution Overview
To solve the problem, I used a no-code approach with the Bubble platform to develop the Franchise Connect website. This allowed me to quickly design and build the application without extensive programming, focusing instead on user experience and functionality. I started by planning user flows and identifying the essential features through research and feedback. Using Bubble’s visual development environment, I implemented these features, iteratively testing and refining the application. Data storage and management were handled seamlessly through Bubble’s integration with AWS RDS, ensuring a secure and scalable backend.

Technical Stack
Programming Languages: No-code (Bubble's built-in logic)
Frameworks: Bubble (No-code application development)
Data Storage: AWS RDS (Relational Database Service)
Software/Tools: JIRA (for project management)
APIs: Bubble’s built-in API integrations
Hosting: Cloud-based (Bubble-hosted, leveraging AWS)
Data: User data from restaurants and investors, survey responses, market research data (quantitative and qualitative).

# 6. Solution Details (Technical Terms)
The development of the Franchise Connect platform followed the SDLC framework, structured into four key stages: Planning and Requirement Gathering/Analysis, Design and Implementation, Testing, and Deployment. This approach ensured a systematic and efficient development process tailored to meet user and business needs.

## Planning and Requirement Gathering/Analysis
In the initial stage, I conducted extensive market research to analyze successful franchises in Japan and benchmarked against competitors. To supplement this, I carried out qualitative research, including surveys and interviews with Japanese restaurant owners, to gather insights into their specific needs. This step helped define the platform’s target user groups—investors and restaurant owners—and identify essential features such as user registration and franchise application management. User flowcharts were created to map out interactions and functionalities, serving as a blueprint for the subsequent design and implementation stages.

## Design and Implementation
Using the no-code development platform Bubble, I designed and implemented the platform's core functionalities. Bubble’s visual design tools enabled the creation of wireframes and mockups, which were transformed into a fully interactive application. CRUD operations were at the heart of the platform’s functionality, allowing users to register accounts, submit and manage franchise applications. Data storage was handled seamlessly through Bubble’s integration with AWS RDS, providing a secure and scalable backend. Additionally, third-party APIs were incorporated for features such as email notifications and external data synchronization, enhancing the platform’s capabilities.

## Testing
During the testing phase, I rigorously evaluated the platform’s functionalities to ensure alignment with user requirements and business goals. Various testing methods were employed, including unit testing for individual features and user acceptance testing to validate the platform's usability. Feedback collected during testing allowed for iterative refinements, addressing issues, and optimizing the user experience.

## Deployment
Finally, the platform was deployed using Bubble’s cloud-hosting capabilities, leveraging AWS for backend support. Deployment included a final round of checks to ensure scalability, security, and performance in a live environment. With this, the Franchise Connect platform was successfully launched, providing a robust and user-friendly application for investors and restaurant owners.

By following this structured methodology and leveraging the no-code capabilities of Bubble along with AWS integration, the project achieved its goal of creating a dynamic and scalable platform tailored to its users' needs.

# 7. Next Steps / Future Improvements
During the development of the Franchise Connect platform, several features were initially planned but later scaled down or abandoned due to time constraints and technical limitations. One such feature was a chat functionality that would allow seamless communication between restaurant owners and investors within the platform. While this feature would have greatly enhanced user interaction, the complexity of implementing real-time messaging and integrating it with external chat services made it challenging to achieve within the timeline. Additionally, the goal of enabling users to finalize franchise contracts directly within the platform was considered, but due to legal and operational complexities, it was decided to scale this feature down to simply facilitating connections between the two parties, leaving contract finalization to be handled externally.

Despite these setbacks, the platform is still ready for deployment into production with the core functionalities intact. The platform can be launched with the existing features, such as connecting restaurant owners and investors, managing applications, and displaying dashboards. Looking ahead, there are several areas for improvement. The chat feature could be revisited in the future, either by integrating a third-party messaging service or developing a custom real-time messaging system. Similarly, the feature for franchise contract finalization could be introduced as an external integration with e-signature services or contract generation tools, which would make the process more seamless without complicating the platform’s core functionalities. Continuous user feedback would be crucial for iterating and refining the platform, ensuring it evolves in line with user needs and market demands. By focusing on these improvements and implementing them incrementally, the platform can continue to grow and offer more value to both investors and restaurant owners.

# 8. Retrospective

During the development of the Franchise Connect platform, several specific challenges arose, primarily related to time management and the complexity of maintaining a balance between development speed and quality. One significant challenge was the temptation to develop for long hours without performing unit testing or checking for bugs regularly. Often, I would spend hours working on a feature, only to find that, by the end of the development session, issues had accumulated, which I had overlooked. This led to more significant problems down the line, as bugs or incomplete features would compound, making them harder to fix later. This experience highlighted the critical importance of unit testing and the need to test incrementally as development progresses. By implementing small, regular tests, I could catch issues early, preventing them from becoming larger problems. This approach helped maintain the quality of the platform and ensured smoother development overall.

Through these challenges, I gained new insights and skills that were invaluable to the success of the project. Most notably, I learned the importance of incremental development—breaking tasks into smaller, manageable pieces and testing them consistently throughout the process. This iterative approach not only improved the quality of my work but also boosted my efficiency and confidence in addressing issues as they arose. Additionally, I deepened my understanding of the no-code development platform, Bubble, and its capabilities, along with cloud-based data storage using AWS RDS. These new skills and insights have significantly enhanced my project management and development approach, providing a solid foundation for future projects.
