md-to-pdf CV_norsk.md \
  --stylesheet "https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.1.0/github-markdown.min.css" \
  --body-class "markdown-body" \
  --pdf-options '{"format":"A4","margin":{"top":"20mm","right":"20mm","bottom":"30mm","left":"20mm"},"printBackground":true}'

md-to-pdf CV.md \
  --stylesheet "https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.1.0/github-markdown.min.css" \
  --body-class "markdown-body" \
  --pdf-options '{"format":"A4","margin":{"top":"20mm","right":"20mm","bottom":"30mm","left":"20mm"},"printBackground":true}'

md-to-pdf README.md \
  --stylesheet "https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/5.1.0/github-markdown.min.css" \
  --body-class "markdown-body" \
  --pdf-options '{"format":"A4","margin":{"top":"20mm","right":"20mm","bottom":"30mm","left":"20mm"},"printBackground":true}'


pandoc "README.md" -o "project_portfolio.pdf" \
  --pdf-engine="weasyprint" \
  --css=style.css \