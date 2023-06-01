
> An ordinary front-end developer who spends her days wrestling with CSS and JavaScript at work, but dreams about the exciting world of backend development at night. 
>> 	普通のフロントエンドエンジニアです。日中は仕事でCSSとJavaScriptに首をつっこみますが、夜はバックエンド開発の刺激的な世界を夢見ています。
>>>	从事前端开发的一般市民。

#### <svg xmlns="http://www.w3.org/2000/svg" width="32" height="32" viewBox="0 0 24 24"><g fill="none" stroke="#888888" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"><path d="M10 21v-6.5a3.5 3.5 0 0 0-7 0V21h18v-6a4 4 0 0 0-4-4H6.5"/><path d="M12 11V3h4l2 2l-2 2h-4m-6 8h1"/></g></svg> Contact

- Email: `hi[@]seviche.cc`
- Matrix: [@seviche:kongwoo.icu](https://matrix.to/#/@seviche:kongwoo.icu)
- Blog: [seviche.cc](https://seviche.cc) 
  ( Please feel free to leave your comments :D 


<details>
  <summary><b> Learn more about what I doing</b>
  </summary>


  
#### 👷 What I'm currently working on
{{range recentContributions 5 }}
- [{{.Repo.Name}}]({{.Repo.URL}}) - {{.Repo.Description}} ({{humanize .OccurredAt}})
{{- end}}
  <br>
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
  
#### 📓 Gists I wrote
  
{{range gists 5}}
- [{{.Description}}]({{.URL}}) ({{humanize .CreatedAt}})
{{- end}}
</details>


<details>
  <summary><b> 📜 My recent blog posts</b></summary>
  <br/>

{{range rss "https://seviche.cc/atom.xml" 5}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
{{- end}}
</details>


---

####  🖇️ See Also:
[Codeberg](https://codeberg.org/Sevichecc) | [Forgejo](https://git.kongwoo.icu/seviche) | [Codepen](https://codepen.io/sevichee)
