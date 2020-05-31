# ROBE & The One World Schoolhouse: Education Reimagined

<img src="https://res.cloudinary.com/eduprojectsil/image/upload/v1589613611/Screen_Shot_2020-05-16_at_12.19.34_AM_iaa5zw.png" width="75%" />

## The Product
ROBE is short for **Ro**bots **B**uilding **E**ducation, an education outplatform that builds both online and physical schools. The central idea behind ROBE is to build a learning platform that rewards schools and students for their efforts and usage. The product will be sold to schools at some fixed value and redistribute some of that cost to a larger pool that will be injected into schools in need of more resources. 

The pricing model will likely be per student (with other considerations) and redistributed similarly through the creative use of cloud pay-as-used transaction system. For a example: 

- A student answers something correctly
- A student answers something something correctly on first try
- A student answers something correctly on the N-th try
- Analytics determines that 85% of students get a "highly rated" problem wrong on the first try, and a student succeeds on the first try
- A student engages with the module's features that assist teachers, themselves, or other students
- A student completes 40-100% of a video
- A student posts, answers, likes, favorites questions and answers
- A teacher grades homework or answers a student instanced questions
- A teacher uploads a lesson plan or classroom findings to their shared resource space
- The list is endless of various, granular cases of learning efforts.

<img src="https://res.cloudinary.com/eduprojectsil/image/upload/v1590905792/unnamed_zf5wyl.png" width="75%" />
<img src="https://miro.medium.com/max/4576/1*s1cl2uJnKBRMejtef3Psjg.png" width="75%" />


## Development Priorities
Quality over everything. Education lacks fault tolerance to a rather grim extent. The should be mindful and built around this. In this case, the software serves to empower education participants and will otherwise fail when that is not executed on correctly.

## Tech Stack - Long term goals
The goal behind the tech stack is to select a suite of software tools that will define high-level software standards in the future with respects to networking speeds and accessibility. We want software tools that prioritize real-time data, native machining, security, and accessibility to quality regardless of location.

### Front End - React w/ Recoil
  - TL;DR: React, Recoil, GraphQL, Google Cloud, Cloudflare Workers
  
  #### React: https://reactjs.org/ 
  
  React is a resilient and evolving front-end framework that provides a state model that ebbs and flows with computing     advancements. It's simple to learn, follow, and work with. 

 <img src="https://miro.medium.com/max/1368/1*R-oovJm4IQBLDjZy6DvbBg.png" width="75%"/> 

  #### Recoil: https://recoiljs.org/docs/introduction/motivation
  
  <img src="https://blog.graphqleditor.com/static/b15af8125162128e750b4206c78a9cb7/c425d/atoms.png" width="75%" />

  Recoil is a nice Hook-based state management tool created by Facebook that approaches the future of web development in an   elegant way. Rather than writing React in a "Redux" way, you sprinkle state managing atoms as needed. It's an orthogonal   injection across a react state tree which reduces overall complexity.
 
  You're dealing with new era web advancements like `Progressive Web Apps, server side rendering, edge computing, web   concurrency, web assembly, serverless architecture, real-time data streaming, privacy, security`. **The name of the game for  front-end web development is to get the web browser to behave more like a native operating system*


### API Management

  #### GraphQL (API Development): https://graphql.org/learn/
  I believe this tool will cooperate best with React and the growing backend's iterations. The goal here is to have a robust   choice that makes networking data smoother and more consistent. I see that GraphQL seems to put API requests through a transformer process and that's a forgiving element worth considering when building out a large scale platform

  <img src="https://devopedia.org/images/article/147/8496.1558526064.jpg" width="75%" />

### Backend

  #### Google Cloud Platform (realtime DB, cloud functions, storage): https://firebase.google.com/docs/firestore
  The primary reason this is selected is due to easier prototyping and familiar integration with teacher and student related tooling(Drive, Docs, Mail, etc) and AI tooling (image, text recognition, data collection, etc). Firebase is also a fantastic introduction to serverless computing that gets front-end developers to think at the network-operative level.

  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRxXJvztjQX7OAi-nQ5iDKfDRp5eGiOPZWjn7VuAGwwA16woHGj&usqp=CAU" width="75%" />
  <img src="https://storage.googleapis.com/gweb-cloudblog-publish/images/cloud_functions.max-600x600.png" width="75%" />

  
  #### Cloudflare Workers (Optimizations, SSR, edge networking, security) https://developers.cloudflare.com/workers/
  This will be the primary tool for serverless computing in the long term with respects to custom development, networking speed, server & cost management, and security. Initially it'll likely be used to optomize server-reads and bring in lightning fast data caches to the product even at early stages.
  
  I believe CloudFlare Workers has the right idea when it comes to building truly Progressive Web Apps with their rework of Service Workers and their handling low level tasks for optimal web experiences. I'm excited to see their serverless platform build and mature over the following years.
  
  <img src="https://lh6.googleusercontent.com/wr4NfjJHXW0y_bIJAoOamYwnj2PCZlQAMJY9-pao_rPWBwlkKikF0W_BV7y1n3GZg9JAV9SyFfVUSvLYQ4nJEUk2w3HRvueKYcJ0nG33QugkSmMR7Neh2EsRZzRV5w_78Nuj2Wyi" width="75%" />

  <img src="https://blog.cloudflare.com/content/images/2018/06/developerplatform.png" width="75%"/>
  

  
  

