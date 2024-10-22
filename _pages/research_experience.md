---
layout: default
permalink: /blog/
title: Research
nav: true
nav_order: 1
toc:
  sidebar: left
pagination:
  enabled: true
  collection: posts
  permalink: /page/:num/
  per_page: 5
  sort_field: date
  sort_reverse: true
  trail:
    before: 1 # The number of links before the current page
    after: 3 # The number of links after the current page
---


<style>
/* 调整全局字体 */
body {
    font-size: 16px; /* 基准字体大小 */
    /* font-family: Verdana, sans-serif; */
    font-family: Tahoma, sans-serif;
    line-height: 1.6; /* 行间距 */
    color: #333;
}

/* 针对不同标题的字体大小和粗细 */
h2 {
    font-size: 1.8em; /* 标题2的大小 */
    font-weight: bold; /* 标题加粗 */
    margin-top: 30px;
    margin-bottom: 20px;
}

h3 {
    font-size: 1.3em; /* 标题3的大小 */
    font-weight: bold; /* 标题加粗 */
    margin-top: 25px;
    margin-bottom: 15px;
}

/* 调整段落和列表的字体大小及间距 */
p {
    font-size: 1em; /* 段落字体大小 */
    font-weight: normal; /* 正文字体粗细 */
    margin-bottom: 15px;
}

ul li {
    font-size: 0.95em; /* 列表项字体稍微小一点 */
    margin-bottom: 10px; /* 列表项之间的间距 */
}

/* 强调的文本加粗 */
strong {
    font-weight: bold;
}
</style>

<!-- github信息
<style>
    .github-link {
        background-color: #24292e;
        color: white;
        padding: 8px 12px;
        text-decoration: none;
        border-radius: 5px;
        font-size: 14px;
        display: inline-block;
    }

    .github-link:hover {
        background-color: #444;
    }
</style> -->

<h1>Research & Course Projects</h1>

<h2>Publications & Manuscripts</h2>

1. Zhixu Li*, <strong>Xiaokang Sun*</strong>, Mingyu Cai, Jiachen Li. “Good Data Matters: STL-Enhanced Data-Efficient Imitation Learning for Long-Horizon Manipulation.” Accepted for presentation at <em>the 2024 Southern California Robotics Symposium</em> (SCR). Planned submission to <strong>IEEE Robotics and Automation Letters</strong>. (Co-first authorship)



<h2>Research Experiences</h2>
<div class="experience">
    <h3>1. STL-Enhanced Data-Efficient IL for Long-Horizon Manipulation</h3>
    <p><strong>Advisor:</strong> Jiachen Li. University of California, Riverside (TASL)   ｜   July 2024 – October 2024</p>    
    <ul>
        <li>Co-led the project with a Ph.D. student, responsible for algorithm design and low-level implementation.</li>
        <li>Developed an LLM-based task planner using STL for long-horizon manipulation and automatic data annotation.</li>
        <li>Introduced a task difficulty rating module for low-level active imitation learning, optimizing data distribution to enhance
the data efficiency of skill acquisition.</li>
    </ul>
</div>
<div class="experience">
    <h3>2. Visual-Tactile Fusion-Based Regrasping Policy Learning</h3>
    <p><strong>Advisor:</strong> Yao Jiang. Tsinghua University (ME)   |   July 2024 – Present</p>
    <ul>
        <li>Co-led the project with a Ph.D. student, focusing on algorithm design and conducting simulations.</li>
        <li>Integrated visual and tactile perception to enable regrasping after grasp failures on objects with varying surface textures
and mass distributions.</li>
        <li>Applied reinforcement learning for grasping skill acquisition and validated the approach in simulated environments.</li>
    </ul>
</div>
<div class="experience">
    <h3>3. Wearable Fingertip Tactile Rendering Devices Based on Parallel Mechanisms</h3>
    <p><strong>Advisor:</strong> Yao Jiang. Tsinghua University (ME) | October 2023 – Present</p>
    <ul>
        <li>Co-developed fingertip haptic rendering devices with another undergraduate and a Ph.D. student, focused on improving flexibility and rendering capabilities for enhanced user experience.</li>
        <li>Completed the mechanism design, 3D modeling, and 3D printing, while actively developing test software to evaluate device performance.</li>
        <li>Aiming for future integration with advanced tactile sensors to enhance robotic tactile perception for remote manipulation and similar applications.</li>
    </ul>
