### Hi there 👋

<!--
**PlusLius/PlusLius** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```glsl
vec3 Bounce(vec3 pos, float time) {
  float bounce = sin(time * 4.0);

  float deform = smoothstep(-1.0, -0.0, bounce);
  deform = mix(1.5, 1.0, deform);

  pos *= vec3(deform, 1.0/deform, deform);
  pos += vec3(0.0, bounce, 0.0);
}
```
<img align="center"
         height="150em"
         src="https://github-readme-stats.vercel.app/api/top-langs?username=PlusLius&show_icons=true&include_all_commits=true&count_private=true&theme=apprentice&hide_border=true&bg_color=0D1117&layout=compact"
    />
<img
      align="center"
      src="https://github-profile-trophy.vercel.app/?username=PlusLius&theme=onedark&no-frame=true&row=1&&margin-w=20&no-bg=true"/>
