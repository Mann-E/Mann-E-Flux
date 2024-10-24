# Mann-E Pro : The last AI image model you'll test

In the past few months, FLUX models became a trend on the internet and specially the AI community. We, at Mann-E, tried to develop FLUX-inspired models (with similar architecture) and this repository is for tools and codes related to the Mann-E Pro model. 

This model, follows the same architecture as flux and can be used with diffusers and we currently use it in our private systems. Thanks to [RunPod](https://runpod.io) we managed to make this model in less than 480 hours on A100 and H100 GPU's!

<p align="center">
    <img src="banner.png">
</p>

## Table of Contents

* [News](#news)
* [Versions](#versions)
    * [Difference Between Proprietary (Quality/Anime) and Flux versions](#difference-between-proprietary-qualityanime-and-flux-versions)
* [Characteristics of The Model](#characteristics-of-the-model)
* [Comparison with FLUX-1[Dev]](https://github.com/Mann-E/Mann-E-Flux?tab=readme-ov-file#characteristics-of-the-model)
* [Release Date](#release-date)
* [Community](#community)
* [Donations](#donations)
* [Affiliations/Sponsorship](#affiliationssponsorships)

## News 

* __October 23rd 2024__ : Public announcements are made in various social media.

## Versions

There will be three versions available. Two of them will be completely proprietary and one will be published under _[MPSL](https://github.com/mann-e/mpsl)_ license.

1. Quality 
2. Anime 
3. Pro

### Difference Between Proprietary (Quality/Anime) and Flux versions

_Quality_ and _Anime_ versions are a little older than Flux version actually, but since we adopted the new architecture, we decided to rebuild these models to have a more unified infrastructure in our hands. Also it is important to note that both of these models are made to support some midjourney-like behavior (such as `--sref` or other flags you're using with midjourney.) and the flux version, is not like that. 

### Outputs of three models

<p align="center">
    <img src="three.png">
</p>

> From left to right Flux, Quality and Anime

## Characteristics of The Model

The model is mostly like your regular FLUX-1[Dev] model, with these differences: 

1. The images used in training, like our _Mann-E Dreams_ model, are from midjourney. So you will have a more "Midjourney like" feel using this model. 
2. The model does the inference in only 8-10 steps (exactly like our Dreams model, we're manouvering on our speed!)

## Comparison with FLUX-1[Dev]

![Analog photo](./compariosn-1.jpg)

In the photo above, we used the same prompt with both models and you can see the output. And now what about something a little more artistic? 

![Expressionism](./compariosn-2.jpg)

In the photo above, we tried to make an expressionist painting with both models. 

## Release Date 

There will be an initial release in the end of November this year. 

## Community 

* [Website](https://mann-e.com)
* [Discord](https://discord.gg/7UBd7J36B4)
* [Personal blog of Muhammadreza Haghiri](https://haghiri75.com/en)

# Donations 

* Bitcoin (BTC): `bc1qtah5agu8629kj3j3jx4w6w0nj7l4srknwg8wku`
* Doge Coin (DOGE): `D7dG7Tk4C8e4K5UdPZyoU76tXZ5LkcCVm1`
* Ethereum (ETH): `0x26abcBd0437C2F2B713D6C2d598cD4988DbacC87`
* Solana (SOL): `8VgLEL2Y6TFWgzdeK5zCMTRN23EQ4HZaK3xsoe6Jggnc`
* Telegram's Ton (TON): `UQBtQ4UBf1gOnlAfkgAo-XNNOCQ_dKlVWj3xygit7oUX4uVA`
* Tron (TRX): `TKx8FWAozZmwDsPAYcGbNnE56mJDxJ4ZWF`

## Affiliations/Sponsorships 

If you can financially support our product, provide infrastructure grants for hosting our models or want to host the model on your own platform, you can contact us at `muhammadreza.haghiri@gmail.com` and send your proposals.
