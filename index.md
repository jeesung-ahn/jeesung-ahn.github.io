---
title: "Jeesung Ahn"
name: index
layout: page
description: Personal Website of Jeesung Ahn, Ph.D. in Psychology at Penn.
hide_description: yes
editor_options:
  markdown:
    wrap: 72
---

<style type="text/css">
    .page-title {
        position: absolute;
        width: 1px;
        height: 1px;
        margin: -1px;
        border: 0;
        padding: 0;
        clip: rect(0 0 0 0);
        overflow: hidden;
    }
    
    h1, h2, h3 {
        text-align: center;
    }

    .section {
        display: none;
    }

    .section.active {
        display: block;
    }

    nav a {
        cursor: pointer;
    }
</style>

<script type="text/javascript">
    function toggleSection(id) {
        var sections = document.querySelectorAll('.section');
        sections.forEach(function(section) {
            section.classList.remove('active');
        });
        document.getElementById(id).classList.add('active');
    }
</script>

<nav>
    <a onclick="toggleSection('about')">About Me</a><br>
    <a onclick="toggleSection('methods')">Research Methods</a><br>
    <a onclick="toggleSection('projects')">Selected Projects</a><br>
    <a onclick="toggleSection('publications')">Publications</a><br>
    <a onclick="toggleSection('activities')">Volunteer Activities</a><br>
    <a onclick="toggleSection('fun')">For Fun</a><br>
    <a onclick="toggleSection('contact')">Contact</a>
</nav>

