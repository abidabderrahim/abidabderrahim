<p align="center">
 
![image](https://user-images.githubusercontent.com/61057666/169029838-74df663d-2e62-4d77-bdff-b43f7d63f00f.png)

</p>

<pre class="astro-code github-dark" style="background-color:#24292e;color:#e1e4e8; overflow-x: auto;" tabindex="0"><code><span class="line"><span style="color:#F97583">class</span><span style="color:#B392F0"> Abderrahim</span><span style="color:#E1E4E8">(</span><span style="color:#B392F0">SelfTaughtDeveloper</span><span style="color:#E1E4E8">):</span></span>
<span class="line"><span style="color:#9ECBFF">   """Self-taught developer with a passion for IT and technology"""</span></span>
<span class="line"><span style="color:#E1E4E8">   </span></span>
<span class="line"><span style="color:#F97583">   def</span><span style="color:#79B8FF"> __init__</span><span style="color:#E1E4E8">(self):</span></span>
<span class="line"><span style="color:#E1E4E8">     </span></span>
<span class="line"><span style="color:#79B8FF">      self</span><span style="color:#E1E4E8">.name </span><span style="color:#F97583">=</span><span style="color:#9ECBFF"> "Abderrahim"</span></span>
<span class="line"><span style="color:#79B8FF">      self</span><span style="color:#E1E4E8">.age </span><span style="color:#F97583">=</span><span style="color:#79B8FF"> 24</span></span>
<span class="line"><span style="color:#79B8FF">      self</span><span style="color:#E1E4E8">.role </span><span style="color:#F97583">=</span><span style="color:#9ECBFF"> "Freelancer & Developer"</span></span>
<span class="line"></span>
<span class="line"><span style="color:#79B8FF">      self</span><span style="color:#E1E4E8">.</span><span style="color:#79B8FF">TOOLS</span><span style="color:#F97583"> =</span><span style="color:#E1E4E8"> {</span></span>
<span class="line"><span style="color:#9ECBFF">          "ScriptingLanguages"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"Python"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"Bash-Script"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"matlab"</span><span style="color:#E1E4E8">),</span></span>
<span class="line"><span style="color:#9ECBFF">          "ProgrammingLanguages"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"C"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"C++"</span><span style="color:#E1E4E8">),</span></span>
<span class="line"><span style="color:#9ECBFF">          "MarkupLanguages"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"HTML"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"markdown"</span><span style="color:#E1E4E8">),</span></span>
<span class="line"><span style="color:#9ECBFF">          "Editors"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"VsCode"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"Sublime"</span><span style="color:#E1E4E8">),</span></span>
<span class="line"><span style="color:#9ECBFF">          "Platform"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"GNU/LINUX"</span><span style="color:#E1E4E8">,),</span></span>
<span class="line"><span style="color:#9ECBFF">          "OtherTools"</span><span style="color:#E1E4E8"> : (</span><span style="color:#9ECBFF">"Git"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"Docker"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"AWS"</span><span style="color:#E1E4E8">, </span><span style="color:#9ECBFF">"Metasploit"</span><span style="color:#E1E4E8">)</span></span>
<span class="line"><span style="color:#E1E4E8">         }</span></span>
<span class="line"></span>
<span class="line"><span style="color:#79B8FF">      self</span><span style="color:#E1E4E8">.</span><span style="color:#79B8FF">INTERESTS</span><span style="color:#F97583"> =</span><span style="color:#E1E4E8"> [</span></span>
<span class="line"><span style="color:#9ECBFF">         "Penetration Testing"</span><span style="color:#E1E4E8">,</span></span>
<span class="line"><span style="color:#9ECBFF">         "Web Development"</span><span style="color:#E1E4E8">,</span></span>
<span class="line"><span style="color:#9ECBFF">         "Cybersecurity"</span><span style="color:#E1E4E8">,</span></span>
<span class="line"><span style="color:#9ECBFF">         "AI and Automation"</span></span>
<span class="line"><span style="color:#E1E4E8">         ]</span></span>
<span class="line"></span>
<span class="line"><span style="color:#F97583">   def</span><span style="color:#B392F0"> use</span><span style="color:#E1E4E8">(self, tool):</span></span>
<span class="line"><span style="color:#9ECBFF">      """Use one of my tools or use multiple tools."""</span></span>
<span class="line"><span style="color:#F97583">      return</span><span style="color:#79B8FF"> self</span><span style="color:#E1E4E8">.TOOLS[tool]</span></span>
<span class="line"></span>
<span class="line"></span>
<span class="line"><span style="color:#F97583">   def</span><span style="color:#B392F0"> work</span><span style="color:#E1E4E8">(self):</span></span>
<span class="line"><span style="color:#9ECBFF">      """"""</span></span>
<span class="line"><span style="color:#F97583">      while</span><span style="color:#F97583"> not</span><span style="color:#79B8FF"> WORK_DONE</span><span style="color:#E1E4E8">:</span></span>
<span class="line"><span style="color:#6A737D">         # Keep working.</span></span>
<span class="line"><span style="color:#79B8FF">         self</span><span style="color:#E1E4E8">.use(tool)</span></span>
<span class="line"></span>
<span class="line"><span style="color:#F97583">      return</span><span style="color:#79B8FF"> WORK_DONE</span></span>
<span class="line"></span>
<span class="line"></span>
<span class="line"><span style="color:#F97583">   def</span><span style="color:#79B8FF"> __len__</span><span style="color:#E1E4E8">(self):</span></span>
<span class="line"><span style="color:#9ECBFF">      """Fun Fact"""</span></span>
<span class="line"><span style="color:#F97583">      return</span><span style="color:#79B8FF"> 181</span><span style="color:#6A737D"> # cm</span></span>
<span class="line"></span>
<span class="line"></span>
<span class="line"><span style="color:#F97583">   def</span><span style="color:#79B8FF"> __repr__</span><span style="color:#E1E4E8">(self):</span></span>
<span class="line"><span style="color:#9ECBFF">      """"""</span></span>
<span class="line"><span style="color:#F97583">      return</span><span style="color:#F97583"> f</span><span style="color:#9ECBFF">"</span><span style="color:#79B8FF">{self</span><span style="color:#E1E4E8">.name</span><span style="color:#79B8FF">}</span><span style="color:#9ECBFF"> an </span><span style="color:#79B8FF">{self</span><span style="color:#E1E4E8">.age</span><span style="color:#79B8FF">}</span><span style="color:#9ECBFF"> y.o self-taught developer, working as </span><span style="color:#79B8FF">{self</span><span style="color:#E1E4E8">.role</span><span style="color:#79B8FF">}</span><span style="color:#9ECBFF">"</span></span>
<span class="line"></code></pre>


