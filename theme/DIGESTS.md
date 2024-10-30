## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/highlight.min.js"
  integrity="sha384-pGqTJHE/m20W4oDrfxTVzOutpMhjK3uP/0lReY0Jq/KInpuJSXUnk4WAYbciCLqT"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.10.0/languages/go.min.js"
  integrity="sha384-Mtb4EH3R9NMDME1sPQALOYR8KGqwrXAtmc6XGxDd0XaXB23irPKsuET0JjZt5utI"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-+9dzNYaLHp3OPspFCOJGrEwfiOV3yqeD/atUDYVt9zKUJ8IW2QxffCT2LfmGfwfW /es/languages/css.js
sha384-G44u1/pUATC8754FIKYqkCxCl9AQYnspnFxzuR3RB1YVnTvqOEofqvZNQMUWcY/1 /es/languages/css.min.js
sha384-8+x0somIBps1EZqOmOJH10vpzi+ZV5gWglDGtuGId33xzYozc4vqreUgzN/9Oka5 /es/languages/fsharp.js
sha384-RwyqgvGLMtAbdxb0JwJS46Hs0xvJDJ7ZhVOBb7vaGQOxJVPL9LYfT7FE10EgHGus /es/languages/fsharp.min.js
sha384-oQpcUGMBf+VDTHOLQ1uhPp1FgNBo0OZc9gbXGuVFwAogHlkh/Iw6cvKKgcgCQkmV /es/languages/javascript.js
sha384-3T8DJ91yCa1//uY9h8Bo4QLrgEtbz4ILN2x9kSM4QWX9/1kKu6UXC3RAbVQV85UQ /es/languages/javascript.min.js
sha384-R87hRh4kF8+iz2sB6FvLrfR0XZBohjFXeJKIXld1Eji2UVi+M2+OIgJKma/9Ko6u /es/languages/json.js
sha384-QFDPNpqtrgZCuAr70TZJFM4VCY+xNnyGKwJw2EsWIBJOVcWAns9PHcLzecyDVv+x /es/languages/json.min.js
sha384-JkFMmKMbHcXjdfHauRnREGG6i73GyMisdqNivBm4Z9m2Oc82YIu5jQtIjLa508e8 /es/languages/markdown.js
sha384-65/lNNIY+ayhHTtFznjnyZ5w2NDdZIpSEcqjss/p4ex5JamZ46FdYwDDf6IBLCmE /es/languages/markdown.min.js
sha384-dkR9Qv3ZGmcTGGFP26gmcHC9DBgRYE0XLGxF3mBXlBZaBrscW0vIiVN7oTyQmrbe /es/languages/plaintext.js
sha384-AkqanemYxn6S3BQnW2++1+xqywaq2bJfFlfiAkPNd7Yv5t9YsS8tFzVVopyOa747 /es/languages/plaintext.min.js
sha384-bJFk2tsVn5F8YUHsonGtmJRBQDWY5KfeY1yoF/KyRKPSe27EXGZozBtwNVK2ZBE/ /es/languages/scala.js
sha384-Ww9na6pFMpl0LFINRDLDfPQf6xtS31SnqKhTud2UgsqMjEYdiU0UCoL6aNcUg0Gc /es/languages/scala.min.js
sha384-pu7G6PD4gGJh1kRx2ukGFeBv0K0Z4pXkyu0AcWvxZ/qB5NkRXESMh4t0NHxMtn0I /es/languages/vbscript-html.js
sha384-hX31lddqojtc+QTe5Wx5sLiCvFSEVdP4vg2FEqwbM206W2c3qfhqz+rjC19nxA3k /es/languages/vbscript-html.min.js
sha384-Tdx2DY9ZTHx3KhVXYqOVKx3q1zOboDGlTTv8sgMlER8y4WETtqL+C4VQ7B4A0OGq /es/languages/xml.js
sha384-n9ZezaAVj8pK1BIFZQxmC1BM9yGuBNRgvsOxHMHPCXzqYd1gSYIu9KjgGEm8K57w /es/languages/xml.min.js
sha384-h6xPJgkyvp13tIs697wZHjCH20tW1aJOrvnAKiZZiATSWZp0lyLB4bAdsEhWUSze /languages/css.js
sha384-+MO3D3y/aZzZq7QMAAA5KiuAcqBZivJHFmVUXfwdBoLxEXeGTeQGsNMll4fpnegg /languages/css.min.js
sha384-3yn52MUDmkYUMfQve8G9PIMJb+OT2CCM97H3VinYelUgdRItYf1DfkxtQ8vbMHS+ /languages/fsharp.js
sha384-nYNTSA4nfVQ5esuMpVP111sGLunWJMnBXsYufX4ExWifybw5u48EAUxr+SsgIowR /languages/fsharp.min.js
sha384-p/utwvqrRVOLlz0BjJ0BCGCb2liTDipfz47/QmGXz9hoPIjCKYEgmYUC30VmGgZy /languages/javascript.js
sha384-L/XmDiyusXomLRGcRmcBpPlboRFjpQNV747OJvg+sEOpgGYvUsNwcC4JLNQ2dI6O /languages/javascript.min.js
sha384-psmmPlbfEWGyvRapexDqkVTgNz7Y1xvlGdLNWQSafI4GFQYFDXPZxVXH1laU4n6l /languages/json.js
sha384-Bb6DhE3tUpBROwypL78TbhRUs9QbCt2GxcxVSYglt2l3MefrYkm4CfwjfWhRfQaX /languages/json.min.js
sha384-TVvUXbmPgdS59xZSFUeyNQ1vUkeCbBpuMj3qlzdEwdQhoO5F/WNdI94UEw8g7Enp /languages/markdown.js
sha384-sFh+6oaRBb6kdaMLf8x7qeH7NTvm2u1Ta6PtI0S8hoA+bP7UtHCyKFzaI1JBXwhT /languages/markdown.min.js
sha384-v4qiQbdZu8obdLOFoHrZxA44mmxnjZUelyHe7A6RuqmckxO5weYQVrN8Dx2UpAR1 /languages/plaintext.js
sha384-hE+znpd5xggEBW6IccZoCI0mgFHAfLVuqT/7aW8RakaQ4UJnI058SfIX3lhdGxtE /languages/plaintext.min.js
sha384-/YpJjx5RnzUuJcVaJYIEU44EkoCD/KX5CiVM8Aj7wfkZj6EYw9g3CPauWCDI+ljG /languages/scala.js
sha384-SA6LxB7n4Y1G9cv1TTU9P9QCpQXJaNURCzOyoGjV/D9gkhcHYSsYERw8IVffZ8uD /languages/scala.min.js
sha384-R2QKmi7N0DVttqhNpU5wkftWRTVN+FlOnv18+Bk/zxM/V8qkRBU4yUCpsr9AdK+x /languages/vbscript-html.js
sha384-q0sJ1YFiPW+i+XVme9b3M6adegU2pnXPpwhLvGukidQZIkV9QIzBFdSCkf4LjQAf /languages/vbscript-html.min.js
sha384-QAL2h4IMgQaJUJjUy0dSWdAut7o/A272ai8qOsJ8SSm9KMxkdLgH7oGfLGft/EJ0 /languages/xml.js
sha384-CN3No+n1UZXCFYyl+ge5yAPGTNGuH23BdIsFJxntDmEYL94AmoZlNBHGSdjVSjKG /languages/xml.min.js
sha384-uhQ74AqidOfp2sRWvMRymi441y2HzXwpgFYX3D3bgx+JH+PcCMH2In4ufiA25ckO /highlight.js
sha384-JsRQFe7fxrZ/RP23XHc25Yr08F9PWcA+N+sPIYZOcofwgMXn41NYI3emC750EiwF /highlight.min.js
```

