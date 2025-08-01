<p align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOWEzenQ2b3ZrdzB1OTFsc2V3cmN0ZDRjb2hoMGVjeWsxdzEwbXcyciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/13Z5kstwARnPna/giphy.gif" alt="Mecha HUD" width="100%">
</p>

<div align="center">
<samp>
<pre>
██╗  ██╗ █████╗ ██╗   ██╗ █████╗  ██╗  ██╗  ██╗  ██╗
██║  ██║██╔══██╗╚██╗ ██╔╝██╔══██╗ ╚██╗██╔╝  ╚██╗██╔╝
███████║███████║ ╚████╔╝ ███████║  ╚███╔╝    ╚███╔╝
██╔══██║██╔══██║  ╚██╔╝  ██╔══██║  ██╔██╗    ██╔██╗
██║  ██║██║  ██║   ██║   ██║  ██║ ██╔╝ ██╗  ██╔╝ ██╗
╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝ ╚═╝  ╚═╝  ╚═╝  ╚═╝
</pre>
</samp>
</div>

<p align="center">
  <code>&lt;ACCESSING MAIN DATABASE.../&gt;</code>
  <br>
  <strong>Subject Name:</strong> HayaXx
  <br>
  <strong>Designation:</strong> Digital Ronin [ Fullstack Developer | UI/UX Architect ]
  <br>
  <strong>Primary Directive:</strong> Crafting elegant digital experiences where logic and aesthetics converge.
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/HayaXx/HayaXx/main/assets/neon-divider.svg" />
</p>

# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          #  - public_repo
          #  - read:project
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Jakarta
          plugin_activity: yes
          plugin_activity_days: 14
          plugin_activity_filter: all
          plugin_activity_limit: 5
          plugin_activity_load: 300
          plugin_activity_visibility: all
          plugin_habits: yes
          plugin_habits_charts_type: classic
          plugin_habits_days: 18
          plugin_habits_facts: yes
          plugin_habits_from: 200
          plugin_habits_languages_limit: 8
          plugin_habits_languages_threshold: 0%
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year
          plugin_projects: yes
          plugin_projects_limit: 4
          plugin_reactions: yes
          plugin_reactions_display: absolute
          plugin_reactions_limit: 200
          plugin_reactions_limit_discussions: 100
          plugin_reactions_limit_discussions_comments: 100
          plugin_reactions_limit_issues: 100
          plugin_screenshot: yes
          plugin_screenshot_background: yes
          plugin_screenshot_mode: image
          plugin_screenshot_selector: body
          plugin_screenshot_title: Screenshot
          plugin_screenshot_viewport: {
  "width": 1280,
  "height": 1280
}

<p align="center">
  <img src="https://raw.githubusercontent.com/HayaXx/HayaXx/main/assets/neon-divider.svg" />
</p>


<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">⌬ Core Modules // Tech Stack ⌬</h3>
      <p align="center">
        <a href="#"><img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></a>
        <a href="#"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"></a>
        <a href="#"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"></a>
        <br>
        <a href="#"><img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"></a>
        <a href="#"><img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"></a>
        <a href="#"><img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"></a>
        <br>
        <a href="#"><img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"></a>
        <a href="#"><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">⛶ System Diagnostics // GitHub Stats ⛶</h3>
      <p align="center">
        <img align="center" src="https://github-readme-stats.vercel.app/api?username=HayaXx&show_icons=true&locale=en&theme=github_dark&count_private=true" alt="HayaXx's GitHub Stats" />
        <br>
        <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=HayaXx&locale=en&layout=compact&theme=github_dark" alt="Top Languages" />
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/HayaXx/HayaXx/main/assets/neon-divider.svg" />
</p>

<h3 align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGZqMmRiaTRwY3A0ZGRtdWlqM3BjcW50bmF3bnR3NW9hdmVsc3B4eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/w7i3c5g05s8ZK/giphy.gif" width="30" />
  &nbsp;Manually Flagged Missions // Featured Projects
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGZqMmRiaTRwY3A0ZGRtdWlqM3BjcW50bmF3bnR3NW9hdmVsc3B4eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/w7i3c5g05s8ZK/giphy.gif" width="30" />
</h3>

<p align="center">
  <a href="https://github.com/HayaXx/NAMA_REPO_UNGGULAN_1">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=HayaXx&repo=NAMA_REPO_UNGGULAN_1&theme=github_dark" />
  </a>
  <a href="https://github.com/HayaXx/NAMA_REPO_UNGGULAN_2">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=HayaXx&repo=NAMA_REPO_UNGGULAN_2&theme=github_dark" />
  </a>
</p>


<p align="center">
  <img src="https://raw.githubusercontent.com/HayaXx/HayaXx/main/assets/neon-divider.svg" />
</p>

> <p align="center"><i>“Man fears the darkness, and so he scrapes away at the edges of it with fire.”</i></p>
> <p align="center"><strong>— Rei Ayanami (Neon Genesis Evangelion)</strong></p>


<p align="center">
  <img src="https://raw.githubusercontent.com/HayaXx/HayaXx/main/assets/neon-divider.svg" />
</p>

<h3 align="center">Establish Comms Link // Find Me</h3>
<p align="center">
  <a href="https://www.linkedin.com/in/username_anda" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="https://twitter.com/username_anda" target="_blank">
    <img src="https://img.shields.io/badge/X (Twitter)-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)"/>
  </a>
  &nbsp;
  <a href="https://www.instagram.com/username_anda" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  &nbsp;
  <a href="mailto:emailanda@example.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

<p align="center">
  <img src="https://media1.tenor.com/m/tY42-94yS2AAAAAC/see-you-space-cowboy.gif" alt="See You Space Cowboy" width="300"/>
</p>
<p align="center"><code>&lt;...TRANSMISSION END.../&gt;</code></p>