<div class="content">
    <div id="about" class="section active">
        <h1 class="h1" style="color: rgb(0,0,0)" id="about">About Me</h1>
        Hi there! I’m Jeesung Ahn, a postdoctoral fellow at the 
        <a href="https://www.asc.upenn.edu/research/centers/communication-neuroscience-lab">Annenberg School for Communication at the University of Pennsylvania</a>, working with 
        <a href="https://www.asc.upenn.edu/people/faculty/emily-falk-phd">Dr. Emily Falk</a>. I’m passionate about using data and science to make a positive impact on people’s lives!
        <br>
        My research primarily focuses on understanding and enhancing social connections, tackling loneliness, and improving mental health. I’m particularly interested in identifying factors that increase the risk of loneliness and understanding the brain’s role in our social connections and isolation.
        <br>
        Additionally, I build models to evaluate how behavioral interventions can promote healthier behaviors, such as increasing physical activity. By leading multidisciplinary research projects, I aim to develop personalized strategies to enhance both physical and mental well-being.
        <br>
        As a health psychologist and neuroscientist, I strive to bridge the gap between data-driven insights and real-world applications, contributing to a healthier and more connected society!
    </div>

    <div id="methods" class="section">
        <h1 class="h1" style="color: rgb(0,0,0)" id="methods-summary">Research Methods</h1>
        Over the past 9+ years, I have led comprehensive psychology and neuroscience research projects, focusing on human behavioral and neuroimaging data.
        <br>
        <br /> 
        My research methods are multidisciplinary and include the following: 
        - Experimental and survey design (including A/B tests, usability tests)
        - Data collection (recruiting, screening, surveys, experimental, behavioral, neuroimaging, experience sampling, in-depth interviews)
        - Descriptive, parametric, non-parametric, and multivariate statistics
        - Regression analysis (e.g., general linear modeling)
        - Multilevel modeling
        - Time-series analysis
        - Signal processing (e.g., denoising, despiking, temporal filtering of fMRI signals)
        - Computational network analysis (brain networks, social networks)
        - Machine learning (supervised and unsupervised)
        - Meta-analysis of multidimensional datasets
        - Qualitative content analysis (including text analysis)
        <br>
        These methods allow me to conduct thorough and rigorous research, contributing valuable insights to the fields of psychology and neuroscience.
    </div>

    <div id="projects" class="section">
        <h1 class="h1" style="color: rgb(0,0,0)" id="research">Selected Projects</h1>
        Below is the selected overview of my research projects. If you have any questions, please shoot me an email to 
        <i>jeesung@sas.upenn.edu</i>. Always happy to chat!
        <h2 style="color:rgb(2, 61, 148)">Data-Driven Promotion of Healthy Lifestyles</h2>
        <div align="center"><font size="+1"><strong>Predicting Physical Activity Behaviors after Health Message Exposure</strong></font><br>
            <a href="https://drive.google.com/file/d/1NWRufaKayrImrfLKJRvITBEs7B3uJGM2/view?usp=share_link" target="_blank">SANS 2022 Poster (top poster award winner)</a>&nbsp;&nbsp;&nbsp;
            <a href="https://www.youtube.com/watch?v=J9rV_aN-n38" target="_blank">SANS 2022 Talk</a>
        </div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/framing.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                In this *mega-analysis* of neuroimaging (fMRI) and physical activity behavioral datasets (N=366), I found the effectiveness of health message interventions in promoting physical activity can be predicted by interactions between message-level (i.e., gain vs. loss framing) and individual-level (i.e., baseline levels of physical activity) characteristics.
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Explaining Alcohol Craving-Drinking Links using Brain Network Dynamics</strong></font><br>
            <a href="https://osf.io/qr9gx" target="_blank">OSF Preregistration</a>&nbsp;&nbsp;&nbsp;
            <a href="https://psyarxiv.com/cj2nx" target="_blank">Study Protocol</a>
        </div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/shine_protocol.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                I ran multi-level models to examine whether the modular organization of functional connectivity networks in the brain (measured by fMRI) can explain real-world associations between alcohol craving and drinking in non-dependent social drinkers (measured by daily experience sampling for one month).
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Using Machine Learning to Promote Healthy Eating</strong></font><br>
            <a href="https://github.com/jeesung-ahn/Nutrients_Project_ModernDataMining" target="_blank">Data+Code in GitHub</a>&nbsp;&nbsp;&nbsp;
            <a href="http://jh-cai.com/modern-data-mining/dsl.html" target="_blank">Wharton Data Science Live</a>
        </div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/mdm.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                <br>
                My goal was to create a data-driven algorithm that provides personalized food recommendations based on an individual’s dietary needs. I performed exploratory data analyses and unsupervised machine learning (PCA, K-means clustering using R) on a 
                <a href="https://www.canada.ca/en/health-canada/services/food-nutrition/healthy-eating/nutrient-data/canadian-nutrient-file-2015-download-files.html">dataset</a> with 5690 (food) x 154 (nutrients) dimensions. As a result, I was able to cluster 5690 food items into 8 categories and simulate real-world examples where I give food recommendations to individuals who are in need of dietary restrictions.
            </div>
        </div>
        <br>
        <h2 style="color:rgb(2, 61, 148)">Connecting Mental Well-Being with Networks in the Brain and Society</h2>
        <div align="center"><font size="+1"><strong>Neural Responses to Peers’ Faces Predict Vulnerability to Loneliness during COVID-19</strong></font><br> 
            <i>2 upcoming conference presentations in 2023</i>
        </div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/covid_loneliness_findings.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                I tested whether neural responses to peers' faces predict the likelihood of becoming lonelier from before to after the COVID-19 pandemic. Findings suggested that lonelier individuals may assign greater emotional salience to self-relevant social stimuli. Furthermore, individuals who showed greater reward sensitivity to peers' faces were more likely to become lonely in response to social stressors such as social isolation during the pandemic.
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Self- vs. Peer- Evaluated Social Status, Mental Health and Social Brains</strong></font></div>
        <br>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/evaluation_findings.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                In this large-scale multi-disciplinary study, we adopted Round Robin design where entire members of campus social groups were recruited. Participants rated themselves and their peers' social status such as likability, attractiveness, and influence over others. Here, I asked three questions: 1) is there a discrepancy between social status that is evaluated by self *vs.* peers?; 2) would under (or over)-evaluating one's social status be associated with poorer mental health?; 3) would under (or over)-evaluating one's social status be associated with thinking more about *others'* thoughts and feelings?
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Developing a Mobile Application for Emotionally and Socially Distressed Individuals</strong></font><br>
            <a href="https://jeesungjessahn.wixsite.com/jeesung/emotional-labor-emoattention" target="_blank">Brief Summary of Related Projects</a>&nbsp;&nbsp;
            <a href="https://6d09de35-a4c2-4d69-8868-8eb5687990c4.filesusr.com/ugd/a6cdc2_09565be4736d4293a135ba2ea51e25d3.pdf" target="_blank">SfN 2018 Poster 1</a>&nbsp;&nbsp;
            <a href="https://6d09de35-a4c2-4d69-8868-8eb5687990c4.filesusr.com/ugd/a6cdc2_6adad23a154a4216882a3e54f7b7040a.pdf" target="_blank">SfN 2018 Poster 2</a>
        </div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/EmoLab_fcMVPA.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                I designed and conducted A/B tests for a mobile application that provides cognitive training to modify attentional bias towards negative social stimuli (*Attentional Bias Modification, ABM*). I recruited healthy controls, individuals who have social anxiety, and service workers who were undergoing extreme emotional load at workplaces. Participants performed the ABM task inside the fMRI scanner as well as on their smartphones. We conducted machine-learning classification of brain functional connectivity networks when participants were performing the ABM task and found socially distressed individuals show attentional bias to negative faces (*vs.* neutral faces) both at the behavioral and neural levels.
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Physical Activity and Loneliness: A Systematic Review of Intervention Studies</strong></font></div>
        <div class="row">
            <div class="column">
                <img class="proj-image" src="/assets/img/review_paper.png" style="height: 100%; width: 100%; object-fit: contain">
            </div>
            <div class="column" markdown="1">
                I qualitatively reviewed literature that examined the effects of interventions that are designed to tackle two important public health matters: physical inactivity and loneliness. My aim was to identify which aspects of intervention most effectively improve physical inactivity and/or loneliness and whether these two variables are bi-directionally related. I proposed a psychological framework that suggests how *positive social experience* may underlie the relationship between loneliness and physical activity.
            </div>
        </div>
        <br>
        <div align="center"><font size="+1"><strong>Unraveling the Negative Loop of Perseverance Thoughts in Depression and Anxiety</strong></font></div>
        <div class="column" markdown="1">*(I was in charge of documenting, wrangling, and engineering behavioral and fMRI datasets.)*<br>
            Repetitive negative thoughts (perseverance thought, PT) are a prominent feature of many mental disorders and a robust predictor of poor clinical outcomes. Although the importance of PT as a source of impairment and an intervention target is well-recognized, it remains a difficult problem to treat. A major obstacle is our very limited understanding of what happens when people perseverate. In this study, we adopted the network control theory (NCT) analysis to examine whether clinical perseverators exhibit more temporally persistent brain states when they have to "turn off" negative thoughts in order to perform a basic cognitive task.
        </div>
    </div>

    <div id="publications" class="section">
        <h1 class="h1" style="color: rgb(0,0,0)" id="publications">Publications</h1>
        - **Ahn, J.**, Falk, E. B., & Kang, Y. (2024). Relationships between physical activity and loneliness: A systematic review of intervention studies. In Press, *Current Research in Behavioral Sciences*
        - Kang, Y., **Ahn, J.**, Cosme, D., McGowan, A., Mwilambwe‐Tshilobo, L., Zhou, D., Jovanova, M., Stanoi, O., Mucha, P., Ochsner, K., Bassett, D., Lydon‐Staley, D., & Falk, E. (2023). [Frontoparietal functional connectivity moderates the link between time spent on social media and subsequent negative affect](https://doi.org/ 10.1038/s41598-023-46040-z){:target="_blank"}, *Scientific Reports*
        - Zhou, D., Kang, Y., Cosme, D., Jovanova, M., He, X., Mahadevan, A., **Ahn, J**., Stanoi, O., Brynildsen, J., Cooper, N., Cornblath, E., Parkes, L., Mucha, P.J., Ochsner, K., Lydon-Staley, D.M., Falk, E.B., Bassett. D.S. (2023). [Mindful attention promotes control of brain network dynamics for self-regulation and discontinues the past from the present](https://doi.org/10.1073/pnas.2201074119){:target="_blank"}, *PNAS*
        - **Ahn, J**., Nah, Y., Ko, I., Han, S. (2022). [Voxel-wise Mapping of Functional Magnetic Resonance Imaging in Impression Formation](https://kiss16.kstudy.com/kiss61/download_viewer.asp){:target="_blank"}, *Science of Emotion and Sensibility*
        - Kang, Y., Cosme, D., Lydon‐Staley, D.M., **Ahn, J**., Jovanova, M., Corbani, F., Lomax, S., Stanoi, O., Strecher, V., Mucha, P.J., Oschner, K., Bassett, D.S., Falk, E.B. (2022). [Purpose in life, Neural Alcohol Cue Reactivity, and Daily Alcohol Use in Social Drinkers](https://onlinelibrary.wiley.com/doi/pdf/10.1111/add.16012){:target="_blank"}, *Addiction*
        - Cosme, D., Kang, Y., Carreras Tartak, J., **Ahn J**., Corbani, F., Cooper, N., Doré, B., He, X., Helion, C., Jovanova, M., Lomax, S., Mahadevan, A., McGowan, A.L., Paul, A., Pei, R., Resnick, A., Stanoi, O., Zhang, Y., Bassett, D.S., Boyd, Z.M., Lydon-Staley, D.M., Mucha, P.J., Ochsner, K., Falk, E.B. (2022). [Study protocol: Social Health Impact of Network Effects (SHINE) Study](https://psyarxiv.com/cj2nx/){:target="_blank"}, *PsyArXiv*
        - **Ahn J**., Lee, J., Han, J., Kang, M., Han, S (2018). [Group Analysis Data Representing the Effects of Frontopolar Transcranial Direct Current Stimulation on the Default Mode Network](https://www.sciencedirect.com/science/article/pii/S2352340918310163){:target="_blank"}, *Data in Brief*
        - **Ahn, J**., Kim, H†., Park, J., Han, S. (2018). [Interactivity of Neural Representations for Perceiving Shared Social Memory](https://koreascience.kr/article/JAKO201836262560035.pdf){:target="_blank"}, *Science of Emotion and Sensibility*
        († denotes co-first authorship)
    </div>

    <div id="activities" class="section">
        <h1 class="h1" style="color: rgb(0,0,0)" id="activities">Volunteer Activities</h1>
        I am deeply committed to utilizing my research skills to translate scientific insights into actionable outcomes in complex decision-making scenarios. In pursuit of this goal, I have actively participated in various volunteer activities, where I have been able to work on making real-world impacts on issues that are important to me.
        <br>
        **Vice President of Consulting** at 
        <a href="https://www.penngradconsulting.com/" target="_blank">Penn Graduate Consulting Club</a> (May 2023~):
        + Directed 6 project managers and 30+ analysts, successfully executing 6 consulting projects with 100% client retention
        + Cultivated strong relationships with 5+ clients, increasing the number of secured consulting projects by 200%
        + Revamped marketing strategies for effective talent recruitment, increasing member applications by 300%
        <br>
        **Consultant** at 
        <a href="https://pennbiotechgroup.org/" target="_blank">Penn Biotech Group Healthcare Consulting</a> (Sept 2022~):
        + Presented weekly deliverables to a biotechnology start-up by analyzing the market landscape for a novel cancer therapy that has the potential to significantly impact 1M+ tumor patients
        + Led in-depth interviews with healthcare stakeholders and qualitatively evaluated more than 200 clinical trials and company profiles, which helped the client to make informed decisions regarding partnership opportunities, market sizing, and product pricing
        + Executed agile and meticulous research, complemented by extensive literature reviews, in order to fulfill the client’s needs and adhere to the established timeline
        <br>
        **Data Scientist** at 
        <a href="https://web.sas.upenn.edu/dive/" target="_blank">Penn Mind Sciences Diversity and Equity Initiative</a> (Mar 2022~):
        + Designed and administered online surveys (using *Qualtrics*) to assess participants’ experience with an outreach program that provides mentorship to underrepresented minority students in their careers in science
        + Wrangled and analyzed pre- vs. post- event data, including qualitatively reviewing participants’ written feedback
        + Visualized event outcomes using *ggplot2*, *wordcloud*, and *R Markdown* and presented actionable insights and recommendations to the program organizers to improve the program
        <br>
        **Data Scientist** at 
        <a href="https://penndsg.com/" target="_blank">Penn Data Science Group</a> (Feb 2022 – May 2022): 
        + Synthesized air pollution and health data from 6 public sources (100K+ data points) into an interactive heat map, providing clients with a compelling visual aid to support informed policy-making decisions
        ![](/assets/img/air.png)
        <br>
        **UX Research Scientist** at Team QuantumLabs (April 2015 – Mar 2019):   
        + Provided consulting services to a start-up company on the efficacy of their novel neurostimulation technology in enhancing cognitive functions, such as attention capacity
        + Designed and conducted A/B tests and usability studies of their product, which led to the successful acquisition of $100K in funding
        + Led a team that presented findings to cross-functional stakeholders, including venture capital funders, designers, engineers, and clinicians, to inform and advocate the direction of product development
    </div>

    <div id="fun" class="section">
        <h1 class="h1" style="color: rgb(0,0,0)" id="funpersonalprojects">For Fun</h1>
        My Kaggle projects on predicting music (Billboard) chart positions and movie (box office) earnings are coming soon!
    </div>

    <div id="contact" class="section">
        <h2 class="h1" style="color: rgb(0,0,0)" id="contact-me">Contact</h2>
        Richards Medical Research Laboratories, 3700 Hamilton Walk, 5F,
        Philadelphia, PA 19104
        <p class="home-element">
            jeesung@sas.upenn.edu
        </p>
    </div>
</div>

<style type="text/css">
    .row {
        display: flex;
    }

    .column {
        flex: 50%;
    }

    img.proj-image {
        display: block;
        margin-right: auto;
        padding-right: 20px;
    }
</style>
