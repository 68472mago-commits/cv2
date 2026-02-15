:root {
    --primary: #1a365d;
    --secondary: #2d3748;
    --accent: #4299e1;
    --light: #f7fafc;
    --gray: #718096;
    --light-gray: #e2e8f0;
    --white: #ffffff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: var(--secondary);
    background-color: #f5f7fa;
    padding: 20px;
}

.cv-container {
    max-width: 1200px;
    margin: 0 auto;
    background: var(--white);
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    border-radius: 10px;
    overflow: hidden;
}

/* Header */
.header {
    background: linear-gradient(135deg, var(--primary), var(--secondary));
    color: var(--white);
    padding: 40px;
    display: flex;
    align-items: center;
    gap: 30px;
}

.profile-img {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    object-fit: cover;
    border: 5px solid rgba(255,255,255,0.2);
    box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

.header-content h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
    font-weight: 700;
}

.header-content .title {
    font-size: 1.5rem;
    color: var(--accent);
    margin-bottom: 15px;
    font-weight: 300;
}

.header-content p {
    font-size: 1.1rem;
    opacity: 0.9;
    max-width: 800px;
}

/* Contact Info */
.contact-info {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 20px;
    padding: 0;
    list-style: none;
}

.contact-info li {
    display: flex;
    align-items: center;
    gap: 8px;
    font-size: 1rem;
}

.contact-info a {
    color: var(--white);
    text-decoration: none;
    transition: opacity 0.3s;
}

.contact-info a:hover {
    opacity: 0.8;
    text-decoration: underline;
}

/* Main Content */
.main-content {
    display: grid;
    grid-template-columns: 1fr 350px;
    gap: 40px;
    padding: 40px;
}

/* Sections */
.section {
    margin-bottom: 35px;
}

.section-title {
    color: var(--primary);
    font-size: 1.5rem;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 3px solid var(--accent);
    position: relative;
}

.section-title::after {
    content: '';
    position: absolute;
    bottom: -3px;
    left: 0;
    width: 60px;
    height: 3px;
    background: var(--accent);
}

/* Professional Summary */
.summary {
    font-size: 1.1rem;
    line-height: 1.8;
    color: var(--secondary);
    margin-bottom: 25px;
}

/* Experience */
.experience-item {
    margin-bottom: 25px;
    padding-bottom: 25px;
    border-bottom: 1px solid var(--light-gray);
}

.experience-item:last-child {
    border-bottom: none;
}

.job-title {
    font-size: 1.2rem;
    font-weight: 600;
    color: var(--primary);
    margin-bottom: 5px;
}

.company {
    color: var(--accent);
    font-weight: 500;
    margin-bottom: 5px;
}

.date {
    color: var(--gray);
    font-style: italic;
    margin-bottom: 10px;
    font-size: 0.95rem;
}

.responsibilities {
    list-style: none;
    padding-left: 0;
}

.responsibilities li {
    position: relative;
    padding-left: 20px;
    margin-bottom: 8px;
}

.responsibilities li::before {
    content: "▸";
    color: var(--accent);
    position: absolute;
    left: 0;
}

/* Skills */
.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
}

.skill-category {
    margin-bottom: 15px;
}

.skill-category h4 {
    color: var(--primary);
    margin-bottom: 10px;
    font-size: 1.1rem;
}

.skill-list {
    list-style: none;
    padding-left: 0;
}

.skill-list li {
    background: var(--light);
    padding: 8px 15px;
    margin-bottom: 8px;
    border-radius: 20px;
    border-left: 4px solid var(--accent);
}

/* Education */
.education-item {
    padding: 15px;
    background: var(--light);
    border-radius: 8px;
    margin-bottom: 15px;
}

.education-title {
    font-weight: 600;
    color: var(--primary);
    margin-bottom: 5px;
}

/* Projects */
.project-item {
    padding: 15px;
    background: var(--light);
    border-radius: 8px;
    margin-bottom: 15px;
    border-left: 4px solid var(--accent);
}

.project-title {
    font-weight: 600;
    color: var(--primary);
    margin-bottom: 5px;
}

/* Certifications */
.cert-badge {
    display: inline-block;
    background: var(--accent);
    color: white;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.9rem;
    margin-right: 10px;
    margin-bottom: 10px;
    text-decoration: none;
    transition: transform 0.3s;
}

.cert-badge:hover {
    transform: translateY(-2px);
}

/* Links */
.link-list {
    list-style: none;
    padding-left: 0;
}

.link-list li {
    margin-bottom: 10px;
}

.link-list a {
    color: var(--accent);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: color 0.3s;
}

.link-list a:hover {
    color: var(--primary);
    text-decoration: underline;
}

/* Sidebar */
.sidebar {
    background: var(--light);
    padding: 30px;
    border-radius: 10px;
    height: fit-content;
}

/* Responsive */
@media (max-width: 992px) {
    .main-content {
        grid-template-columns: 1fr;
    }
    
    .header {
        flex-direction: column;
        text-align: center;
        padding: 30px 20px;
    }
    
    .profile-img {
        width: 120px;
        height: 120px;
    }
    
    .contact-info {
        justify-content: center;
    }
}

@media (max-width: 768px) {
    .header-content h1 {
        font-size: 2rem;
    }
    
    .header-content .title {
        font-size: 1.3rem;
    }
    
    .main-content {
        padding: 20px;
    }
    
    .skills-grid {
        grid-template-columns: 1fr;
    }
}

/* Print Styles */
@media print {
    body {
        background: white;
        padding: 0;
    }
    
    .cv-container {
        box-shadow: none;
        border-radius: 0;
    }
    
    .header {
        padding: 30px;
    }
    
    .main-content {
        padding: 30px;
    }
    
    .cert-badge, .link-list a {
        color: black !important;
    }
}