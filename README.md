# HTML Resume Builder

_Forked from [mszep/pandoc_resume](https://github.com/mszep/pandoc_resume)_

### Instructions

```sh
git clone https://github.com/andybyers21/HTML-Resume-Builder
cd HTML-Resume-Builder
vim input/<your_CV>.md   # insert your own resume info
```

Substitute `vim` with your chosen code editor (vim, nano, code etc.)

The program will process whatever files are in the `input` folder to your CV. Replace `Andy_Byers_CV_Nov_2020.md`

Update CSS in `styles` to adjust the styling to your preference.

Build your CV with the command `make`

Print to PDF if required. Margins etc are all set up for an attractive PDF.

### Requirements

- pandoc 2.x

### TODO:

- [ ] Update styling to docx format output
