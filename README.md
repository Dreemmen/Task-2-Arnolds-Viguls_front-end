TO-DO:
- izmantot boilerpaltes font typography, nevis boostrap 5.0.2

problēmas:
sass kompilators neņem pretī url() parametru
_header_footer.scss -> .site-header -> background-image: url('uploads/paper_tear_66.png')
risinājums: div elements ar role=img un backgroud css

problēma:
150px atstarpe starp daziem saita elementiem, gribētos gutter
risinājums:
custom klase $large-margin