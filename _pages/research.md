---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style>
  body {
    line-height: 1.4; /* Adjust line spacing */
  }

  p, li {
    font-size: 1em; /* Font size for regular text */
  }

  .coauthors, .other-text {
    font-size: 0.9em; /* Customize specific classes if needed */
  }

  .abstract {
    display: none; /* Hide the abstract by default */
    text-align: justify; /* Justify text for better readability */
    margin-top: 5px;
  }

  h2, h3 {
    margin-top: 1.5em; /* Increase space above headings */
  }

  /* Indent subcontents and add bullet points for them */
  ul.subcontent {
    list-style-type: circle; /* Set bullet points to circles for subcontent */
    margin-left: 20px; /* Indent subcontents */
  }

  .toggle-link {
    color: #007bff;
    text-decoration: underline;
    cursor: pointer;
    font-size: 0.9em;
  }

  /* Divider between each paper */
  .underline {
    display: block;
    margin: 20px 0;
    border-bottom: 1px solid #ddd;
  }
</style>

<script>
  function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none" || abstract.style.display === "") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }
</script>

## Working Papers

<ul>
  <!-- Paper 1 -->
  <li>
    <a href="https://qifan-han.github.io/files/JMP.pdf">The Impact of Banning Online Gambling Livestreams: Evidence from Twitch.tv</a> <em>(Job Market Paper)</em>
    <ul class="subcontent">
      <li> with Jasmine Yang and Andrey Simonov</li>
      <li><span class="toggle-link" onclick="toggleAbstract('abstract1')">Abstract</span></li>
      <li id="abstract1" class="abstract">
        The necessity of content regulation on digital platforms, particularly concerning misinformation and harmful content, has sparked a growing debate. While many platforms have increasingly relied on self-regulation to address these issues, the effectiveness of such measures remains unclear, due to a potential misalignment between the incentives of the platforms and those of the regulators. We investigate the effectiveness and market consequences of self-regulation by studying Twitch's ban on online gambling livestreams in October 2022. We use a novel high-frequency panel dataset including top 6000 streamers to assess the policy impact, and leverage historical video clips, high-frequency stream titles and in-stream chats to detect banned content and streamers for identification. We find that the policy successfully decreased weekly gambling streams by 63.2% for streamers whose content were banned and a 12% among unbanned ones. However, it also resulted in a reduction of non-gambling content production, hurting content variety on the platform. Additionally, the policy had a larger impact on more popular streamers, driven by two underlying mechanisms: lower reliance on gambling content and concern for personal reputation. On the demand side, we find that the policy reduced total viewership and low-tier subscriptions among treated streamers but did not decrease revenue from their loyal viewers.
      </li>
    </ul>
  </li>

  <div class="underline"></div>

  <!-- Paper 2 -->
  <li>
    <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4538856">Collaboration Among Content Creators</a>
    <ul class="subcontent">
      <li> with Jasmine Yang and Jerath Kinshuk</li>
      <li><span class="toggle-link" onclick="toggleAbstract('abstract2')">Abstract</span></li>
      <li id="abstract2" class="abstract">
        We study content collaboration in the creator economy, in which competing creators mutually agree to collaborate on joint content and negotiate on content production and revenue sharing. Using a game theory model with creators competing for consumers on a Hotelling line, we show that collaboration allows creators to use the jointly-produced content to moderate competition, while using their individual content to expand into new audiences. This increases content diversity but also leads to increased monetizability of content. In general, collaboration among creators has an effect of increasing the profits of creators while reducing consumer surplus. When creators create content with heterogeneous entertainment values, the creator producing content of lower entertainment value has an incentive to free ride on the collaborative content. This free riding may increase surplus for consumers (who without collaboration would watch content of low entertainment value), thereby improving creators’ profits as well as consumer surplus. Our results provide guidance to content creators, to platforms designing tools to facilitate collaborations, and to policymakers.
      </li>
    </ul>
  </li>

  <div class="underline"></div>

  <!-- Paper 3 -->
  <li>
    <a href="https://qifan-han.github.io/files/IRF_paper.pdf">Impulse Response Inferences With Existence of Repeated Roots</a>
    <ul class="subcontent">
<!--      <li>Co-authors: Not applicable</li>-->
      <li><span class="toggle-link" onclick="toggleAbstract('abstract3')">Abstract</span></li>
      <li id="abstract3" class="abstract">
        Vector Autoregression (VAR) and Local Projection (LP) are two popular methods of estimating the impulse response functions (IRFs) and conducting inferences in macroeconomic studies. However, it remains unclear which one should be a better choice in empirical practices. This paper extends existing works on the comparison between Vector Autoregression and Local Projection methods, by considering inferences when the data generating processes involve repeated roots. I show that the autoregressive estimation of impulse response functions will converge to a special type of real-valued random variable, resulting in conservativeness of the widely-used bootstrap Efron confidence interval, even when the roots are away from the unit circle. This property of conservativeness becomes even more severe in the following cases: 1) when the time series is highly persistent; and 2) when the researcher is interested in impulse response functions at intermediate or long horizons. The theoretical results are supported by Monte Carlo simulations with different values of roots in a variety of model specifications, including AR(2), AR(3) and VAR(1).
      </li>
    </ul>
  </li>

