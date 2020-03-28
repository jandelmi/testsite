---
# Display name
name: Juho Andelmin

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: Doctoral Candidate

# Organizations/Affiliations
organizations:
- name: Aalto University School of Science
  url: "https://sal.aalto.fi/en/personnel/juho.andelmin"

# Short bio (displayed in user profile at end of posts)
bio: My current research is focused on multi-stage decision optimization under uncertainty.

interests:
- Mathematical Optimization
- Decision Analysis
- Computer Science

education:
  courses:
  - course: Doctoral Candidate in Mathematics and Systems Analysis
    institution: Aalto University School of Science
    year: 2015 --
  - course: MSc in Systems and Operations Research
    institution: Aalto University School of Science
    year: 2014
  - course: BSc in Systems Sciences
    institution: Aalto University School of Science 
    year: 2013

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "mailto:juho.andelmin@aalto.fi"
#- icon: twitter
#  icon_pack: fab
#  link: https://twitter.com/GeorgeCushen
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.com/citations?user=YmTEz4UAAAAJ&hl=fi&oi=ao
- icon: researchgate
  icon_pack: ai
  link: https://www.researchgate.net/profile/Juho_Andelmin
#- icon: github
#  icon_pack: fab
#  link: https://github.com/gcushen
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: "mailto:juho.andelmin@aalto.fi"

# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.
#user_groups:
#- Researchers
#- Visitors
---

<div style="text-align: justify">
  
I am a Doctoral Candidate in [Aalto University School of Science](https://www.aalto.fi/en/school-of-science), working as a researcher and teaching courses on various fields of Mathematical Optimization at the [Department of Mathematics and Systems Analysis](https://math.aalto.fi/en/). My other interest are Computer Science and GPU programming. Specifically, I am interested in combining techniques from Operations Research and Computer Science to develop efficient solution methods. Typical example of this could be a large-scale Mixed-Integer Linear Programming (MILP) problem with a structure that decomposes into several smaller subproblems, each of which can be solved in parallel with Constraint Programming methods. In the same vein, I am investigating how to exploit GPU computing in Mathematical Optimization to solve, for example, the subproblems mentioned above. Besides research and teaching, I have been working as a senior consultant in [WeOptIt](https://weoptit.com/) since December 2018. 

My previous research includes modeling and developing algorithms (both [exact](https://doi.org/10.1287/trsc.2016.0734) and [heuristic](https://doi.org/10.1016/j.cor.2019.04.018)) for Vehicle Routing Problems (VRPs), especially in the context of alternative fuel vehicles (e.g., [Electric VRP with Time Windows and Partial Recharges](https://sal.aalto.fi/files/personnel/juho.andelmin/tand14_public.pdf)), where fuel consumption and refueling stations are both included in the routing models. The developed algorithms utilize a novel multigraph reformulation where possible refueling station visits that can be part of an optimal solution are encoded in arcs of the multigraph - each arc corresponds to a sequence of refueling stops between two customers. I have also studied [Resource Allocation Problems](https://doi.org/10.1016/j.ejor.2020.03.031) where decision makers wish to (re-)allocate input resources among several decision-making units (e.g., supermarkets, restaurants) to maximize total outputs (e.g., profit, sales) and/or minimize total inputs. This study demonstrates that making resource allocation decisions based on conventional efficiency analysis may lead to suboptimal solutions. 

I am currently focusing on graduating and expanding my team's latest research related to the [Decision Programming](https://arxiv.org/pdf/1910.09196.pdf) framework for solving discrete multi-stage decision-making problems under uncertainty. These problems are often modeled as influence diagrams and solved with enumeration techniques such as Dynamic Programming. Decision Programming, however, employs MILP formulations to solve such problems, thereby extending the modeling capabilities of earlier approaches. The Decision Programming framework makes it possible to: (i) omit the usual 'no forgetting' assumption in that earlier decisions need not be known when making later ones; (ii) use multiple objectives simultaneously, including a variety of risk measures; and (iii) include several kinds of deterministic and chance constraints. Model uncertainties can be endogenous or exogenous, and, in presence of multiple objectives, all non-dominated decision strategies can be computed with a MILP solver by utilizing cutting planes that exclude dominated decision strategies.

</div>
