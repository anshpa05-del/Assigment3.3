HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College Information</title>
</head>
<body>

    <!-- Section 1: Introduction (Requirement 1 & 6) -->
    <header>
        <h1>Welcome to the School of Computer Science & Technology</h1>
    </header>

    <main>
        <section id="introduction">
            <h2>About Our Department</h2>
            <p>
                The School of Computer Science & Technology provides students with a robust foundation 
                in software engineering, modern web technologies, modern computer architectures, and data science. 
                Our curriculum balances theoretical principles with practical project work to prepare students for tech industry careers.
            </p>
        </section>

        <!-- Section 2: Unordered List of Departments/Subjects (Requirement 2 & 6) -->
        <section id="departments">
            <h2>Offered Core Subjects</h2>
            <ul>
                <li>Web Development & Internet Technologies</li>
                <li>Data Structures & Algorithms</li>
                <li>Database Management Systems</li>
                <li>Operating Systems</li>
                <li>Software Engineering</li>
            </ul>
        </section>

        <!-- Section 3: Ordered List for Admission Process (Requirement 3 & 6) -->
        <section id="admissions">
            <h2>Admission Process</h2>
            <ol>
                <li>Fill out the online application form on the university portal.</li>
                <li>Upload official high school or prior university transcripts.</li>
                <li>Submit standardized test scores or complete the department entrance test.</li>
                <li>Attend the online or in-person counseling and interview session.</li>
                <li>Pay the initial seat acceptance fee to confirm enrollment.</li>
            </ol>
        </section>

        <!-- Section 4: Nested List for Subject Topics (Requirement 4 & 6) -->
        <section id="curriculum">
            <h2>Syllabus Breakdown: Web Development</h2>
            <ul>
                <li>
                    <strong>HTML5 Foundations</strong>
                    <ul>
                        <li>Document Structure & Metadata</li>
                        <li>Text Formatting & Headings</li>
                        <li>Ordered, Unordered, and Description Lists</li>
                    </ul>
                </li>
                <li>
                    <strong>CSS Styling</strong>
                    <ul>
                        <li>Selectors and Specificity</li>
                        <li>Flexbox and Grid Layouts</li>
                        <li>Responsive Web Design</li>
                    </ul>
                </li>
                <li>
                    <strong>JavaScript Basics</strong>
                    <ul>
                        <li>Variables & Data Types</li>
                        <li>DOM Manipulation</li>
                        <li>Event Handling</li>
                    </ul>
                </li>
            </ul>
        </section>

        <!-- Section 5: Description List for Faculty/Course Details (Requirement 5 & 6) -->
        <section id="faculty">
            <h2>Faculty Overview</h2>
            <dl>
                <dt><strong>Dr. Alan Turing</strong></dt>
                <dd>Head of Computer Science — Specializes in Algorithms and Computational Theory.</dd>

                <dt><strong>Prof. Grace Hopper</strong></dt>
                <dd>Lead Instructor — Specializes in Systems Programming and Compilers.</dd>

                <dt><strong>Dr. Tim Berners-Lee</strong></dt>
                <dd>Senior Lecturer — Specializes in Web Architecture and Hypermedia Systems.</dd>
            </dl>
        </section>
    </main>

</body>
</html>