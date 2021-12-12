# My Analysis Options
This has a small set of rules and some ignores with flutter_lints added that I use on my projects to use it add 
```yaml
  my_analysis_options:
    git:
      url: https://github.com/IsmailAlamKhan/my_analysis_options.git
```
to your projects dev dependencies

and then in your analysis_options
```yaml
include: package:my_analysis_options/analysis_options.yaml
```
