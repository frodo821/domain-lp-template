# domain-lp-template
Domain Landing Page Template Repository

Run those commands:
```
find . -type f -not -path "./.git/*" | xargs sed -i "" "s/\${domain-name}/domain.example.com/g"
find . -type f -not -path "./.git/*" | xargs sed -i "" "s/\${domain-description}/Domain description/g"
```
