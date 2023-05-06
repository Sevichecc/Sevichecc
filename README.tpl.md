
An ordinary front-end engineer who spends her days wrestling with CSS and JavaScript at work, but dreams about the exciting world of backend development at night. 

普通のフロントエンドエンジニアです。日中は仕事でCSSとJavaScriptに首をつっこみますが、夜はバックエンド開発の刺激的な世界を夢見ています。

从事前端开发的一般市民。

#### 👷 Check out what I'm currently working on
{{range recentContributions 5 }}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}

#### 🌱 My latest projects
{{range recentRepos 5 }}
- [{{.Name}}]({{.URL}}) - {{.Description}}
{{- end}}

#### 🔨 My recent Pull Requests
{{range recentPullRequests 5}}
- [{{.Title}}]({{.URL}}) on [{{.Repo.Name}}]({{.Repo.URL}}) ({{humanize .CreatedAt}})
{{- end}}

#### 🔭 Latest releases I've contributed to
{{range recentReleases 5 }}
- [{{.Name}}]({{.URL}}) ([{{.LastRelease.TagName}}]({{.LastRelease.URL}}), {{humanize .LastRelease.PublishedAt}}) - {{.Description}}
{{- end}}

#### 📜 My recent blog posts
{{range rss "https://seviche.cc/atom.xml" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}

#### 📓 Gists I wrote
{{range gists 5}}
- [{{.Description}}]({{.URL}}) ({{humanize .CreatedAt}})
{{- end}}

### See Also:
- [Codeberg](https://codeberg.org/Sevichecc)
- [Forgejo](https://git.kongwoo.icu/seviche)
- [Codepen](https://codepen.io/sevichee)
