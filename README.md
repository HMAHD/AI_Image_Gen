<div align="center">
    <h1>AI_Image_Gen</h1>
</div>
<div align="center">
    <a href="http://chat-ai-two.vercel.app/">
        <img src="public/img/logo.png" width ="250" height ="250" crossorigin>
    </a>
</div>

<br />

<div align="center">

![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)
<br />
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/5b677e607def4466b8084eb76be4f0d7)](https://app.codacy.com/app/supunlakmal/thismypc?utm_source=github.com&utm_medium=referral&utm_content=supunlakmal/thismypc&utm_campaign=Badge_Grade_Dashboard)
![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/supunlakmal/thismypc/graphs/commit-activity) [![Website thismypc.com](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](http://thismypc.com/) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/supunlakmal/thismypc/blob/master/LICENSE)
[![Gitter](https://badges.gitter.im/gitterHQ/gitter.svg)](https://gitter.im/Thismypc/community)

</div>
<div align="center">
DALL-E 2 is an AI image generator created by OpenAI, which uses deep learning to generate images based on textual descriptions. This advanced image generator can create images of almost anything that can be described in words, including complex and abstract concepts.

The technology behind DALL-E 2 is based on a deep learning framework known as GPT (Generative Pre-trained Transformer). The GPT framework is a neural network that has been pre-trained on vast amounts of data, enabling it to generate new content based on the patterns it has learned from the data.

With DALL-E 2, users can provide textual descriptions of an object or scene, and the AI model will generate a corresponding image. For example, a user can input a textual description such as "a blue cat playing the guitar on a cloud," and DALL-E 2 will generate a corresponding image that meets the given criteria.
 </div>
  
## Built With

 ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![Remix](https://img.shields.io/badge/OpenAI-%23000.svg?style=for-the-badge&logo=remix&logoColor=gold)![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)


# OpenAI Image Generator

This is a simple image generator built with Node.js and Express that uses [OpenAI's Dall-E models](https://beta.openai.com/docs/guides/images) to generate images.

## Usage

Rename the `example.env` file to `.env`.

Generate an API KEY at [OpenAI](https://beta.openai.com/) and add it to the `.env` file.

Install the dependencies

```bash
npm install
```

Run server

```bash
npm start
```

Visit `http://localhost:5000` in your browser.

The endpoint is at `POST http://localhost:5000/openai/generateimage`.
