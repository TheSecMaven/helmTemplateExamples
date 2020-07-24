1. helm template .
2. helm template . -f values-override.yml
3. helm template . -f values-override.yml --output-dir .
4. cat example/templates/message | tail -n +3