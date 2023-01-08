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
  
```
pub   ed25519/0x4444777733334444 2022-05-16 [C] [expires: 2025-01-07]
      Key fingerprint = ABCB A12F 1A8E 3CCC F10B  5109 4444 7777 3333 4444
uid                   [ultimate] 藍+85CD <kwa[a]kwaa.dev>
uid                   [ultimate] 藍+85CD (GitHub) <50108258+kwaa[a]users.noreply.github.com>
uid                   [ultimate] [jpeg image of size 889]
sub   ed25519/0xBCB0111111111111 2022-12-24 [S] [expires: 2025-01-07]
sub   ed25519/0x6656222222222222 2022-10-27 [A] [expires: 2025-01-07]
sub   cv25519/0x6EC06EC06EC06EC0 2022-10-05 [E] [expires: 2025-01-07]

# via keys.openpgp.org
gpg --keyserver hkps://keys.openpgp.org --recv-keys 4444777733334444
# via kwaa.dev
gpg --fetch-keys https://kwaa.dev/pgp/4734.pgp
```

</details>
