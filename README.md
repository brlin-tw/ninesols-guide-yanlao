# Subtle hints to help beat Yanlao

Help you beat the Yanlao boss without being spoiled too much to a point it is no
longer challenging.

![Article branding image that shows a mechanical claw of the claw machine arcade game in Taiwan](branding.512px.jpg "A mechanical claw of the claw machine arcade game in Taiwan")

<https://gitlab.com/brlin/ninesols-guide-yanlao>  
[![The GitLab CI pipeline status badge of the project's `main` branch](https://gitlab.com/brlin/ninesols-guide-yanlao/badges/main/pipeline.svg?ignore_skipped=true "Click here to check out the comprehensive status of the GitLab CI pipelines")](https://gitlab.com/brlin/ninesols-guide-yanlao/-/pipelines) [![GitHub Actions workflow status badge](https://github.com/brlin-tw/ninesols-guide-yanlao/actions/workflows/check-potential-problems.yml/badge.svg "GitHub Actions workflow status")](https://github.com/brlin-tw/ninesols-guide-yanlao/actions/workflows/check-potential-problems.yml) [![pre-commit enabled badge](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white "This project uses pre-commit to check potential problems")](https://pre-commit.com/) [![REUSE Specification compliance badge](https://api.reuse.software/badge/gitlab.com/brlin/ninesols-guide-yanlao "This project complies to the REUSE specification to decrease software licensing costs")](https://api.reuse.software/info/gitlab.com/brlin/ninesols-guide-yanlao)

## Table of contents

[TOC]

## Hints

This section documents the hints in various markup languages used in different
platforms:

### Markdown(with non-standard spoiler tags)

```markdown
Some hints that may help you in this fight:

* Avoid dodging the <span class="spoiler">claw</span> attacks which is not the designated solution of these attack patterns.
* The <span class="spoiler">Swift Rise</span> skill reduces the vulnerability window after you are knocked down by the boss's attack.
* The <span class="spoiler">Quick Dose</span> jade reduces the vulnerability window when you're healing.
* The <span class="spoiler">Revival</span> jade gives you a second chance when receiving too much Direct Damage.
* It is possible to increase your <span class="spoiler">maximum health</span> by using a certain in-game mechanic, try to discover/make good use of it.
* The <span class="spoiler">Immortal Dash</span> and the <span class="spoiler">Air Dash</span> skill give you I-frames to dodge the <span class="spoiler">laser beam</span> attacks during <span class="spoiler">the second phase</span>.
* The laser portion of the <span class="spoiler">consecutive sniping and crimson claw laser attack pattern</span> can be avoided in at least two ways while one gives you a big attack window, observe and use the surrounding environments!
* As a last resort, switch to Story Mode and reduce the received damage modifier to allow you more time to practice, you can tweak back to normal difficulty at any time!

Good luck!
```

### Discord-flavored Markdown

```discord
Some hints that may help you in this fight:

* Avoid dodging the ||claw|| attacks which is not the designated solution of these attack patterns.
* The ||Swift Rise|| skill reduces the vulnerability window after you are knocked down by the boss's attack.
* The ||Quick Dose|| jade reduces the vulnerability window when you're healing.
* The ||Revival|| jade gives you a second chance when receiving too much Direct Damage.
* It is possible to increase your ||maximum health|| by using a certain in-game mechanic, try to discover/make good use of it.
* The ||Immortal Dash|| and the ||Air Dash|| skill give you I-frames to dodge the ||laser beam|| attacks during ||the second phase||.
* The laser portion of the ||consecutive sniping and crimson claw laser attack pattern|| can be avoided in at least two ways while one gives you a big attack window, observe and use the surrounding environments!
* As a last resort, switch to Story Mode and reduce the received damage modifier to allow you more time to practice, you can tweak back to normal difficulty at any time!

Good luck!
```

### Steam-flavored BBCode

```bbcode
Some hints that may help you in this fight:

[list]
    [*] Avoid dodging the [spoiler]claw[/spoiler] attacks which is not the designated solution of these attack patterns.
    [*] The [spoiler]Swift Rise[/spoiler] skill reduces the vulnerability window after you are knocked down by the boss's attack.
    [*] The [spoiler]Quick Dose[/spoiler] jade reduces the vulnerability window when you're healing.
    [*] The [spoiler]Revival[/spoiler] jade gives you a second chance when receiving too much Direct Damage.
    [*] It is possible to increase your [spoiler]maximum health[/spoiler] by using a certain in-game mechanic, try to discover/make good use of it.
    [*] The [spoiler]Immortal Dash[/spoiler] and the [spoiler]Air Dash[/spoiler] skill give you I-frames to dodge the [spoiler]laser beam[/spoiler] attacks during [spoiler]the second phase[/spoiler].
    [*] The laser portion of the [spoiler]consecutive sniping and crimson claw laser attack pattern[/spoiler] can be avoided in at least two ways while one gives you a big attack window, observe and use the surrounding environments!
    [*] As a last resort, switch to Story Mode and reduce the received damage modifier to allow you more time to practice, you can tweak back to normal difficulty at any time!
[/list]

Good luck!
```

## References

The following external materials are referenced during the writing of this article:

* [A guide to Markdown on Discord.](https://gist.github.com/matthewzring/9f7bbfd102003963f9be7dbcf7d40e51)
  Explains how to write proper list markups on Discord servers.
* [Markdown Github to BBCode Feral converter](https://feralhosting.github.io/)  
  Features a utility to automatically convert GitHub-flavored Markdown(GFM) to BBCode.
* [BBCode - Wikipedia](https://en.wikipedia.org/wiki/BBCode)  
  Explains the basic information of the BBCode markup language.
* [highlight.js/SUPPORTED_LANGUAGES.md at main · highlightjs/highlight.js](https://github.com/highlightjs/highlight.js/blob/main/SUPPORTED_LANGUAGES.md)  
  Explains the language hints used for the code fences markup in Markdown
  applications powered by [highlight.js](https://highlightjs.org/).
* [html - How can I create spoiler text? - Stack Overflow](https://stackoverflow.com/questions/28615544/how-can-i-create-spoiler-text)  
  Explains how to implement spoiler text formatting on HTML documents using CSS.

## Licensing

Unless otherwise noted(individual file's header/[REUSE DEP5](.reuse/dep5)), this product is licensed under [the 4.0 International version of the Creative Commons Attribution-ShareAlike license](https://creativecommons.org/licenses/by-sa/4.0/), or any of its more recent versions of your preference.

This work complies to [the REUSE Specification](https://reuse.software/spec/), refer the [REUSE - Make licensing easy for everyone](https://reuse.software/) website for info regarding the licensing of this product.

<!-- markdownlint-disable no-space-in-emphasis -->
<style>
    /* Configure spoiler text formatting on supported Markdown applications */
    .spoiler{
        background-color: gray;
        color: transparent;
        user-select: none;
    }
    .spoiler:hover{
        background-color: inherit;
        color: inherit;
    }
</style>
