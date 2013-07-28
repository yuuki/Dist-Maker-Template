# Dist-Maker-Template

My Dist-Maker templates.

# SYNOPSIS

```
dim --config argyle-backend.pl init Argyle-Backend Frame8::Tmpl
```

# PREPARETION

[Dist::Maker::FromProject](https://github.com/shibayu36/p5-Dist-Maker-FromProject) generates Dist Maker template from project directory.

```
cpanm https://github.com/shibayu36/p5-Dist-Maker-FromProject.git
dim-from-project --class=Frame8::Tmpl --project-dir=/path/to/Frame8 --config-file frame8.pl > ./Dist/Maker/Template/Frame8/Tmpl.pm
```
