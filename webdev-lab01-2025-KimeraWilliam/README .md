 Lab 01 — Environment Setup & Git Workflow

 Student
Name: Kimera William  
Course: Web & Mobile applications Development 

 Tasks Completed
- [x] Install Node LTS, Git, and VS Code  
- [x] Configure Git user and default branch  
- [x] Initialize repository and create semantic index.html  
- [x] Create style.css for styling  
- [x] Create .gitignore and README.md  
- [x] Open a Pull Request from a feature branch and merge  

---

How to Run
1. Open index.html in a web browser directly, or  
2. Use Live Server in VS Code:
   - Right-click index.html → Open with Live Server
   - Page opens at http://127.0.0.1:5500/index.html  
   - Any changes saved in VS Code auto-refresh in the browser  


 Features
- Semantic HTML5 structure: <header>, <nav>, <main>, <section>, <article>, <footer>  
- Styled with *CSS variables* for colors and layout  
- Fully responsive layout using viewport meta tag  
- Contact form with labeled email input and submit button  
- Gallery section with images and captions  
- Colored header/footer, shadows, and rounded corners for modern look  



 Screenshots
1. Pull Request page:  
![PR page](images/pr.png)

1. Network tab showing status 200:  
![Network 200](images/network.png)

Reflection 
An HTTP request is a message sent by the browser to a server asking for a resource, such as a web page while an HTTP response is what the server sends back, typically HTML, CSS, or images. When I opened my page via Live Server, I saw status code 200, which means the server successfully returned the requested HTML file. This confirms the page loaded correctly over HTTP. One important thing I learned about Git is the value of using feature branches and Pull Requests. By creating a feature/add-news-item branch and committing changes there, I could safely merge updates into the main branch without affecting the main code immediately. The .gitignore file helped keep unnecessary files like node_modules out of the repository.