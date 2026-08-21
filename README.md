# Hi there, I'm Krishna Dobhal 👋

![Profile views](https://komarev.com/ghpvc/?username=krishnadobhal&color=blueviolet&style=flat)

<p>
  <a href="https://www.krishnadobhal.dev"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-FFB020?style=for-the-badge&logo=googlechrome&logoColor=141312"></a>
  <a href="https://www.linkedin.com/in/krishnadobhal/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/krishnadobhal"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
  <a href="https://leetcode.com/u/KrishnaDobhal/"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"></a>
  <a href="mailto:krishnadobhal234@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-141312?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

Full-stack software engineer based in Gurugram, India, with a strong foundation in object-oriented programming and a focus on building scalable backend systems and the interfaces on top of them.

- 🔭 Currently a **Software Developer Intern** at **Outbox Labs**, working on lead discovery and identity resolution.
- 🛠️ Hands-on experience across React, Next.js, Node.js, and Spring Boot.
- 🌐 Portfolio: [krishnadobhal.dev](https://www.krishnadobhal.dev)
- 📫 Reach me at **krishnadobhal234@gmail.com**.

---

### 🛠️ Tech Stack

**Languages**

<p>
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white">
</p>

**Frameworks & Libraries**

<p>
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white">
  <img alt="Express" src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white">
  <img alt="Spring Boot" src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white">
  <img alt="GraphQL" src="https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white">
  <img alt="Apollo" src="https://img.shields.io/badge/Apollo_Server-311C87?style=for-the-badge&logo=apollo-graphql&logoColor=white">
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white">
  <img alt="LangChain" src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=langchain&logoColor=white">
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">
</p>

**Data & Infra**

<p>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
  <img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white">
  <img alt="Elasticsearch" src="https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white">
  <img alt="Amazon S3" src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white">
</p>

---

### 📌 Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Video Streaming Platform</h3>
      <p>A microservices architecture for video upload, transcoding, and streaming, using Kafka for asynchronous communication between services.</p>
      <ul>
        <li>RESTful APIs for chunked video uploads to Amazon S3.</li>
        <li>Transcode service built with FFmpeg to convert uploads into HLS-compatible formats.</li>
        <li>Watch service that dynamically serves <code>.m3u8</code> playlists for adaptive streaming.</li>
      </ul>
      <p><strong>Stack:</strong> Next.js, TypeScript, Node.js, Kafka, AWS S3, Prisma, FFmpeg</p>
      <a href="https://github.com/krishnadobhal/Video-Streaming">View Code →</a>
    </td>
    <td width="50%" valign="top">
      <h3>URL Shortener</h3>
      <p>A three-service platform (Spring Boot for URLs, Node.js/TypeScript for ID generation and analytics) covering the full URL-shortening lifecycle.</p>
      <ul>
        <li>Fault-tolerant ID generation using sharded PostgreSQL with transactional row locking (<code>FOR UPDATE</code>) for unique, concurrent short-code allocation.</li>
        <li>Asynchronous click pipeline via Kafka into ClickHouse for fast, aggregated analytics.</li>
        <li>Redis-cached URL resolution; API secured with Spring Security and BCrypt password hashing.</li>
      </ul>
      <p><strong>Stack:</strong> Spring Boot, Node.js, TypeScript, PostgreSQL, Redis, ClickHouse, Kafka</p>
      <a href="https://github.com/krishnadobhal/URL-Shortener">View Code →</a>
    </td>
  </tr>
</table>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=krishnadobhal&show_icons=true&theme=radical" alt="Krishna's GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=krishnadobhal&layout=compact&theme=radical" alt="Top Languages" height="165">
</p>
