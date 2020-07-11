# This is my CV implemented in Markdown using Pandoc

To build the HTML page install _pandoc_ and run the following command:
`pandoc -c styles.css -s index.md -o index.html`

For a PDF build run the following command:
`pandoc -t html --css styles.css index.md -o output.pdf`

Due to PDF ignoring @media style, a temporary work-around is to comment out __@media only__ part to get two-column representation.
