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

{{range rss "https://seviche.cc/atom.xml" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}
