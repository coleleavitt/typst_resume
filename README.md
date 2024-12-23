# Typst Resume Template

A modern, professional resume template built with Typst featuring gradient styling, comprehensive sections, and automated PDF generation.

## Features

- Clean, professional layout with customizable sections
- Gradient-styled links and highlights
- Comprehensive section organization for technical resumes
- Automated PDF generation through GitHub Actions
- Built-in document metadata and copyright protection
- Optimized for technical and IT professional resumes

## Usage

1. Clone this repository
2. Modify `resume.typ` with your information
3. Compile using Typst:
```bash
typst compile resume.typ
```

## Customization

### Colors
The template uses gradient colors for visual elements. Modify the gradient parameters in the header section:
```typst
#text(gradient.linear(
  angle: 45deg,
  rgb("#ff0000"),
  rgb("#8000ff")
))
```

### Sections
Customize sections using the following format:
```typst
== *SECTION NAME*
#line(length: 100%, stroke: 0.75pt)
```

### Document Properties
Adjust document properties in the header:
```typst
#set document(
  title: "Resume",
  author: "Your Name",
  keywords: ("resume", "professional")
)
```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Acknowledgments

- Built with [Typst](https://github.com/typst/typst)
- Inspired by modern resume design principles
- Gradient styling adapted from Typst documentation

## Author

Cole Leavitt
- GitHub: [@coleleavitt](https://github.com/coleleavitt)
