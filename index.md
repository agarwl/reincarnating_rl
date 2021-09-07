---
title: 'Deep Reinforcement Learning at the Edge of the Statistical Precipice'
layout: default
---

<style>thead { display: none; }</style>

<p class="cover" align="center"> <img src="assets/poster.png" /> </p>

Our findings call for a change in how we evaluate performance in deep RL, for which we present a more rigorous evaluation methodology, accompanied with an open-source library <a href="https://github.com/google-research/rliable">rliable</a>, to prevent unreliable results from stagnating the field.

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
