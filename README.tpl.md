![藍](ai.webp)

<details>
  <summary><b>🌠 About Me</b></summary>
  <br/>

- 藍
  - Nickname
  - a.k.a あい, Ai
- Earthling.
- Front-end Developer.

</details>
<details>
  <summary><b>🏗️ I'm currently working on</b></summary>
  <br/>

{{range recentContributions 10}}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}

</details>
<details>
  <summary><b>✨ Latest projects</b></summary>
  <br/>

{{range recentRepos 10}}
- [{{.Name}}]({{.URL}}) - {{.Description}}
{{- end}}

</details>
<details>
  <summary><b>🎨 Recent Pull Requests</b></summary>
  <br/>

{{range recentPullRequests 10}}
- [{{.Title}}]({{.URL}}) on [{{.Repo.Name}}]({{.Repo.URL}}) ({{humanize .CreatedAt}})
{{- end}}

</details>
<details>
  <summary><b>📜 Recent posts</b></summary>
  <br/>

{{range rss "https://kwaa.dev/atom.xml" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}

👉 read more at [./kwaa.dev](https://kwaa.dev)

</details>
<details>
  <summary><b>📧 Contact</b></summary>
  <br/>

- Blog: https://kwaa.dev
- Telegram: @kwaabot
- Discord: 917#1929

👋 If u want to say hello, I'll be happy to meet u.

</details>
<details>
  <summary><b>🔒 PGP Public Key</b></summary>
  <br/>

> User Key: `8964 78D9 78EB 0000`

> Code Signing Key: [`2E18 657D 8C32 CC47`](https://github.com/kwaa.gpg)

</details>