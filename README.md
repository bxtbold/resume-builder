# Resume Builder

## Installation

Refer to [this link](https://docs.rendercv.com/) for the full documentation.
```
pip install rendercv
```

## Building a PDF resume
`resume.pdf` will be generated once the command is executed.
```
cd resume-builder
make resume
```

## Building all available formats
All files will be generated in `rendercv_output` directory by default.
```
cd resume-builder
rendercv render resume_builder.yaml
```