</ul>

## Working in Progress

<ul>
  <!-- WIP 1 -->
  <li class="paper-title">
    Partial Identification Under Multiple Nest Structures
  </li>
<!--  <div class="coauthors"> with Jasmine Yang and Andrey Simonov</div>-->
  <div class="abstract-row">
    <span class="toggle-link" onclick="toggleAbstract('abstract1')">Abstract</span>
  </div>
  <div id="abstract_wip1" class="abstract">
    Nested logit model is one of the most widely applied tools in discrete choice analysis, due to its ability to capture rich substitution patterns in market data. However, the researcher needs to define a nest structure ex ante, as the chosen nest is usually based on prior knowledge of the market and will be applied to all individuals. This paper discusses the identification of individual preferences, while relaxing this unique nest structure assumption and allowing for heterogeneity in individuals' recognition of the nest structures in the same market. I characterize the sharp identification region of parameters in the nested logit model, based on the coexistence of a given set of nest structures. I show in a series of Monte Carlo simulations that misspecification of the nest structure may result in the identification region not covering the true parameter, whereas the identification region solves the misspecification problem and partially identifies the parameters by allowing for multiple nest structures.
  </div>

  <div class="underline"></div>

  <!-- WIP 2 -->
  <li class="paper-title">
    Optimal Achievement System Design on Video Game Platforms
  </li>
<!--  <div class="coauthors"> with Jasmine Yang and Jerath Kinshuk</div>-->
  <div class="abstract-row">
    <span class="toggle-link" onclick="toggleAbstract('abstract2')">Abstract</span>
  </div>
  <div id="abstract2" class="abstract">
    Abstract: We study content collaboration in the creator economy, in which competing creators mutually agree to collaborate on joint content and negotiate on content production and revenue sharing. Using a game theory model with creators competing for consumers on a Hotelling line, we show that collaboration allows creators to use the jointly-produced content to moderate competition, while using their individual content to expand into new audiences. This increases content diversity but also leads to increased monetizability of content. In general, collaboration among creators has an effect of increasing the profits of creators while reducing consumer surplus. When creators create content with heterogeneous entertainment values, the creator producing content of lower entertainment value has an incentive to free ride on the collaborative content. This free riding may increase surplus for consumers (who without collaboration would watch content of low entertainment value), thereby improving creators’ profits as well as consumer surplus. Our results provide guidance to content creators, to platforms designing tools to facilitate collaborations, and to policymakers.
  </div>

  <div class="underline"></div>

  <!-- Paper 3 -->
  <li class="paper-title">
    <a href="https://qifan-han.github.io/files/IRF_paper.pdf">Impulse Response Inferences With Existence of Repeated Roots</a>
  </li>
<!--  <div class="coauthors">Co-authors: Not applicable</div>-->
  <div class="abstract-row">
    <span class="toggle-link" onclick="toggleAbstract('abstract3')">Abstract</span>
  </div>
  <div id="abstract3" class="abstract">
    Abstract: Vector Autoregression (VAR) and Local Projection (LP) are two popular methods of estimating the impulse response functions (IRFs) and conducting inferences in macroeconomic studies. However, it remains unclear which one should be a better choice in empirical practices. This paper extends existing works on the comparison between Vector Autoregression and Local Projection methods, by considering inferences when the data generating processes involve repeated roots. I show that the autoregressive estimation of impulse response functions will converge to a special type of real-valued random variable, resulting in conservativeness of the widely-used bootstrap Efron confidence interval, even when the roots are away from the unit circle. This property of conservativeness becomes even more severe in the following cases: 1) when the time series is highly persistent; and 2) when the researcher is interested in impulse response functions at intermediate or long horizons. The theoretical results are supported by Monte Carlo simulations with different values of roots in a variety of model specifications, including AR(2), AR(3) and VAR(1).
  </div>

</ul>

