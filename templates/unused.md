#### ✍️ My Blog Posts
{{range rss "https://www.katzien.de/en/posts/index.xml" 20}}
- [{{.Title}}]({{.URL}}) ({{humanize .PublishedAt}})
  {{- end}}
