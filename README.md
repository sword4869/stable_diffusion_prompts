- [1. Architecture](#1-architecture)
- [2. install stable-diffusion](#2-install-stable-diffusion)
- [3. prompts site](#3-prompts-site)
- [4. Trick](#4-trick)
  - [4.1. Punctuation](#41-punctuation)
  - [4.2. Attention / Emphasis](#42-attention--emphasis)
  - [4.3. Famous anime characters](#43-famous-anime-characters)

# 1. Architecture

> signal meaning:
- `something` means sexual prompts which result in hentai painting.
- ~~something~~ means usefulness prompts which don't work.

> director architecture:
- tags directory: prompt keyword.
  - [common](/tags/common.md): general prompts, i.e. view, style, lighting, background...
  - [girl](/tags/girl.md): tell you how can produce a beautiful girl painting. (included nsfw content)
  - [man](/tags/man.md)
  - [negative](/tags/negative.md): negative prompts that you want to avoid.
- examples: combination of elements.
  - [negative](/examples/negative.md): common negative prompts.
  - [masterpiece](/examples/masterpiece.md): beautiful girls which don't contain explicit content.
  - [nfsw](/examples/nsfw.md): u know.
# 2. install stable-diffusion


GPU: <https://rentry.org/voldy>
<https://github.com/AbdBarho/stable-diffusion-webui-docker.git>

CPU: <http://rentry.org/cputard>


[NAI install](https://rentry.org/sdg_FAQ#how-do-i-setup-the-leaked-novelai-model)

# 3. prompts site

<https://wiki.installgentoo.com/wiki/Stable_Diffusion>

<https://lexica.art/>

<https://boards.4chan.org/h/thread/6891432>(nfsw)

# 4. Trick

## 4.1. Punctuation
Separating keywords by commas`,`, periods`.`, or even null characters ("\0") improves image quality.

!!!question space or underscore?
    Some [article](https://wiki.installgentoo.com/wiki/Stable_Diffusion) says that additional spaces between words are also discarded. Underscores ("_") are not converted to spaces. So, Replace spaces within tags with underscores, `long hair` is wrong, `long_hair` is right.

    But I have tested many times and found that the effect of using more convenient spaces is the same as that of underlining.

    So in my opinion, the syntax of prompts is `long hair`.


In addition, you can casually combine many keywords, i.e. `see-through transparent wet white skirt`.

## 4.2. Attention / Emphasis

There is a lot of confusion: Some people assert that putting a keyword in **round brackets** increases`()` its effect while putting a keyword in **square brackets**`[]` decreases its effect; Using more brackets supposedly results in a stronger change. However, others can frequently not reproduce this effect in their own prompts. As it turns out the reason for the discrepancy is that different scripts process brackets differently. For this reason: make sure to check whether the syntax of a prompt that you copy from someone else matches the syntax of the script that you use.


The **repetition of a certain keyword** seems to increase its effect regardless of the specific script that is being used. i.e. `long hair, hair over waist`


## 4.3. Famous anime characters 

Put the `copyright` tags first, then the character tags `miku`.


