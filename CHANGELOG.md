# Change Log

All notable changes to the "erb-types" extension will be documented in this file.

## [0.0.1]

- Initial release
- Created erb.tmLanguage.json
- Created js.erb.tmLanguage.json

## [0.1.0]

- Added LaTeX support, pdf.erb
    - Created language-configurations/pdf.erb.configuration.json
    - Created syntaxes/pdf.erb.tmLanguage.json
- Reorganized files
    - Moved language-configuration.json -> language-configurations/js.erb.configuration.json
- Edited README.md
    - Description of new language and added contributions

## [0.1.1]
- Added BibTeX and TeX support
    - Created language-configurations/tex.erb.configuration.json
    - Created syntaxes/tex.erb.tmLanguage.json
    - Created language-configurations/bibtex.erb.configuration.json
    - Created syntaxes/bibtex.erb.tmLanguage.json
- Added example.tmLanguage file
    - Example file that in conjunction with example.configuration, with both anyone should be able to contribute
- Renamed pdf.erb to latex.erb, since pdf.erb is from an specific gem and the syntax doesn't depend on the gem
    - Moved language-configurations/pdf.erb.configuration.json -> language-configurations/latex.erb.configuration.json
    - Moved syntaxes/pdf.erb.configuration.json -> syntaxes/latex.erb.configuration.json
- Edited README.md
    - Description of new languages BibTeX (ERB) and TeX (ERB)
