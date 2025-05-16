---
layout: sidebar
permalink: /research/
title: research

---

## Selected Works in Progress 
<div style="display: flex; justify-content: space-between; align-items: baseline; max-width: 700px; margin-left: 0; margin-top: 1.5rem;">
  <div>
    <strong>Firms Believing Women Get Less Means They Do</strong><br>
    (with <a href="https://nancywang3.github.io" target="_blank">Nancy Wang</a>)
  </div>

  <a class="btn btn-sm btn-outline-primary" 
     href="/assets/papers/Lowballing.pdf" 
     target="_blank"
     onclick="gtag('event', 'click', {
       event_category: 'Research',
       event_label: 'Firms Believing Women Get Less Means They Do'
     });">
     PDF
  </a>
</div>
<details>
  <summary>Abstract</summary> 
  This paper examines an employer-driven mechanism behind the early-career gender earnings gap using novel data on MIT graduates’ job offers and negotiation process. We document three key findings. First, women receive lower initial compensation offers than men within an employer-occupation. Second, this gap is entirely concentrated in non-salary components—signing bonus and equity—with no gap in base salary. Third, we find no gender differences in job search, and women negotiate as frequently and successfully as men. These findings also generalize to a national sample of high-skill workers in a dataset from Levels.fyi. To understand these patterns, we develop a model showing that a small number of discriminatory firms leads <em>all firms</em> in the market to lowball women in equilibrium. This market-wide gender gap is sustained through outside offers and cannot be closed by changes in worker behavior. We validate this mechanism using an incentivized resume evaluation experiment with recruiters, where we find that firms expect <em>other firms</em> to offer women less. Our results highlight the role of firm behavior—rather than worker decisions alone—in perpetuating gender pay disparities. 
</details> 


<br>
**Screening or Exclusion? Reduced standardized testing and academic mismatch** \
(with [Kartik Vira](https://economics.mit.edu/people/phd-students/kartikeya-vira))
<details>
  <summary>Abstract</summary> 
The fairness and effectiveness of standardized testing in higher education have been heavily scrutinized, most saliently with the rise of SAT-optional admissions. Despite this growing debate, empirical evidence on how reducing standardized testing affects academic sorting and educational outcomes is scarce. This project examines a reform that gradually reduced subject-specific standardized testing requirements in parts of the UK. We present a stylized framework to show that such reforms increase university attendance, but their effects on distributional outcomes and mismatch are ambiguous when teachers and tests have different demographic biases and noise. Using an event-study design, we find that the reform increased enrollment in academic-track subjects in high school, particularly in STEM, and boosted university application and enrollment by 7pp among disadvantaged students. A small subset of these students succeed: they are 1pp more likely to graduate university and less likely to begin their careers at bad firms. However, we also find evidence of aggregate academic mismatch — conditional on attending university, treated students are 3pp less likely to graduate on time and have lower GPAs.
</details> 

<br>
**Friends in Higher Places: Can exposure to high-achieving peers raise university aspirations for disadvantaged students?** \
(with [Kartik Vira](https://economics.mit.edu/people/phd-students/kartikeya-vira))
<details>
  <summary>Abstract</summary> 
Lower-income students apply to and attend elite universities at lower rates than high-income students with similar grades. We examine whether and how lack of exposure to attendees of prestigious universities and social perceptions shape these socioeconomic gaps by combining analysis of administrative data with surveys and a field experiment at high schools in the UK. First, we show that a high school student attending a particular elite university raises the probability of future students from that school applying to that university, and that these students go on to successfully graduate and obtain higher earnings after graduation. This suggests that limited exposure may deter applications from low-income students even when they would succeed at elite universities. To learn more about the mechanisms underlying these effects and evaluate scalable policy interventions, we conduct a survey and field experiment at over 20 UK high schools, where we randomly induce exposure to students attending less familiar universities via videos from current students, one-on-one mentorship, and subsidized visits to universities.
</details> 

<br>
**The Effect of Confidence in Ability on Job Search Behavior** \
(with [Maxim Massenkoff](https://maximmassenkoff.com/) and [Nancy Wang](https://nancywang3.github.io))

<br>

## Publications
**Trade Competition and the Decline in Union Organizing: Evidence from Certification Elections** \
(with [Kerwin K. Charles](https://economics.mit.edu/people/phd-students/kartikeya-vira) and [Matthew S. Johnson](https://sites.google.com/site/mslaterjohnson/research)). <em>Forthcoming<em>, <strong>Journal of Labor Economics<strong>. 
<details>
  <summary>Abstract</summary> 
We assess whether and why trade competition partly explains the sharp decline in U.S. workers' attempts to organize labor unions in recent decades. We find that the swift rise of imports from China in the early 2000s led to substantially lower rates of union certification elections, both among workers in manufacturing industries directly exposed to imports and among workers indirectly exposed through their local labor market. Consistent with a simple model of workers' decision to seek union representation, direct exposure lowered the expected wage gain from unionization, whereas indirect exposure increased the cost of job loss, both of which discourage organizing.
</details> 

<script>
  document.addEventListener('DOMContentLoaded', function () {
    // Track when any <details> is opened
    document.querySelectorAll('details').forEach(function (el) {
      el.addEventListener('toggle', function () {
        if (el.open) {
          const title = el.previousElementSibling?.innerText || 'Unnamed abstract';
          gtag('event', 'abstract_open', {
            event_category: 'Research',
            event_label: title.trim()
          });
        }
      });
    });
  });
</script>