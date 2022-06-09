---
title: "Staff"
date: 2022-06-09T08:23:17+02:00
draft: false
---



## List of employees


{{ range .Site.Data.staff }}
	<h2>{{ .name }}</h2>
	<p>{{ .email }}</p>
{{end}}
