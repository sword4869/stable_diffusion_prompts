# install stable-diffusion

<https://github.com/AbdBarho/stable-diffusion-webui-docker.git>

# prompts site

<https://wiki.installgentoo.com/wiki/Stable_Diffusion>
<https://lexica.art/>

# Trick

## Punctuation
Separating keywords by commas`,`, periods`.`, or even null characters ("\0") improves image quality.

Extra spaces at the beginning and end of your prompt are simply discarded. Additional spaces between words are also discarded. Underscores ("_") are not converted to spaces. So, Replace spaces within tags with underscores, `long hair` is wrong, `long_hair` is right.

## Attention / Emphasis
There is a lot of confusion: Some people assert that putting a keyword in **round brackets** increases`()` its effect while putting a keyword in **square brackets**`[]` decreases its effect; Using more brackets supposedly results in a stronger change. However, others can frequently not reproduce this effect in their own prompts. As it turns out the reason for the discrepancy is that different scripts process brackets differently. For this reason: make sure to check whether the syntax of a prompt that you copy from someone else matches the syntax of the script that you use.


The **repetition of a certain keyword **seems to increase its effect regardless of the specific script that is being used. i.e. `long_hair, hair_over_shoulder`


## original character

Put the `copyright` tags first, then the character tags `miku`