## Skills and Tools

### **Languages**
- ![Python](https://img.shields.io/badge/-Python-blue) 
- ![C](https://img.shields.io/badge/-C-green) 
- ![Bash](https://img.shields.io/badge/-Bash-black)  
- ![HTML](https://img.shields.io/badge/-HTML-orange)
- ![CSS](https://img.shields.io/badge/-CSS-blue) 
- ![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)

### **Frameworks and Libraries**
- ![React](https://img.shields.io/badge/-React-blue) 
- ![React Native](https://img.shields.io/badge/-React%20Native-lightblue)
- ![Django](https://img.shields.io/badge/-Django-darkgreen) 
- ![FastAPI](https://img.shields.io/badge/-FastAPI-teal) 
- ![REST API](https://img.shields.io/badge/-REST%20API-brightgreen)
- ![Tkinter](https://img.shields.io/badge/-Tkinter-blueviolet)
- ![Beautiful Soup](https://img.shields.io/badge/-Beautiful%20Soup-yellowgreen) 
- ![Selenium](https://img.shields.io/badge/-Selenium-lightgreen)

### **Databases**
- ![MySQL](https://img.shields.io/badge/-MySQL-blue)
- ![MongoDB](https://img.shields.io/badge/-MongoDB-brightgreen)
- ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-lightblue)

### **Development Tools**
- ![VSCode](https://img.shields.io/badge/-VSCode-blue)
- ![Git](https://img.shields.io/badge/-Git-orange)
- ![GitHub](https://img.shields.io/badge/-GitHub-black)

### **Operating Systems**
- ![Linux](https://img.shields.io/badge/-Linux-yellow)
- ![Windows](https://img.shields.io/badge/-Windows-blue) 
- ![Mac OS](https://img.shields.io/badge/-Mac%20OS-silver)

### **Tools & Platforms**
- ![API Tools](https://img.shields.io/badge/-API%20Tools-darkblue)
- ![Google Workspace](https://img.shields.io/badge/-Google%20Workspace-blueviolet)
- ![Microsoft Office](https://img.shields.io/badge/-Microsoft%20Office-orange)
- ![Firefox](https://img.shields.io/badge/-Firefox-red)
- ![Chrome](https://img.shields.io/badge/-Chrome-lightgray)
- ![Penetration Testing Tools](https://img.shields.io/badge/-Penetration%20Testing%20Tools-black)


## Achievements

- 🥇 **Certified in Professional Foundations** (ALX Program)  
- 📈 **Contributed to 50+ open-source projects**  
- 🌟 **Maintainer of 5 repositories with 100

## 📧 Contact Info

- **Email**: [abderrahim@example.com](mailto:abidabderrahim01@gmail.com)  
- **LinkedIn**: [linkedin.com/in/abderrahim](https://www.upwork.com/freelancers/~01edac6730544c1cb3?mp_source=share)  
- **Upwork**: [upwork.com/freelancers/~abderrahim](https://www.upwork.com/freelancers/~01edac6730544c1cb3?mp_source=share)

## Certifications

- **AI Career Essentials** (ALX Program) [Repository Link](https://github.com/abidabderrahim/AI-Career-Essentials-Certificate)
- **Git-at-a-Startup** (ALX Program) [Repository Link](https://github.com/abidabderrahim/gig-at-a-startup-certificate)
- **Professional Foundations** (ALX Program) [Repository Link](https://github.com/abidabderrahim/abidabderrahim-Professional-Foundations-Certificate)