<!---->
<!--### [The Impact of Banning Online Gambling Livestreams: Evidence from Twitch.tv](https://qifan-han.github.io/files/JMP.pdf) (*Job Market Paper*)-->
<!--<div class="coauthors">with Jasmine Yang and Andrey Simonov</div>-->
<!---->
<!--<button class="toggle-btn" onclick="toggleAbstract('abstract1')">Abstract</button>-->
<!--<div id="abstract1" class="abstract">-->
<!--  Abstract: The necessity of content regulation on digital platforms, particularly concerning misinformation and harmful content, has sparked a growing debate. While many platforms have increasingly relied on self-regulation to address these issues, the effectiveness of such measures remains unclear, due to a potential misalignment between the incentives of the platforms and those of the regulators. We investigate the effectiveness and market consequences of self-regulation by studying Twitch's ban on online gambling livestreams in October 2022. We use a novel high-frequency panel dataset including top 6000 streamers to assess the policy impact, and leverage historical video clips, high-frequency stream titles and in-stream chats to detect banned content and streamers for identification. We find that the policy successfully decreased weekly gambling streams by 63.2% for streamers whose content were banned and a 12% among unbanned ones. However, it also resulted in a reduction of non-gambling content production, hurting content variety on the platform. Additionally, the policy had a larger impact on more popular streamers, driven by two underlying mechanisms: lower reliance on gambling content and concern for personal reputation. On the demand side, we find that the policy reduced total viewership and low-tier subscriptions among treated streamers but did not decrease revenue from their loyal viewers.-->
<!--</div>-->
<!---->
<!--<!--<div class="abstract">-->-->
<!--<!--Abstract: The necessity of content regulation on digital platforms, particularly concerning misinformation and harmful content, has sparked a growing debate. While many platforms have increasingly relied on self-regulation to address these issues, the effectiveness of such measures remains unclear, due to a potential misalignment between the incentives of the platforms and those of the regulators. We investigate the effectiveness and market consequences of self-regulation by studying Twitch's ban on online gambling livestreams in October 2022. We use a novel high-frequency panel dataset including top 6000 streamers to assess the policy impact, and leverage historical video clips, high-frequency stream titles and in-stream chats to detect banned content and streamers for identification. We find that the policy successfully decreased weekly gambling streams by 63.2% for streamers whose content were banned and a 12% among unbanned ones. However, it also resulted in a reduction of non-gambling content production, hurting content variety on the platform. Additionally, the policy had a larger impact on more popular streamers, driven by two underlying mechanisms: lower reliance on gambling content and concern for personal reputation. On the demand side, we find that the policy reduced total viewership and low-tier subscriptions among treated streamers but did not decrease revenue from their loyal viewers.-->-->
<!--<!--</div>-->-->
<!---->
<!---->
<!--### [Collaboration Among Content Creators](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4538856)-->
<!--<div class="coauthors">with Jasmine Yang and Jerath Kinshuk</div>-->
<!---->
<!--<div class="abstract">-->
<!--Abstract: We study content collaboration in the creator economy, in which competing creators -->
<!--mutually agree to collaborate on joint content and negotiate on content production and revenue-->
<!--sharing. Using a game theory model with creators competing for consumers on a Hotelling line, we-->
<!--show that collaboration allows creators to use the jointly-produced content to moderate competition,-->
<!--while using their individual content to expand into new audiences. This increases content diversity-->
<!--but also leads to increased monetizability of content. In general, collaboration among creators has an-->
<!--effect of increasing the profits of creators while reducing consumer surplus. When creators create-->
<!--content with heterogeneous entertainment values, the creator producing content of lower-->
<!--entertainment value has an incentive to free ride on the collaborative content. This free riding may-->
<!--increase surplus for consumers (who without collaboration would watch content of low entertainment-->
<!--value), thereby improving creators’ profits as well as consumer surplus. Our results provide guidance-->
<!--to content creators, to platforms designing tools to facilitate collaborations, and to policy makers.-->
<!--</div>-->
<!---->
<!---->
<!--### [Impulse Response Inferences With Existence of Repeated Roots](https://qifan-han.github.io/files/IRF_paper.pdf)-->
<!---->
<!--<div class="abstract">-->
<!--Abstract: Vector Autoregression (VAR) and Local Projection (LP) are two popular methods of estimating the impulse response functions (IRFs) and conducting inferences in macroeconomic studies. However, it remains unclear which one should be a better choice in empirical practices. This paper extends existing works on the comparison between Vector Autoregression and Local Projection methods, by considering inferences when the data generating processes involve repeated roots. I show that the autoregressive estimation of impulse response functions will converge to a special type of real-valued random variable, resulting in conservativeness of the widely-used bootstrap Efron confidence interval, even when the roots are away from the unit circle. This property of conservativeness becomes even more severe in the following cases: 1) when the time series is highly persistent; and 2) when the researcher is interested in impulse response functions at intermediate or long horizons. The theoretical results are supported by Monte Carlo simulations with different values of roots in a variety of model specifications, including AR(2), AR(3) and VAR(1).-->
<!--</div>-->
<!---->
<!---->
<!--## Working in Progress-->
<!---->
<!---->
<!--### Partial Identification Under Multiple Nest Structures-->
<!---->
<!--<div class="abstract">-->
<!--Abstract: Nested logit model is one of the most widely applied tools in discrete choice analysis, due to its ability to capture rich substitution patterns in market data. However, the researcher needs to define a nest structure ex ante, as the chosen nest is usually based on prior knowledge of the market and will be applied to all individuals. This paper discusses the identification of individual preferences, while relaxing this unique nest structure assumption and allowing for heterogeneity in individuals' recognition of the nest structures in the same market. I characterize the sharp identification region of parameters in the nested logit model, based on the coexistence of a given set of nest structures. I show in a series of Monte Carlo simulations that misspecification of the nest structure may result in the identification region not covering the true parameter, whereas the identification region solves the misspecification problem and partially identifies the parameters by allowing for multiple nest structures.-->
<!--</div>-->
<!---->
<!---->
<!--### Optimal Achievement System Design on Video Game Platforms-->