</div>
<div class="experience">
    <h3>4. Fine-tuned Sim-to-sim Framework for Mitigating Sim-to-real Problem</h3>
    <p><strong>Advisor:</strong> Jianyu Chen. Tsinghua University (IIIS) | February 2024 – June 2024</p>
    <ul>
        <li>Collaborated on validating policies with real humanoid robots to ensure robustness across different environments.</li>
        <li>Fine-tuned learned policies in a sim-to-sim framework to address sim-to-real transfer challenges.</li>
        <li>Conducted simulations in MuJoCo and Isaac Gym, refining models for better real-world performance.</li>
    </ul>
</div>
<div class="experience">
    <h3>5. Brain-Machine Integrated Intelligent Animal Experiment Platform</h3>
    <p><strong>Advisor:</strong> Mingjun Zhang. Tsinghua University (BME) | August 2022 – January 2023</p>
    <ul>
        <li>Developed a brain-machine hybrid intelligence platform for experiments with mice and miniature pigs, expanding applications in brain-computer interfaces.</li>
        <li>Designed the structure and completed 3D printing of a mini-vehicle platform, supporting the experimental setup.</li>
        <li>Gained significant skills in mechanical design and hardware programming, which are essential for robotics research.</li>
    </ul>
</div>



<!-- 课程项目 -->
<h2>Selected Projects</h2>
<div class="experience">
    <h3>1. Blocks Classification and Stacking with UR-5</h3>
    <p><strong>Course:</strong> <em>Smart Robot Manipulation</em>. Perception, Planning, Control | June 2024  <a href="https://github.com/Studeas/Smart_Robot_Manipulation_2024" target="_blank">[GitHub]</a></p>
    <ul>
        <li>Performed block detection, classification, and stacking, ensuring task completeness, safety, and speed of execution.</li>
        <li>Implemented a full pipeline grasping task on UR-5 using ROS, MoveIt, OpenCV, and other frameworks and tools.</li>
    </ul>
</div>
<div class="experience">
    <h3>2. Image Classification by Head Features</h3>
    <p><strong>Course:</strong> <em>Principles of AI</em>. Machine Learning, Image Classification | December 2023  <a href="https://github.com/Studeas/Principle_of_AI_2023" target="_blank">[GitHub]</a></p>
    <ul>
        <li>Applied ML methods to solve binary and five-class head feature classification problems.</li>
        <li>Strengthened foundational knowledge in image classification and practiced the application of PyTorch and NumPy.</li>
    </ul>
</div>
<div class="experience">
    <h3>3. Bipedal Robot Walking Based on PDW</h3>
    <p><strong>Course:</strong> <em>Research and Practice</em>. Humanoid Robot, PDW, MATLAB | December 2023</p>
    <ul>
        <li>Developed a walking model based on Passive Dynamic Walking (PDW), powered by center of mass (COM) movement.</li>
        <li>Proposed and verified a passive walking solution, including literature review, simulation, and reporting.</li>
    </ul>
</div>
<div class="experience">
    <h3>4. Optical Field Imaging and Digital Refocusing Experiment</h3>
    <p><strong>Course:</strong> <em>Smart Sensing and Measuring</em>. Refocus | December 2023</p>
    <ul>
        <li>Gained deep understanding of light field imaging and digital refocusing algorithms.</li>
        <li>Conducted experiments using a light field camera, captured images, implemented digital refocusing algorithms.</li>
    </ul>
</div>
<div class="experience">
    <h3>5. Escape Tower of the Sorcerer: Search Algorithms Application</h3>
    <p><strong>Course:</strong> <em>Principles of AI</em>. Search Algorithms | October   <a href="https://github.com/Studeas/Principle_of_AI_2023" target="_blank">[GitHub]</a></p>
    <ul>
        <li>Built a simplified Tower of the Sorcerer scenario and implemented a search algorithm for character escape.</li>
        <li>Implemented algorithms to solve high-complexity search problems and developed a visual interface to display.</li>
    </ul>
</div>
<div class="experience">
    <h3>6. Remote-controlled Robotic Arm & Small Vehicle Based on PSoC</h3>
    <p><strong>Course:</strong> <em>Modern Electronics</em>. PSoC, FPGA | August 2023</p>
    <ul>
        <li>Designed motion unit functions, UART communication and controllers for the remote-controlled robotic arm.</li>
        <li>Cultivated the ability to debug hardware programs and troubleshoot circuit faults.</li>
    </ul>
</div>
<div class="experience">
    <h3>7. Holiday Management Software Development</h3>
    <p><strong>Course:</strong> <em>Object Oriented Programming (OOP)</em>. C++ | July 2023  <a href="https://github.com/Studeas/Holiday-Management-OOP" target="_blank">[GitHub]</a></p>
    <ul>
        <li>Independently completed the design of a holiday management software and wrote several thousand lines of code.</li>
        <li>Conformed to MVC pattern and OOP principles, developed a good coding style.</li>
    </ul>    
</div>