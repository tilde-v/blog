{
    "date": "{{ .Date }}",
    "title": "{{ replace .File.ContentBaseName "-" " " | title }}",
    "draft": true,
    "categories": [],
    "tags": []
}
