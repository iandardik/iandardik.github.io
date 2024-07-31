---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
footer: null
---
<html>
  <head>
    <meta charset="utf-8">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="/styles/mystyle.css"/>
  </head>
  <body>
    <div class="wrapper">
        <h1 class="ian">Ian Dardik</h1>
    </div>

    <div class="wrapper">
        <img src="images/ian_dardik_cmu.jpg" width="200" class="float-left"/>
        <div class="side-panel">
            <p>
                I am a Software Engineering Ph.D. student at Carnegie Mellon University.
                My research interests are in Formal Methods and Software Engineering with applications to Distributed Systems and Cyber Physical Systems.
            </p>
            <ul class="social-media-list">
                <li>
                    <!--<a class="u-email" href="mailto:idardik (at) andrew (dot) cmu (dot) edu">idardik (at) andrew (dot) cmu (dot) edu</a>-->
                    Email: idardik (at) andrew (dot) cmu (dot) edu
                </li>
                <li>
                    <a href="https://github.com/iandardik">
                        <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#github"></use></svg>
                        <span class="username">iandardik</span>
                    </a>
                </li>
                <li>
                    <a href="https://www.twitter.com/IanDardik">
                        <svg class="svg-icon"><use xlink:href="/assets/minima-social-icons.svg#twitter"></use></svg>
                        <span class="username">IanDardik</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>

    <div class="wrapper pub-list sect">
        <h2>Publications</h2>
        <ul>
            <li>
                <a href="papers/recomp_fmcad24.pdf"><h3>Recomposition: A New Technique for Efficient Compositional Verification</h3></a>
                <p>
                    <b>Ian Dardik</b>, April Porter, Eunsuk Kang <br/>
                    <i>To appear in FMCAD 2024</i>
                </p>
            </li>
            <li>
                <a href="papers/fortis_fmcad23.pdf"><h3>Fortis: A Tool for Analysis and Repair of Robust Software Systems</h3></a>
                <p>
                    Changjian Zhang, <b>Ian Dardik</b>, Rômulo Meira-Góes, David Garlan, Eunsuk Kang. <br/>
                    <i>FMCAD 2023</i> (Tool paper)
                </p>
            </li>
            <li>
                <a href="papers/safe_env_cav23.pdf"><h3>Safe Environmental Envelopes of Discrete Systems</h3></a>
                <p>
                    Rômulo Meira-Góes, <b>Ian Dardik</b>, Eunsuk Kang, Stéphane Lafortune, Stavros Tripakis. <br/>
                    <i>CAV 2023</i>
                </p>
            </li>
            <li>
                <a href="papers/ind_inf_fmcad22.pdf"><h3>Plain and Simple Inductive Invariant Inference for Distributed Protocols in TLA+</h3></a>
                <p>
                    William Schultz, <b>Ian Dardik</b>, Stavros Tripakis. <br/>
                    <i>FMCAD 2022</i>
                </p>
            </li>
            <li>
                <a href="papers/verif_cpp22.pdf"><h3>Formal Verification of a Distributed Dynamic Reconfiguration Protocol</h3></a>
                <p>
                    William Schultz, <b>Ian Dardik</b>, Stavros Tripakis. <br/>
                    <i>CPP 2022</i>
                </p>
            </li>
            <li>
                <a href="papers/design_opodis21.pdf"><h3>Design and Analysis of a Logless Dynamic Reconfiguration Protocol</h3></a>
                William Schultz, Siyuan Zhou, <b>Ian Dardik</b>, Stavros Tripakis. <br/>
                <i>OPODIS 2021</i>
            </li>
        </ul>
    </div>

    <div class="wrapper sect">
        <h2>Bio</h2>
        <p>At Carnegie Mellon, I am advised by Professor <a href="https://eskang.github.io/">Eunsuk Kang</a> and a member of <a href="https://cmu-soda.github.io/">SoDA Lab</a>.</p>
        <p>Prior to joining CMU, I was a Masters student at Northeastern University in the <a href="https://www.khoury.northeastern.edu/information-for-overview/current-masters-and-certificate-students/khoury-research-apprenticeship/past-participants/">Khoury Research Apprenticeship Program</a>, supervised by Professor <a href="http://www.ccs.neu.edu/~stavros/">Stavros Tripakis</a>.</p>
    </div>
  </body>
</html>
