<div align="center">
  <h1>Omri Shahar</h1>
  <h3>Machine Learning Engineer | Data Scientist</h3>
  <p>
    I am an engineer who enjoys the intersection of software development and statistical theory. While I focus on building production-ready NLP systems, I am equally passionate about understanding the math behind the models, reading research papers, and keeping up with the rapid pace of the field.
  </p>
  <p>
    This GitHub profile serves as my primary portfolio.
  </p>
  
  <p>
    <a href="https://www.linkedin.com/in/omri-shahar-38909a1b0/" target="_blank">Connect on LinkedIn</a>
  </p>
</div>

<hr />

<h3>Featured Project: Intelligent Job Market Scanner</h3>
<p>
  I built an automated pipeline to solve the "needle in a haystack" problem of job hunting. Instead of manually scrolling through boards, this tool autonomously finds, filters, and ranks positions based on a deep semantic understanding of a specific CV.
</p>

<strong>How it works:</strong>
<ul>
  <li><strong>Ingestion:</strong> The system scans job boards at fixed intervals to fetch new listings.</li>
  <li><strong>Extraction:</strong> It utilizes NLP techniques to parse unstructured job descriptions into a standardized format.</li>
  <li><strong>CV Parsing:</strong> Using <strong>LangChain</strong> and <strong>Pydantic</strong>, the system extracts structured data from a target CV to establish a baseline profile.</li>
  <li><strong>Filtering & Ranking:</strong>
    <ul>
      <li>First, it applies a rational filter to remove irrelevant roles based on hard constraints.</li>
      <li>The remaining positions are converted into vector embeddings and stored in a vector database.</li>
      <li>The system calculates the cosine similarity between the CV embeddings and job embeddings to rank the opportunities.</li>
    </ul>
  </li>
  <li><strong>Reporting:</strong> It generates a digest of the top-k positions, including their specific rank and a generated explanation of why each role is a statistical fit for the candidate.</li>
</ul>

<p><strong>Tech Stack:</strong> Python, LangChain, Pydantic, Vector Database, Transformers/Embeddings.</p>

<hr />

<h3>Technical Skills</h3>

<table>
  <thead>
    <tr>
      <th align="center">Languages & Core</th>
      <th align="center">Machine Learning & NLP</th>
      <th align="center">Engineering & MLOps</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" valign="top">
        Python<br/>
        SQL<br/>
        Bash
      </td>
      <td align="center" valign="top">
        PyTorch<br/>
        Hugging Face<br/>
        LangChain<br/>
        Vector Databases (Pinecone/Chroma)<br/>
        Scikit-learn
      </td>
      <td align="center" valign="top">
        Docker<br/>
        API Development<br/>
        CI/CD pipelines
      </td>
    </tr>
  </tbody>
</table>
