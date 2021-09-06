---
title: 'Deep Reinforcement Learning at the Edge of the Statistical Precipice'
layout: default
---

<style>thead { display: none; }</style>

<p class="cover" align="center"> <img src="assets/poster.png" /> </p>

Deep reinforcement learning (RL) algorithms are predominantly evaluated by comparing their relative performance on a large suite of tasks. Most published results on deep RL benchmarks compare point estimates of aggregate performance such as mean and median scores across tasks, ignoring the statistical uncertainty implied by the use of a finite number of training runs. Beginning with the Arcade Learning Environment (ALE), the shift towards computationally-demanding benchmarks has led to the practice of evaluating only a small number of runs per task, exacerbating the statistical uncertainty in point estimates. In this paper, we argue that reliable evaluation in the few run deep RL regime cannot ignore the uncertainty in results without running the risk of slowing down progress in the field. We illustrate this point using a case study on the Atari 100k benchmark, where we find substantial discrepancies between conclusions drawn from point estimates alone versus a more thorough statistical analysis. With the aim of increasing the field's confidence in reported results with a handful of runs, we advocate for reporting interval estimates of aggregate performance and propose performance profiles to account for the variability in results, as well as present more robust and efficient aggregate metrics, such as interquartile mean scores, to achieve small uncertainty in results. Using such statistical tools, we scrutinize performance evaluations of existing algorithms on other widely used RL benchmarks including the ALE, Procgen, and the DeepMind Control Suite, again revealing discrepancies in prior comparisons. Our findings call for a change in how we evaluate performance in deep RL, for which we present a more rigorous evaluation methodology, accompanied with an open-source library <a href="https://github.com/google-research/rliable">rliable</a>, to prevent unreliable results from stagnating the field.

Citing
------
To cite this paper, please use the following reference:

    @article{agarwal2021deep,
      title={Deep Reinforcement Learning at the Edge of the Statistical Precipice},
      author={Agarwal, Rishabh and Schwarzer, Max and Castro, Pablo Samuel and Courville, Aaron and Bellemare, Marc G},
      journal={arXiv preprint arXiv:2108.13264},
      year={2021}
    }


## Authors

<div style="text-align: left;">
{%- for person in site.data.authors -%}
<div class="person">
  <img src="{{ person.image }}" />
  <a href="{{ person.url | relative_url }}">{{ person.name }}</a><br>
  <span>{{ person.title | replace: '&', '<br>' }}</span>
  <!--span>({{ person.topics }})</span-->
</div>
{%- endfor -%}
</div>


<p style="text-align: left">
For questions, please contact us at:
<a href="mailto:rishabhagarwal@google.com">rishabhagarwal@google.com</a>.
</p>
